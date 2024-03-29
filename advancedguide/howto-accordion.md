# Collapsible Sections / Accordions

Collapsible sections or "accordions" are another way to organize long documents or pages, while taking up less screen space. Readers can flip between the sections of your document by clicking or tapping to expand one section of the document at a time. Below is an example of collapsed and expanded accordion respectively.

![image](../.gitbook/assets/accord1.png)

![image](../.gitbook/assets/accord2.png)

To create collapsible sections in your content: 

1. Under Text Format, ensure your page is set to "Full HTML" instead of "Filtered HTML"
2. Click the _Source_ button on the editor toolbar to switch the editor to source editing mode

![image](../.gitbook/assets/source2.png)

3. Copy and paste the following markup into the source editor

![image](../.gitbook/assets/add-accordion-code.png)

4. Adjust the number and description of the sections to suit your content. When adding a new accordion section to your code, remember to update the values in the new section that reference "headingThree" or "collapseThree" so that the new section has unique values on the page (e.g. headingFour, collapseFour).

## Markup

The following markup will show three accordion sections. All sections are closed when users initially load the page.

```html
<div class="panel-group" id="accordion">
  
  <div class="panel panel-default">
    <div class="panel-heading" id="headingOne">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
          Collapsible Group Item #1
        </a>
      </h4>
    </div>
    <div id="collapseOne" class="panel-collapse collapse" aria-labelledby="headingOne" role="region">
      <div class="panel-body">
        ...
      </div>
    </div>
  </div>
  
  <div class="panel panel-default">
    <div class="panel-heading" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          Collapsible Group Item #2
        </a>
      </h4>
    </div>
    <div id="collapseTwo" class="panel-collapse collapse" aria-labelledby="headingTwo" role="region">
      <div class="panel-body">
        ...
      </div>
    </div>
  </div>
  
  <div class="panel panel-default">
    <div class="panel-heading" id="headingThree">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Collapsible Group Item #3
        </a>
      </h4>
    </div>
    <div id="collapseThree" class="panel-collapse collapse" aria-labelledby="headingThree" role="region">
      <div class="panel-body">
        ...
      </div>
    </div>
  </div>
  
</div>
```

If you wanted the first accordion section to appear open for users by default, you would update the first section as follows:

  ```html
  <div class="panel panel-default">
    <div class="panel-heading" id="headingOne">
      <h4 class="panel-title">
        <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          Collapsible Group Item #1
        </a>
      </h4>
    </div>
    <div id="collapseOne" class="panel-collapse collapse in" role="region" aria-labelledby="headingOne">
      <div class="panel-body">
        ...
      </div>
    </div>
  </div>
  ```
  
  To add additional (closed) sections, add the following code directly below the last accordion section and above the closing </div> tag. Remember to update any values referencing "headingThree" or "collapseThree" so it is unique on the page (e.g. headingFour, collapseFour).

  ```html
  <div class="panel panel-default">
    <div class="panel-heading" id="headingThree">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Collapsible Group Item #3
        </a>
      </h4>
    </div>
    <div id="collapseThree" class="panel-collapse collapse" role="region" aria-labelledby="headingThree">
      <div class="panel-body">
        ...
      </div>
    </div>
  </div>
```

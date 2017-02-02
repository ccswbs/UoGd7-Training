# How to Add Course Outlines

The course outlines feature allows **Content Creators** to create and
edit course outlines. Anonymous users can browse through these outlines
in a listing page view and find more details about a specific course.

## Creating Terms for Vocabularies

Before creating course outlines, add terms to the following vocabularies:

* **Course outline category:** Create terms in this vocabulary to filter
course outlines by area of study (e.g. Philosophy or History).

* **Course outline term:** Use terms in this vocabulary to filter and group
course outlines by academic term. The default values are Fall, Winter, and Spring.

* **Course outline subject:** A list of course subjects (e.g. HIST, PSYC).

* **Course outline academic department:** A list of academic departments.

## To Add Course Outlines

1. On the Administration bar, select `Add Content`.
2. Select `Course Outline`.
3. Enter a **Course name** and **Course code**.
4. Fill in any optional fields.
5. Attach the course outline document.
6. Click `Save` when you are done.

## Add a menu link

1. On the Administration bar, select `Structure` > `Menus`.
2. Select **Main menu**: `add link`. 
3. Enter a menu link title (e.g. Course outlines).
4. Enter the link path `course-outlines`.

To create a menu link that lists course outlines for a single term,
enter the path `course-outlines/[term-id]`, where [term-id] is the
term ID of a term in the Course outline term vocabulary.

## Filtering by category

1. On a course outline listing page, click `Customize this page`.
2. Select the cog icon (settings) for "View: C01 - Listing page for Mulitple Course Outlines"
3. In the "Category" field, enter the term ID of a term in the Course outline category vocabulary.



#bronzeAgeComics

##Attribute Values

**ID attributes**

*banner*
>Applied to a DIV tag. Displays the title of the current page.

*main*
>Applied to a DIV tag. All non-head content below the title banner.

*menu*
>Applied to a SECTION tag. A list of titles. It may contain one or more UL items.

*content*
>Applied to a SECTION tag. A container that displays the content of a page.

*primary*
>Applied to a DIV tag. Enables CSS styles to be applied to the SECTION.id="content".

**Class attributes**

*Search*
>Applied to a FORM tag. A templated query link to search for issues matching specified criteria. The element must be set to FORM.method="get".

*PeriodicalSeries*
>Applied to a FORM tag. A templated query link to search for titles matching specified criteria. The element must be set to FORM.method="get".

*ComicIssue*
>Applied to a FORM tag. A non-idempotent update link that posts a new title with the specified metadata. The element must be set to FORM.method="post".

*PeriodicalSeries*
>Applied to a FORM tag. A templated query link to search for titles matching specified criteria. The element must be set to FORM.method="get".


**Name attributes**

*id*
>Applied to an INPUT[text] element. The user-created uri of the title.

*name*
>Applied to an INPUT[text] element. The formal title of a specific title.

*imprint*
>Applied to an INPUT[text] element. The publisher of a title.

*startyear*
>Applied to an INPUT[int] element. The year the title began publication. Must be a four digit year.

*description* 
>Applied to a TEXT AREA element. The description of the title.

*writer*
>Applied to an INPUT[text] element. The user wants to see only titles that contain this text.

**Rel attributes**

*index*
>Applied to an A tag. A reference to the starting URI for the application.

*stylesheet*
>Applied to an A tag. A reference to the CSS stylesheet.

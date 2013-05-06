
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

*create-title*
>Applied to a FORM tag. A non-idempotent update link that posts a new title with the specified metadata. The element must be set to FORM.method="post".

*create-issue*
>Applied to a FORM tag. A non-idempotent update link that posts a new issue with the specified metadata. The element must be set to FORM.method="post".

**Class attributes**

*Search*
>Applied to a FORM tag. A templated query link to search for issues matching specified criteria. The element must be set to FORM.method="get".

*PeriodicalSeries*
>Applied to a FORM tag. A templated query link to search for titles matching specified criteria. The element must be set to FORM.method="get".

*ComicIssue*
>Applied to a FORM tag. A non-idempotent update link that posts a new title with the specified metadata. The element must be set to FORM.method="post".


**Name attributes**

*id*
>Applied to an INPUT[text] element. The user-created uri of the title.

*name*
>May be applied to an INPUT[text] element for titles and/or applied to an INPUT[text] element for issues. The formal title of a specific title, or the issue number of a specific issue.

*imprint*
>Applied to an INPUT[text] element. The publisher of a title.

*startyear*
>Applied to an INPUT[int] element. The year the title began publication. Must be a four digit year.

*description* 
>Applied to a TEXT AREA element. The description of the title.

*writer*
>Applied to an INPUT[text] element. The person responsible for the story of the issue.

*penciler*
>Applied to an INPUT[text] element. The person responsible for rendering the story of the issue into visual form.

*coverartist*
>Applied to an INPUT[text] element. The person responsible for illustrating the front cover of the issue.

*colorist*
>Applied to an INPUT[text] element. The person responsible for adding color to the issue.

*letterer*
>Applied to an INPUT[text] element. The person responsible for writing the text of the issue.

*inker*
>Applied to an INPUT[text] element. The person responsible for using black ink to outline, shadow, and embellish the pencil illustrations of the issue (not tracing).

*editor*
>Applied to an INPUT[text] element. The person responsible for editing the content of the issue.

*datepub*
>Applied to an INPUT[int] element. The year the issue was published. Must be a four digit year between 1970 and 1985 (the Bronze Age of Comic Books).

*image*
>Applied to an INPUT[url] element. A link to the cover image of the issue.

**Rel attributes**

*index*
>Applied to an A tag. A reference to the starting URI for the application.

*stylesheet*
>Applied to an A tag. A reference to the CSS stylesheet.

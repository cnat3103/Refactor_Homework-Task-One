# Refactor_Homework-Task-One
Horiseon refactor
Notes on work undertaken for webpage to meet accessibility standards

WHEN I view the source code THEN I find semantic HTML elements
Note the following changes:
    - inclusion of <section> element to denote thematic grouping of content.
    - use of comments to aid source code reader in understanding layout of content.
    - deletion of closing tag </img> (previously line 68) as self closing tag does not require closing tag.
    - inclusion of line spacing between sections and divs to signal break in content.

WHEN I view the structure of the HTML elements THEN I find that the elements follow a logical structure independent of styling and positioning
    - source code spaced and grouped, where relevant, into sections indicating consistency in thematic content across groupings.

WHEN I view the image elements THEN I find accessible alt attributes
    - <img> elements all have alt attributes with clear and concise description of image content.

WHEN I view the heading attributes THEN they fall in sequential order
    - heading attributes follow logically according to section and fall into sequential order.
    - h2 footer changed in source code to h4.

WHEN I view the title element THEN I find a concise, descriptive title
    - Title of document changed to concise description of page content.

Additional Notes:
    - change colour of benefits class for consistency and accessibility.
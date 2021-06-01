# Refactoring Homework
This homework is centered around a marketing agency that must be refactored. The focus is on accessibility improvements and code quality/efficiency. 

# general refactoring approach
In the homework my main goals were 
    -to replace as many div tags with semantic tags as was reasonably and positively possible
    -to reduce css repetition through seperation of class and id tags in the html
    -adding seo improvements through meta tags and title tags

The css file was restructured to show related selector patterns together. 

# Specific refactors

# semantic tags used;
    header
    nav
    figure
    section
    article
    footer

# tag classes added;
    content-container: This allowed for general properties to be specified without repetition in        multiple selectors

# tag classes changed;
    benefit-xxxx -> benefit: by seperating the benefit from the id name xxxx I can provide generic properties for each benefit and do some individual specification with the id that was created too.

    seo -> #seo: since this tag is unique it is better suited as an id tag not a class

# id's that were added;
    benefit-lead: Added for any overrides needed for the first benefit about lead generation
    benefit-brand: Added for any overrides needed for the second benefit about brand awareness
    benefit-cost: Added for any overrides needed for the third benefit about cost management

# Refactoring Homework
This homework is centered around a marketing agency website that must be refactored. The focus is on accessibility improvements and code quality/efficiency. The website is shown below;

![Alt text](screenshot.png?raw=true "Agency website")

# General Refactoring Approach
In the homework my main goals were 
    -to replace as many div tags with semantic tags as was reasonably and positively possible
    -to reduce css repetition through separation of class and id tags in the html
    -adding seo improvements through meta tags and title tags

The css file  was commented, streamlined into general classes and id's and was restructured to show related selector patterns together. Where the html selectors had been replaced with specific semantic tags, the css selector was made as general as possible. 
    Example: .header {} -> header {}

# Specific refactors

## semantic tags used;
    header
    nav
    figure
    section
    article
    footer

## tag classes added;
    content-container: This allowed for general properties to be specified without repetition in        multiple selectors

## tag classes changed;
    benefit-xxxx -> benefit: by seperating the benefit from the id name xxxx I can provide generic properties for each benefit and do some individual specification with the id that was created too.

    seo -> #seo: since this tag is unique it is better suited as an id tag not a class

## id's that were added;
    benefit-lead: Added for any overrides needed for the first benefit about lead generation
    benefit-brand: Added for any overrides needed for the second benefit about brand awareness
    benefit-cost: Added for any overrides needed for the third benefit about cost management


# Running Location of Homework:
https://fonyx.github.io/homework-02/#social-media-marketing
## Instructions for Updating Website

Website is built using Quarto, and is hosted on GitHub pages through the
UBC-STAT Organization.

I (Grace) rebuilt this website in 2025 to use Quarto and provide a more
easily editable and maintainable website for this course.

### Editing the Website

To edit the website: - Clone the repository to your local machine - Open
the R project - Edit the webpages (.qmd files) in the webpages folder -
If adding any webpages, add them to the \_quarto.yml file

NOTES: - the \_quarto.yml file is white space sensitive. - to hide pages
if you'd prefer to release lectures one-by-one, comment them out in the
\_quarto.yml file - index.qmd must be named index.qmd and must be on the
top level (not in a folder) - if you rename, delete, or move a webpage,
you need to go into the docs folder and delete it there. You can just
delete everything and re-render. - always render site and save all
before pushing to GitHub - right now lectures are named by week since
some weeks have two lectures and some don't. Due to how I wrote the
syllabus I found this made the most sense

### Formatting (my preference)

-   in-class exercises are built using a call-out block (warning type
    with icon = F. Orange, minimal)
-   instructor demos are build using a call-out block (tip type with
    icon = F. Green, minimal)
-   notes are build using call out blocks (note type, blue)
-   tips are built using call out blocks (tip type, green)
-   cautions are build using call out blocks (caution type, orange)


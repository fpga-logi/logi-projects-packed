logi-projects-packed
====================

self contained logi-projects.  The logi repositores are split into logical elements of hardware, software, tools, etc.  Each of these repository can get quite large, so it was chosen to make them indpendent repositories.  The logi projects source reference source from the external repositories including hardware, software, tools repositories.  These are referenced within the project and then built.  If the external references indpendently change, then the project will no longer successfully build.  

The projects repository is a work in action and we will be continually working on this and the external references.  Thus it would require a great frequency of maintenace to continually up the projects when the external source changes. A clean solution to overcoming this is to "archive" the project at a working state and move it the project packed repository.  This take a snapshot of the working project and archives all external sources into a single project folder.  This project folder is waht ou will find in this "packed" repository.  It will just "work" without having to worry about the external dependencies.  The LOGI-Team will update the packed-projects only when a major change in functionality upgraded.

The nice feature of the "packed" projects is that you can browse through all of the source and easily make changes to the projects.  For those that are not interested in the source should have a look a the "logi-apps".  logi-apps are fully contained projects with pre-built bitstreams.  Just download the logi-app and run the make_demo shell script.  



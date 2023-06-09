This repo contains a sample unit (Grade 6, Unit 2) marked up in OCX (html + JSON-LD).

The sitemap for the May 5 release can be found at: https://ocx.illustrativemathematics.org/05-05/sitemap.xml

This doesn't represent the final version. Known issues include:
* The links in the OCX files are relative for now.
* We're using grade 6 version 3, so it won't exactly match the hand-created sample. We used the new (un-released) version 4 content in the hand-created sample, but since the version 4 content isn't finalized (and we don't have the correct license in place yet), we didn't want to expose that content publicly. There are some minor content differences, including the fact that the version 3 content doesn't include section checkpoints.
* We don't have .qti files for the practice problem sets. (We have QTI 1.2 files, but I think we need to standardize on QTI 2.1.) Long term, we'll need to build that functionality into the CMS.
* We don't have .qti files for the cool downs. We still need to build that functionality into the CMS.
* Links to images currently don't work. We're actively working on a fix.
* The math is currently represented as LaTeX, not MathML.
* We don't currently have hasPart fields in the metadata.
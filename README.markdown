README

MMD metadata input files for Scrivener exports (to produce LaTeX thesis)

Created by Stephen Murphy on 2011-04-20

# Folder Contents

LaTeX template files for writing the dissertation or for other academic/research writing.

These files will be used in MMD metadata, typically for Compiling from Scrivener 2.

Example use:

    latex input: my-mmd-thesis-header 
    Title: My Document 
    Author: My Name
    Keywords: draft, thesis
    Base Header Level: 2 
    LaTeX Mode: memoir 
    latex input: my-mmd-thesis-setup
    latex input: my-mmd-thesis-begin-doc
    latex footer: my-mmd-thesis-footer

Some files such as preamble.tex will need to be included (see thesispreamble repo)

Note that style files, BibTeX files etc would be in the texmf tree.

This folder is versioned with git.

# License

All files are written by and copyright Stephen Murphy <mailto:stephen.j.murphy@student.uts.edu.au>, although there have been many influences over the years affecting the final result.

Any and all of the author's rights are currently reserved.
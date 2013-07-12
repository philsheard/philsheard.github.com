---
published: true
title: Workflow tip for anyone who writes for fun or money
template: post
---
I've got into the habit of using a simple text editor and the Markdown format for all my writing recently. However, I've never tried it with documents of more than 5 or so pages.

Today I spent a bit of time tinkering and put together this workflow:

* [Sublime Text 2](http://www.sublimetext.com/2) for writing, enhanced by a good Markdown plugin. [MarkdownEditing](http://ttscoff.github.com/MarkdownEditing) is the one I use.
* [Pandoc](http://johnmacfarlane.net/pandoc/) to enable conversion from Markdown to Microsoft's docx format
* Finally [Jeff Clement's great plugin](https://github.com/jclement/SublimePandoc) for ST2 so you don't need to use Pandoc at the command line

Write in Markdown and when the document is ready, export to .docx and Word's themes are already applied, ready to share. 

### Going further

If you use the native Markdown format for embedded images (keep them in the same folder for convenience) then these will also be embedded into the document, although they may need some resizing in the final edit.

Even better, if you later want to output to other formats (HTML, PDF, ebook) you can do that via Pandoc too.
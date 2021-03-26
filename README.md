# asciidoctor-doctitle
This allows an author to directly define the docname for a file as an attribute. 

All credit goes to mojavelinux - https://github.com/asciidoctor/asciidoctor/issues/1992#issuecomment-801492006

What this extension does is unlock the docname attribute so that the document can set it. Now you can add the following attribute entry to the document header:

:docname: {docname}-{revnumber}

or

:docname: {doctitle}-{revnumber}

The processor uses the value of the docname attribute to create the output filename (adding the file extension requested by the converter).

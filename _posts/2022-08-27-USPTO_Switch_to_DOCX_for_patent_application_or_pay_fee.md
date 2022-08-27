---
layout: post
published: true
main: true
title: "USPTO: Switch to DOCX for patents applications or pay a surcharge"

description: "USPTO will require Docx format for patent application documents unless you want to pay a fee. This change is part of the recent effort of the USPTO to automate their process, which relied heavily on human labor."

picture: docx-filing-feature.jpg

label_default: "USPTO" 
label_primary: "Patent"
label_info: "Fee"
---
<!-- Main Container -->

USPTO has been making a lot of formatting changes recently :
* Most of their PDF forms have changed.
* They require XML versions of all data submitted.
* They're handling classifications differently, etc.

The USPTO process always felt stuck in the past and relied heavily on human manual processing. It feels like they are finally moving everything toward automated intake and initial reviews and [docx applications format requirement](https://www.federalregister.gov/documents/2022/04/28/2022-09027/filing-patent-applications-in-docx-format) is here to streamline the effort.  

I imagine this change is for the same reasons, and that's a hefty fee to force it. The fee is $100, $200, or $400, depending on the size of the document.

If you wonder why docx format would be chosen instead of PDF, they answer it pretty thoroughly here if anyone else is interested: [https://www.uspto.gov/patents/docx](https://www.uspto.gov/patents/docx)

Moreover, the USPTO has provided an MS Word Style Template and a document schema (document template). 
The great thing with docx is that it is effectively a zipped XML document. XML means extracting information from XML for further analysis is easy by writing XPaths and XQuery requests that provide an API for the original docx document collection.

I can't wait to see what kinds of unredacted metadata people start uploading without a thought.

<!--End Main Container -->

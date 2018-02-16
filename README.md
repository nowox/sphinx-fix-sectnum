# sphinx-fix-sectnum
Fix incorrect section numbering (from docutils)

This extension allow to render this document

```rst
==========
Document Title
==========

.. sectnum:: 

Section
=====

Subsection
------------
```

Without number for the document title as GitHub does. 

```
Document Title

1. Section

1.1 Subsection
```

Without this extension, you will get this output:

```
1. Document Title

1.1 Section

1.1.1 Subsection
```

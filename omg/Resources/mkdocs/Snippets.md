Sections in .md files that should be referenced dynamically in other .md files should contain Snippets. Here is the rule:

\--8<-- \[start:name]

Surround a referenceable section with start and end snippet codes seen here.

--8<-- \[end:name]

After this section is named, you can reference the absolute path in another OMG file by using:

\--8<-- "path\\to\\\file.md:name"
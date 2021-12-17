# About these Repositories

The Repositories in GutenbergSource are all my source files for ebooks I've submitted to Project Gutenberg. These source
files are in the TEI format, and to be more precise in the now obsolete SGML format, following the P3 version of TEI (A version in XML is also included).

Each of these repositories has the following contents (some of these are optional).

* `<name>-<version>.tei` -- The source file itself.
* metadata.xml -- automatically generated metadata in RDF format.
* README.md -- automatically generated readme in markdown format.
* good_words.txt -- File generated by PGDP site, containing words marked as 'good'.
* bad_words -- File generated by PGDP site, continaing words marked as 'bad'.
* project<hex-number>-comments.html -- Instructions used at PGDP site.
* tei2html.config -- Configuration for my tei2html tooling, used to create derived versions.
* Processed -- a directory with processed results
  * <name>.html -- HTML file derived from the source file.
  * <name>.xml -- XML file in TEI format, derived from the source file.
  * <name>.txt -- Latin1 plain text file, manually derived from the source file.
  * <name>-utf8.txt -- UTF8 plain text file, manually derived from the source file.
  * images -- a directory with illustrations.
  * images@1 -- a directory with illustrations, at 144 DPI, maximum dimension 720px on longest edge.
  * images@2 -- a directory with illustrations, at 288 DPI, maximum dimension 1440px on longest edge.

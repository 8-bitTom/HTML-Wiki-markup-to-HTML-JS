HTML-Wiki-markup-to-HTML-JS
===========================

a test our dev sent to romania. This is how I solved it. Had a number of syntaxes that had to be parsed and converted to a valid HTML string.
Here's the original js fiddle: http://jsfiddle.net/FLwfN/44/



Write a HTML UI application to convert custom formatted text to HTML.

The rules are:

1.  Paragraphs are separated by blank lines.  Each paragraph should be
     wrapped with the "<p>" tag
2.  A paragraph that starts with '`' symbols is a "preformatted" text
     and should be wrapped with the "\<pre>" tag
3.  A paragraph that starts with '#' symbol is a header.
       The more '#' symbols, the smaller the header.
       For example a single '#' will be represented as a '\<h1>' tag.
       A sequence of "###" will be converted to "'"\<h3>"
4.  Inside paragraphs, pieces of text can be emphasised by putting
     them between exclamation marks '!".
       The '!' character will be converted to the HTML bold "\<b>"
5.  External http contents can be pulled in by specifying {http://google.com}.
       Replace the text with the contents of HTTP URL specified.

You can assume the text are all well formatted
and http contents are always of content type text/plain


See sample.png for a sample UI.

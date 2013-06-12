This is a fork of http://html2latex.sourceforge.net/. See original site for full documentation and other information.

Reduced documentation below. Original package appears to have last been edited in 2000, and is still available here: http://sourceforge.net/projects/html2latex/files/

Summary
=======

html2latex is a Perl script designed to convert a properly formatted HTML file into a properly formatted LaTeX file.

Supports
========

It can handle URLs on the command line and in the IMG tag.  
Converts pictures from jpeg or gif to png. pdflatex can have included
pngs.  
Renders nested tables correctly.  
Supports most international characters (umlats, accents, etc).  
Converts all headers into sections. This can be easily customized.  
Lists of any form.  
Configuration through command-line options or an XML config file.  
It is also very easy to extend by writing your own handlers.  

Requirements
============

html2latex requires the following modules for basic operation:

HTML::Tree - It requires HTML::Parser.  
XML::Simple - It requires XML::Parser.  


html2latex can use the following modules for advanced operation:

LWP::Simple - Used do download URLs. Requires lots of things; look for
Bundle::LWP or libwww.  
URI - Comes with libwww or Bundle::LWP. Also required to grab URLs.  
Image::Magick - If you want to convert images to PNGs.  

The easiest way to get these modules is to use the CPAN module. Try man CPAN.

This is a fork of HtmlAgilityPack from https://htmlagilitypack.codeplex.com/

Currently, here is what is done:
* build with appveyor: DONE [![Build status](https://ci.appveyor.com/api/projects/status/2uiw19maorp2laor?svg=true)](https://ci.appveyor.com/project/tomap/htmlagilitypack)
* publish a nuget package

ToDo:
* Build all projects with appveyor (silverlight, ...). Not interested in doing that, but I accept PR :)


# What is exactly the Html Agility Pack (HAP)?

This is an agile HTML parser that builds a read/write DOM and supports plain XPATH or XSLT (you actually don't HAVE to understand XPATH nor XSLT to use it, don't worry...). It is a .NET code library that allows you to parse "out of the web" HTML files. The parser is very tolerant with "real world" malformed HTML. The object model is very similar to what proposes System.Xml, but for HTML documents (or streams).

Html Agility Pack now supports Linq to Objects (via a LINQ to Xml Like interface). Check out the new beta to play with this feature

# Sample applications:

* Page fixing or generation. You can fix a page the way you want, modify the DOM, add nodes, copy nodes, well... you name it.
* Web scanners. You can easily get to img/src or a/hrefs with a bunch XPATH queries.
* Web scrapers. You can easily scrap any existing web page into an RSS feed for example, with just an XSLT file serving as the binding. An example of this is provided.

There is no dependency on anything else than .Net's XPATH implementation. There is no dependency on Internet Explorer's MSHTML dll or W3C's HTML tidy or ActiveX / COM object, or anything like that. There is also no adherence to XHTML or XML, although you can actually produce XML using the tool. The version posted here on CodePlex is for the .NET Framework 2.0. If you need the old version, please go to the old page or drop me a note.

# License

Code under Microsoft Public License (Ms-PL). See License.txt
# SaxonCSXSLT30ExampleVB
Example .NET 5 console application to use SaxonCS 11 and XSLT 3 to run an XSLT stylesheet against an input document with VB.NET

Use of `Saxon.Api` from VB.NET to run XSLT 3.0 with `Xslt30Transformer` and the `Transform` method, to run the XSLT code from the StackOverflow answer https://stackoverflow.com/a/69949565/252228 against
the input sample and write the result to `Console.Out`.

No error checking on compiling or runnning the XSLT is done, so basically just the shortest code path once you know you have a working XSLT is shown. 

<img src="images/ENHTOP.gif"/>

# The Ethiopian News Headlines Corpus Collection

This repository houses the corpus of the Ethiopian News Headlines (ENH) service that ran from late Hamle 1989 - Yekatit 1997. The ENH was published initially under the ENH.EthiopiaOnline.Net website, then later under both EthioZena.Net and News.Com.Et .  The service came to an end in the midst of the chaotic 1997 Ethiopian election period when agents of the government begun an investigation of the service operations.  While online publishing stopped, out of concern for the safety of the staff, offline corpus development continued up until Tahsas 2002. After this time, focus shifted to developing a [book based corpus](https://github.com/geezorg/ebooks/).

The ENH effort reached a total volume of **13,079** articles from **126** newspapers. In 1998 (GC) it was responsible for no less than 95% of the first 1 million words of Amharic appearing online.

The full corpus collection can be downloaded under the [“Releases”](https://github.com/geezorg/enh-corpus/releases/) link of this repository. 


## Terse Background
The ENH got its start as a private research corpus.  Typist were instructed to type content *exactly* as they saw it in news articles and *not* correct typographic errors. Invariably the typist would introduce their own typographic errors which would become indistinguishable from the source errors. This was deemed OK since error detection and correction was very much a part of the research objective.  These errors remain in the corpus. 

The value of the growing current news corpus to the diaspora was immediately evident and so they were published online at the end of 1989 EC with the help of Joseph Kibur of NetNation. Promoting the free press in Ethiopia was another goal of the publishing service. Newspaper publishers in Addis Ababa were approached to provide their weekly content to the service and indirectly its corpus. A number of publishers saw the value of reaching a world wide audience and contributed their full weekly edition's worth of articles (which they otherwise would have deleted to save limited harddrive space). For those that participated, a surprise benefit found in online publishing was that it would relieve the publisher of the burden of mailing weekly physical papers to subscribers in Europe and North America.

ENH articles were both manually retyped from weekly newspapers and converted from files provided directly by the news agencies (noteably Tobia, Fiameta, Addis Admas and InterSport). Tobia would develop a significant archive under a parallel website, Tobia.EthiopiaOnline.Net , the contents of the site are also included here.

Content is in the XHTML format in UTF-8 encoding.  Internal links within the archive are not expected to work.  Conversion of the content to a modern and consistent HTML and CSS representation, fixing internal links, and other minor cleanup from conversion issues, are goals of a version 1.0 release of the archive.

## SERA Source Files
ENH articles were composed with Multilingual Emacs (aka [MULE](https://en.wikipedia.org/wiki/MULE)) using the Ethiopic package and stored in the SERA transliteration with HTML markup. As an ASCII based encoding, SERA provided a means of character encoding that was safe for all operating systems, storage systems, and interchange protocols of the 1990s (and prior) while waiting for Unicode to support Ethiopic script (in the year 2000).

The ENH web server would use Perl and C language extensions (based on [the LibEth library](http://libeth.sourceforge.net/)) to convert SERA source files into [one of many](http://libeth.sourceforge.net/CharacterSets.html]) pre-Unicode encoding systems in use by a customer selected font preference. Unicode was also initially supported under a draft specification but limitations with operating systems and web browsers would persist for some time (think of Netscape on Windows 95).

The SERA source files are being prepared for the archive and will appear with the version 1.000 release if not sooner. 

The Multilingual Emacs Ethiopic package became part of the regular GNU Emacs when MULE features were merged in version 21. The Ethiopic package was created in 1994 by Naoto Takahashi of the Electrotechnical Laboratory in Tsukuba, Japan, for which we are eternally grateful.  




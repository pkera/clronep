========================================
About clronep
========================================
This project is a C# binding to the to the Exosite One Platform API. The API is
exposed over HTTP in a JSON RPC style interface.  The solution creates a Common
Language Runtime dll for use by .NET applications that wish to interact with 
Exosite's One Platform.

Recommend using with Microsoft .NET Framework 3.5.

License is BSD, Copyright 2011, Exosite LLC (see LICENSE file)

========================================
Quick Start
========================================
Tested with Visual Studio 2010 (Windows) and MonoDevelop 2.4/Mono 2.6.7 
(Windows/Linux).

--) Example test project in the ./clronep/clronep.examples/ folder<br>
--) API documentation in the ./clronep/docs/ folder<br>

For more information on the API and examples, reference Exosite online 
documentation at http://exosite.com/developers/documentation.

========================================
Release Info
========================================
----------------------------------------
Release 0.2
----------------------------------------
--) added example application<br>
--) NOTE: Due to using JSON.Net dll for .NET 2.0 (for best compatibility), the
    projects generate some related warnings when built against .NET 3.5.<br>

----------------------------------------
Release 0.1
----------------------------------------
--) initial version<br>

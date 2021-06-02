# Techedia Solutions List


## .NET Development

### Techedia solutions - internal

* [SOAP API web service](https://github.com/techedia/Techedia-SOAP-API)
  - ClientActiveCheck.asmx - called by Techedia applications to check they should be active
  - Infotrack.asmx
  - SortRefer.asmx
  - SortReferIDCheck.asmx
* [System Monitor](https://github.com/techedia/TechediaSystemMonitor)
* [Helpdesk\Ticket Email  Processor](https://github.com/techedia/TicketSystemEmailProcessor)
* [Trello JSON file processor for MI Pack](https://github.com/techedia/TrelloJSONProcessorReporting)

### Techedia solutions - external\client

* [Techedia Proclaim Utilitites](https://github.com/techedia/TechediaProclaimUtils) (ClientActiveCheck : YES)
* [ODBC Connection poller](https://github.com/techedia/ODBC-Connection-Poller)
* [SFTPConsole](https://github.com/techedia/SFTPConsole)
* [Email Extractor](https://github.com/techedia/EmailExtractor)
* [Document PDF Bundler](https://github.com/techedia/techediaProclaimDocBundler)  (ClientActiveCheck : YES)

### Techedia solutions - external\generic

* [Chatbot](https://github.com/techedia/Chatbot)
  - Chatbot.Database - Class library for Data Access and Database Interactions. Houses all data layer objects, DBContext and repositories.
  - Chatbot.Core - Class library for utility classes. Houses all Helpers, Exensions, Model classes, API Integrations, Attributes.
  - Chatbot.Web - ASP.Net MVC web application for the frontend of the chatbot.
  - Chatbot.Console - C# console application for automating reporting, emailing and sms's
  
* [PortalIP](https://github.com/techedia/PortalIP)
  - PortalIP.Web
  - PortalIP.API
  - PortalIP.Core
  - PortalIP.Database

### Integrations

#### SortRefer\SortMove

* SOAP API web service is called for this integation : [SOAP API web service](https://github.com/techedia/Techedia-SOAP-API)
* [SortRefer CaseDownload console app](https://github.com/techedia/SortRefer-CaseDownload-consoleapp) (ClientActiveCheck : YES)
* [Sort Refer ID](TBC)

#### Perfect Portal

* [Perfect Portal Case Download console app](https://github.com/techedia/PerfectPoralCaseDownloadConsoleApp) (ClientActiveCheck : YES)
* [Perfect Portal Quote PDF Download console app](https://github.com/techedia/PerfectPoralQuotePDFDownloadConsoleApp)

#### InfoTrack

* SOAP API web service is called for this integation : [SOAP API web service](https://github.com/techedia/Techedia-SOAP-API)
* [InfoTrack Document download console app](https://github.com/techedia/InfoTrackDocumentDownloadConsoleApp)
* [InfoTrack Process XML Get Case Type console app](https://github.com/techedia/InfoTrackProcessXMLGetCaseTypeConsoleApp)

#### X-Press Legal Services

* [X-Press Legal Services : Case Order and document download](https://github.com/techedia/XPressLegalServicesIntegration/tree/master)

#### Spectra XML funding integration

* [Spectra XML funding integration](https://github.com/techedia/MoneyPlusSpectra) (ClientActiveCheck : YES)


## Client specific solutions

### Gorvins

* [ULS Technologies console app](https://github.com/techedia/ULSTechnology) (ClientActiveCheck : YES) Not listed under generic integrations as I wouldn't advise doing this for another client
* [LMS](https://github.com/techedia/LMSFTPandFileProcessor) Not listed under generic integrations as I wouldn't advise doing this for another client

### MoneyPlusLegal

* [Pentacle API - case download](https://github.com/techedia/PentacleClaimsPortalConsole) (ClientActiveCheck : YES)
* [Case import data prep and cleanse](https://github.com/techedia/VS_caseimport_datapreprocess/tree/master)

### Progress Law

* [Progress Law case instruction webhook](https://github.com/techedia/ProgressLaw_FLG_webhook)

### Keller Lenkner

* [UClaim4Me - New plevin case import](https://github.com/techedia/UClaim4Me)
* [Secret Commission Lawyers - New plevin case import with documents](https://github.com/techedia/KLSCLDocProcessing)
* [c2solutions Acumen API integration](https://github.com/techedia/c2solution-Acumen-API)

## Web Deveopment
  * [Techedia Helpdesk & Intranet](https://github.com/techedia/helpdesk)

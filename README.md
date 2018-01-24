# Password-Manager-Pro-Syslog-Grok-Pattern

## Installation

The extractor is built using grok patterns. It is necessary to add the date format YYYY/MM/DD to graylogs library of stored patterns in order for the extractor to work.

* go to System -> Grok Patterns -> Import pattern file
  * select grok-pattern.txt and press OK

* then go to your input and select "Manage extractors"
  * click Actions -> Import extractor
  * paste the content of the extractor.txt file

If you like you can add rules to restrict execution of this extractor to certain occurences of strings or other criteria.

## Result

<screen shot>

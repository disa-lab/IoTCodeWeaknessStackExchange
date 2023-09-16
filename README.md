# IoTCodeWeaknessStackExchange

The results and methods of our study can be found in this paper: IoTVulnerability.pdf

## Code Folder
Contains code used in the study.
* cppcheck-results-analysis: analyze CWE information from cppcheck results, and question view counts
* cve-types-scores: analyze CVSS score distribution of CVE types 
* trend-analysis: obtain post date information of weak code snippets

## Dataset
Contains extracted code snippets from the June 2021 Stack Overflow, Arduino, and Raspberry Pi data dump. Also contains post and question information, downloaded CVE information from cvedetails.com, as well as the result of cppcheck analysis (output.xml file) 

## Example of vulnerable code snippets and suggested solutions
This website contains a few vulnerable code snippets from each weakness category we analyze (https://madhuselvarajj.github.io/IoTCodeWeaknessStackExchange/). We have also provided a safer solution for each code snippet: 

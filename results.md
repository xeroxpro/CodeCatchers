Date:
2018-10-14

Authors:
xeroxatpro

Status:
Fixed, action items in progress

Summary:
Issue with AES CIS service affected delay in sending customer data from AES EDI.

Impact:
Records were missed and were not discovered automatically.

Root Causes:
Issue with the AES CIS service(Jira Issue No: AESCIS-38263) resulted the file with customer data did not get processed and it also affected EDI to CIS monitoring service working on the CIS side. So the missed records were not discovered automatically. 

Resolution:
The file was resent and the issue got resolved. The missing records were discovered at 11:56 AM, processed at 1:00 PM

Detection:
A Jira issue ( AESEDI-53447) was logged that the customer data was not sent from AES EDI.

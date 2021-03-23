# Document_Forensics_KTA_Resistant
Step 1 : Download the zipped Packaged file 

Step 2 : Import it into KTA using the Import wizard along with all the artifacts included in the package

Step 3 : Create a File Import configuration for the documents to be ingested by KTA.

Step 3.1 : Use the same path for Watched folder and Archive Folder ( mandatory ). In this case the archive folder will automatically create an OK folder within.

Step 4 : Review the server variables under "Online Document Fraud Detection >> Resistant project" and update the "FileUploadDirectory" to the same as the Watched folder in step 3.1

Step 5 : Place the files in the watched folder and enjoy!

Please note that KTA should be running on the HTTPS protocol in order for the viewer to work securely. 

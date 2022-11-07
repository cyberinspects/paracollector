# Http Server using Sockets 
This is a project of http client and server communitcation using sockets, In this project we have built a http server and a client for communitcation over tcp using http protocol.
## Server
the Server has defined number of path for content serving like home and list path. Home shows the default page while list is another endpoint to disable available files on server,
their is also a dymanic path serving function to show files.
##### Impletments threading concept to deal multiple clients at once
##### Defined routes and dynamic serving
##### Running over 8080 (http)
##### Files can also be displayed over browser clients

## Cleint
Client is built over requests, beautifulsoup and file writers to list and download files from http server.
##### Can list files
##### Can download files
##### Request implementation
##### Uses custom headers for validation

## Use
1) First simple run the server file
2) Now you can browse your local server in browser at http:127.0.0.1:8080/
3) You can also download and list files using Client script
## Requirement
##### sockets
##### requests
##### beautifulsoup

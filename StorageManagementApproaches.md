[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8842962&assignment_repo_type=AssignmentRepo)

For this web platform, there are two overarching types of storage management: local storage and session storage.
Local Storage:
- This helps the programmer store data on the client’s computer web browser. 
- It is in the form of key/value pairs. 
- It will not be removed upon closing of the web browser. 
- It will be stored for the lifetime of the browser unless the client opts to delete it from the browser's memory. 
- The limit for this type of store is approximately 10 MB depending on the browser.
- These are the benefits. The drawbacks ae the following.
- The data here cannot be read by the severs, only the clients.
- It is limited to Strings, so serialization is required.
Session Storage:
- The main difference from local storage is in the lifespan of the data. 
- The data does not persist in the browser. Once the browser is closed, the data will be lost.
- The above is partially a drawback depending on the reason for storing that data.
- An extra benefit is that this data can be retrived by the server.
Another type of storage is cookies and these used to be the only type of storage available for legacy web browsers. They contain aspects of both the above storage types in various segments of cookie storage like session cookies and persistent cookies.

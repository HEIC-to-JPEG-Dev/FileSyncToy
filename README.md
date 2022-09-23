# FreeFolderSync

A new Wnidows 11 file sync tool.

#Design Principles

FreeFolderSync is designed for a modern Windows, but with the ethos that everything is simple and editable, for example:

* Use of ini files. This allows editing, searching, diffing, merging, copying between machines, and to be easily readable to identify what information is stored for security and privacy.
  
* Security. FreeFolderSync's files are stored in a common location (~Documents) and can optionaly be encrypted and compressed. This is an extension to ini files.
  

#Progress

We're still in planning. But our first task is to build a custom ini class that supports comments, compression, and encryption. We chose ini files for everything instead of database files because we wanted anyone to be able to see what was going on and to edit them outside of the app with something as simple a Windows Notepad. Optional compression is required when we need to store lots of data for two-way sync. Encryption is required when the user doesn't want anyone else to see the data and configuration.

Oncce this is complete, we'll move onto the UI and start posting

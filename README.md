# FileSyncToy - A modern SyncToy with a nod to the past.

A new Windows 10/11 file sync tool. If you have any requirements, suggestions, must have's, or want to ask about this project - use the GitHub Issues - thanks.

See the Wiki page for more information. We're going through the old forums looking at suggestions and bugs in the original, and merging this into this development.

# Design Principles

If you've never seen SyncToy, go have a look [here](https://en.wikipedia.org/wiki/SyncToy).

* Styling and color schemes of the original, making it familiar for anyone who has used SyncToy.
  
* A rewrite of the .Net Sync Framework with improvements and bug fixes. So far, we have increased performance for enumeration beyond the expectations of SyncToy; what took the original hours to complete, now takes a few minutes - for very large jobs.
  
* Native Windows development using C#, .Net 7, and WinUI for Desktop.

# Progress

We're in active development...
* :white_check_mark: [February 2023] Core design layout completed. 
* :white_check_mark: [March 2023] File filters and enumeration complete.
* :white_check_mark: [March] Preview and Actions.
* :small_orange_diamond: [Current Task] Running the Actions
* :small_orange_diamond: [ToDo] Sync Metadata for handling changes between sync sessions
* :small_orange_diamond: [ToDo] Test & Prepeare for release

# Publishing

The app will be distributed via the Microsoft App Store and support x64 and ARM64 on Windows 10 and 11.

# Roadmap

The first release will provide most of the functionality of the original and be the ground zero for future enhancements. The focus is to get a working SyncToy alternative to satisfy most people and then take requests for changes and enhancements; we also have a list the length of a CVS receipt of things planned - the priorities will change based on feedback. See the roadmap poll for the community [Roadmap Poll](https://github.com/HEIC-to-JPEG-Dev/FileSyncToy/discussions/7).

The following features that exist in SyncToy, will  be absent for the version 1.0 but added during version 1.x.
* All folder Pairs: The ability to run multiple Left/Right jobs simultaneously.
* Scheduling: We're still determining how this will be accomplished.
* Logs: A record of what has happened.
* SubFolder exclusion from folder pairs
* Content checking for comparison

# Some Screenshots

![image](https://user-images.githubusercontent.com/32410442/225571465-d13f1706-02ae-443f-81f4-dfcacf44340d.png)
![image](https://user-images.githubusercontent.com/32410442/227699572-2ada0a4a-8d77-4f97-9e79-a2e0ef832af6.png)


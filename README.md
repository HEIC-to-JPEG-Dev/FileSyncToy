# Update. June 2024

The UI of FileSyncToy was deemed too close to the original. The original is Trademarked and a compromise needed to happen. This has now happened and development can continue. However, a redesign is required, this has been prototyped and is being implemented. We're taking this opportunity to update many of the internal components of the app so it will be faster and easier than ever, while still retaining the "essence" that is SyncToy.


# FileSyncToy - A modern SyncToy with a nod to the past.

A new Windows 10/11 file sync tool. If you have any requirements, suggestions, must have's, or want to ask about this project - use the GitHub Issues - thanks.

See the Wiki page for more information. We're going through the old forums looking at suggestions and bugs in the original, and merging this into this development.

# Design Principles

If you've never seen SyncToy, go have a look [here](https://en.wikipedia.org/wiki/SyncToy).

* Styling and color schemes of the original, making it familiar for anyone who has used SyncToy.
  
* A rewrite of the .Net Sync Framework with improvements and bug fixes. So far, we have increased performance for enumeration beyond the expectations of SyncToy; what took the original hours to complete, now takes a few minutes - for very large jobs.
  
* Native Windows development using C#, .Net 7, and WinUI for Desktop.

# Updates

We're in active development...
* :white_check_mark: [April 2023] It's alive! [Microsoft App Store](https://www.microsoft.com/store/apps/9NC0TXT5ZM7R)
* :white_check_mark: [June 2023 - Version 1.1] Improved the sync engine, currently 50% faster and uses 75% less memory, and added user based file logging.

# Publishing

The app is distributed via the Microsoft App Store and supports x86, x64 and ARM64 on Windows 10 and 11.

# Roadmap

The first release will provide most of the functionality of the original and be the ground zero for future enhancements. The focus is to get a working SyncToy alternative to satisfy most people and then take requests for changes and enhancements; we also have a list the length of a CVS receipt of things planned - the priorities will change based on feedback. See the roadmap poll for the community [Roadmap Poll](https://github.com/HEIC-to-JPEG-Dev/FileSyncToy/discussions/7).

The following features that exist in SyncToy, will  be absent for the version 1.0 but added during version 1.x.
* All folder Pairs: The ability to run multiple Left/Right jobs simultaneously.
* Scheduling: We're still determining how this will be accomplished.
* Logs: A record of what has happened.
* SubFolder exclusion from folder pairs
* Content checking for comparison
* Collisions, when a file is changed on the left and right of a sync pair
* Drag and Drop, from File Explorer into the app for folder pairs

# Some Screenshots

![2023-04-13 12_23_17-WinUI Desktop](https://user-images.githubusercontent.com/32410442/231760867-3c9fddd8-7bf8-4ded-b84d-d9d884e4b716.png)
![2023-04-13 12_27_44-WinUI Desktop](https://user-images.githubusercontent.com/32410442/231760882-5c92c5c0-d838-4eb6-874b-f50d339f1194.png)
![2023-04-13 12_27_58-WinUI Desktop](https://user-images.githubusercontent.com/32410442/231760899-2a09ce15-8a3f-419a-a3ab-e956cc2e8ad9.png)



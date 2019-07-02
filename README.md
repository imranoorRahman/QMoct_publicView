# QMoct
Mobile OCT System Implementation~ Using a modern smartphone with modest specs(not the latest and greatest but usbale) to capture large quantities of *'BURSTS'* of RAW images, in order to create an OCT image by processing them together. Various potential issues were found throughout this project, solutions were provided i.e. when capturing large volumes of RAW Images, the handheld device had no external memory, so implementing asynchronous loops in order to transfer captured images as they are captured using TCP/IP rather than UDP as teh information in each image holds value, so we can't afford to drop any pixels, other solutions were provided to combat issues found trhoughout this project.

# Important Note
Without setting up Matlab Engine on Desktop (Remote System) correctly: 
*This project will not work as intended.*

# Segments
There are 3 main segments of this project:

1. Mobile Application (main counter-part)
    - Connect to a remote location
    - Adjust camera settings
    - Capture RAW images
    - Transfer Images to remote location
  
2. Dektop Interface
    - Communicates with mobile device
    - Adjust camera settings remotely from desktop
    - Recieve incoming Images

3. Matlab Engine
    - Enables Java Dekstop application to process images it recieves by accessing Matlab Image processing library

# Ingredients
Java, Matlab, Android, and a sprinkle of hope

# Improvements currently being worked on
  - Recreate mobile application using Flutter: allowing the same code base to run on both IOS and Android
  - Improvements to current functionality
  - Improvments to UI
  
  # Acknowledgement
  Thanking Dr.Robert Donnan and Dr.Peter Tomlins from QMUL for support and guidance

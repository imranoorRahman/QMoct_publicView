# QMoct
Mobile OCT System Implementation

# Important Note
Without setting up Matlab Engine on Desktop (Remote System) correctly: 
*This project will not work as intended.*

# Segments
There are 3 main segments of this project:

1. Mobile Application (main counter-part)
  -Connect to a remote location
  -Adjust camera settings
  -Capture RAW images
  -Transfer Images to remote location
  
2. Dektop Interface
  -Communicates with mobile device
  -Adjust camera settings remotely from desktop
  -Recieve incoming Images

3. Matlab Engine
  -Enables Java Dekstop application to process images it recieves by accessing Matlab Image processing library

# Ingredients
Java, Matlab, Android, and a sprinkle of hope

# Improvements currently being worked on
  - Recreate mobile application using Flutter: allowing the same code base to run on both IOS and Android
  - Improvements to current functionality
  - Improvments to UI

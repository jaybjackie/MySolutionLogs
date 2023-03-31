# Swift and SwiftUI

capture the sitimulation live preview in Xcode without the shadow.

### disable the shadow
  run this command in the terminal.
  ```
  defaults write com.apple.screencapture disable-shadow -bool TRUE; killall SystemUIServer
  ```
---
### toggle the keyboard (for xcode simulator)
  error like this: 
  ```
  Can't find keyplane that supports type 4 for keyboard
  ```
  
  Press `cmd` + `k` to toggle
  
  or
  
  `Simulator > I/O > Keyboard > Toggle software keyboard`
  
---
### improper close the simulator
   error like this:
   ```
   Thread 1: signal SIGTERM
   ```
   <img width="688" alt="image" src="https://user-images.githubusercontent.com/88821578/229178190-121b0d17-03bd-4314-81fc-d880dd27cb59.png">
  
  solutions: to close the simulator properly
  
  force quit manually
  
  or 
  
  `cmd` + `q`
  
---

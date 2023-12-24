# Different Ways of Godot Debugging

## 1. Remote Debugging 

  a) **USB Debugging:** 
    - It is impossible for remote users.
    - Experimental Hack No USB –  
      ```
      $ adb tcpip 5555
      $ adb connect mobileIp:5555
      ```
      To connect with the mobile, you should see the Android icon on Godot debug (Should connect in the same network).

   b) **HTTP Server:** 
      - Need to explore.
      - (Looks like Godot-JavaScript Bridge for web).
      - It runs in the browser (mathApp not working in that way).

## 2. Android Emulator – Costly

  - Should Explore How to setup [link: https://docs.godotengine.org/en/3.5/development/compiling/compiling_for_android.html ]
  - It requires 2 to 4 GB RAM for a single good instance (Average 3GB).
  - Can run 5 to 6 instances simultaneously in 16 GB RAM.

## 3. APK Installation  

   - It is time-consuming.
      - Export a .apk file.
      - Upload and download to get it into the mobile.
      - Installation and Google Play verification time.
      - We only test it without debugging console.

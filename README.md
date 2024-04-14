XP3Player for AI project by Tuba Khan and Nisha
--- 
 You can also download the app for the desktop, by clicking on this link below
<h3 align="center" > XR3Player ( <a href="https://xr3player.netlify.com/" target="_blank">Download</a>  )</h3>
<p align="center">
<img src="https://cloud.githubusercontent.com/assets/20374208/26214265/6b605cae-3c04-11e7-9c14-2cd59e10dd03.png">
</p>       
<p align="center">                 
<sup>        
<b>The most advanced Java Media Player/Organizer you will ever find out there </b>      
</sup>                      
</p>                                      
                           
---         
| Image|
|:-:|
| [![First](https://user-images.githubusercontent.com/20374208/48313813-34fdc180-e5ca-11e8-9da7-c6148dc0cbe5.png)] |

| You can watch the video if you want|
|:-:|
| [![First](https://user-images.githubusercontent.com/20374208/48313813-34fdc180-e5ca-11e8-9da7-c6148dc0cbe5.png)](https://www.youtube.com/watch?v=7Hai7cavmUY)  |

## Platform Support ( 64 bit ) 

| Installer | Windows x64 | MacOS x64| Linux x64 | Android | IOS|
| ------- | :-----: | :-: | :-----: |  :-----: | :-----: |
| Download | [ link ](https://goxr3plus.github.io/xr3player.io/) | X (help wanted) | X (help wanted) |  X (planning) | X (planning) |

| DJ UI | Chromium Web Browser 
|:-:|:-:|
| ![First](https://user-images.githubusercontent.com/20374208/48313813-34fdc180-e5ca-11e8-9da7-c6148dc0cbe5.png) | ![web_browser](https://user-images.githubusercontent.com/20374208/169485711-785cfd5f-c68c-4354-a8ae-6479f329ecdc.jpg) |

| Multiple Users | Advanced UI 
|:-:|:-:|
| ![login_mode](https://user-images.githubusercontent.com/20374208/169485737-11362c9f-57d9-4f57-ac58-2dfa1eac6ed6.jpg) | ![main_mode](https://user-images.githubusercontent.com/20374208/169485764-6809b0aa-d5ef-4099-99d4-31276e0fb9e0.jpg) |

-------------------------------------------------------------------------------------

# HOW TO RUN PROJECT 

To build XR3Player, you will need: 

* [JDK 21]
* [Maven](http://maven.apache.org/) - Version 3.8.1++

Open IntelliJ and fork the project (https://github.com/tubakhxn/XP3Player).

![2019-08-01_18-04-22](https://user-images.githubusercontent.com/20374208/62304551-d5f91900-b486-11e9-80e9-cf802d91ee6f.gif)

In order to run the project you should add the following **VM Options** ( easy using IntelliJ , Eclipse or Netbeans ) :
```
--add-exports javafx.controls/com.sun.javafx.scene.control.behavior=com.jfoenix
--add-exports javafx.controls/com.sun.javafx.scene.control=com.jfoenix
--add-exports javafx.base/com.sun.javafx.binding=com.jfoenix
--add-exports javafx.graphics/com.sun.javafx.stage=com.jfoenix
--add-exports javafx.base/com.sun.javafx.event=com.jfoenix
--add-exports javafx.graphics/com.sun.javafx.scene=org.controlsfx.controls,
--add-exports javafx.graphics/com.sun.javafx.scene.traversal=org.controlsfx.controls
```

Ready to go :) 

This is only for me when i build the new installers ( i wrote this to not forget in future )

How i package for the installer : ```Maven clean``` and then ```Maven package``` from the lifecycles .

It prepares a ```XR3Player_lib``` and a ```XR3Player.jar``` and it copies then using the assemply into a zip called XR3Player Update xxx . zip

![image](https://user-images.githubusercontent.com/20374208/232339947-df1ccbe2-b15e-430f-968c-ba0bd0ef9e94.png)

![image](https://user-images.githubusercontent.com/20374208/232339975-308fcc90-5276-4a19-8656-41e5ca424878.png)

## Modular
 - **As XR3Player codebase keeps growing i decided to make it modular so it's main components are the below :**
   - [XR3Player Core](https://github.com/goxr3plus/XR3Player) ( The main code of XR3Player )
   - [XR3Capture](https://github.com/goxr3plus/XR3Capture) ( For capturing the computer screen )
   - [Stream Player](https://github.com/goxr3plus/java-stream-player) ( Audio Library 100% Java )
   -  //TODO JVisualizations ( Advanced Java Audio Visualizations Library )
   -  //TODO  [JAmplitudeVisuals](https://github.com/goxr3plus/Java-Audio-Wave-Spectrum-API) ( Advanced Java Library for representing Audio Amplitude Visualizations ) 
  
   ## Features
- **Done ✔️**
  - Support almost all audio formats through smart converting to .mp3
  - Amazing Audio Spectrum Visualizers
  - Audio Amplitudes Waveform
  - Chromium Web Browser
  - Full Dropbox access
  - Multiple User Accounts
  - Configurable via multiple settings
  - Advanced Tag Editor
  - File Organizer and Explorer
  - Multiple Libraries/Playlists support
  - System monitor ( CPU , RAM )
  - Audio Effects and Filters
- **TODO 🚧**
  - _XR3Player is actively developed. More features will come!_
  - Support all audio file formats by default
  - Support all video file formats by default
  - Speech Recongition 
  - Smart AI Assistant
  - Online Subscription website
  - Android and IOS applications
## Java Audio Tutorials and API's by GOXR3PLUS STUDIO
 - **Spectrum Analyzers**
   - [Java-Audio-Wave-Spectrum-API](https://github.com/goxr3plus/Java-Audio-Wave-Spectrum-API)
    ![image](https://github.com/goxr3plus/Java-Audio-Wave-Spectrum-API/raw/master/images/Screenshot_2.jpg?raw=true)
   - [Jave Spectrum Analyzers from Audio](https://github.com/goxr3plus/Java-Spectrum-Analyser-Tutorials)
   - [Capture Audio from Microphone and make complex spectrum analyzers](https://github.com/goxr3plus/Java-Microphone-Audio-Spectrum-Analyzers-Tutorial)
  
 - **Java multiple audio formats player**
   - [Java-stream-player](https://github.com/goxr3plus/java-stream-player)
   - **Speech Recognition/Translation/Synthenizers**
   - [Java Speech Recognition/Translation/Synthesizer based on Google Cloud Services](https://github.com/goxr3plus/java-google-speech-api)
   - [Java-Speech-Recognizer-Tutorial--Calculator](https://github.com/goxr3plus/Java-Speech-Recognizer-Tutorial--Calculator)
   - [Java+MaryTTS=Java Text To Speech](https://github.com/goxr3plus/Java-Text-To-Speech-Tutorial)
   - [Java Speech Recognition Program based on Google Cloud Services ](https://github.com/goxr3plus/Java-Google-Speech-Recognizer)
   - [Java Google Text To Speech](https://github.com/goxr3plus/Java-Google-Text-To-Speech)
   - [Full Google Translate Support using Java](https://github.com/goxr3plus/java-google-translator)
   - [Professional Java Google Desktop Translator](https://github.com/goxr3plus/Java-Google-Desktop-Translator)


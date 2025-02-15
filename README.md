
# Shader Demo
![Screenshot](logo.png)

# Small Trailer 
[YouTube-Link](https://www.youtube.com/watch?v=2xpn_W1_3SU&ab_channel=ValentinSchmidberger)

# Requirements
- To run the shader demo you need an oculus quest 1 or 2 
- A working internet connection 

# To get started
- If you only want to test our demo, just click on this link in your oculus browser: [Shader Demo](https://vale-sch.github.io/ecg_GruppeEVA/sprint3/index.html) 
- You must agree to the request to use hand tracking for the demo 

# To get deeper sights in our code
- If you want to tweak your own things into our demo, clone this repository via SSH: "git@github.com:vale-sch/ecg_GruppeEVA.git"
- Next step is to create your own server certificate to run the project locally via live server on vs code, to get this done follow the instructions from here: [SSL Certificate - Live Server](https://medium.com/webisora/how-to-enable-https-on-live-server-visual-studio-code-5659fbc5542c)
- Then you have to find out via the console (ipconfig) which IPv4 address your computer uses. With the given IP address and the port number of the live server (default is: 5500) you can access the project in the HMD. It should look similar to this: "https://192.168.178.136:5500/"
- Now you are ready to make some changes to our code!

# Documentation
- [Class Digram](ShaderDemoClassDiagram.png)
- To understand component system: [Ecsy](https://three.ecsy.io/docs/#/)
- To understand hand tracking and their functionalitys: [Handinput - three.js](https://threejs.org/examples/?q=hand#webxr_vr_handinput_pointerclick)
- To understand positional audio: [Positional Audio - three.js](https://threejs.org/docs/#api/en/audio/PositionalAudio)




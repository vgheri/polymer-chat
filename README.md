Polymer-chat
==
Polymer-chat is a very simple, proof-of-concept, web component for embedding an unobtrusive chat widget in your website. 
I'm having fun building it using Google Polymer and its server side companion project is called nodeChatServer.

Please note that this project is born as a self teaching experiment and therefore is not meant at all to be released in the wild __as-is__!

Every feedback is very well accepted as well as pull requests.


How to use it
==
Polymer-chat at the moment relies on a Primus node server to connect to and its address is hardcoded into the polymer component.
Therefore if you wish to use this component you need to either supply your own server and modify the URL, either ```git clone``` my other repository nodeChatsServer and start it up.
Once this is all done, you only need to reference Polymer and the element itself from within your HTML file:

```
<!-- Place your HTML imports here -->
<script src="bower_components/platform/platform.js"></script> 
<link rel="import" href="elements/chat.html">
```

How to build and play with it
===
To build the project just clone the repository and issue command
 
```npm install```

followed by 

```bower install```

To launch the example page, simply type

```grunt serve```


You will need to have both ```npm``` and ```bower``` installed.
 

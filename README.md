# Dependent Libary 
- "react-native": "^0.50.3",
- "react-native-webrtc": "^1.58.3"
- "react-native-incall-manager": "^2.2.0",


# Demo

# Functionality
- Janus WebRTC Gateway Video Room Implementation
- Mobile Users can send teh audio and video msg to other paritciapnts up to 6 max (can configure in janus)

# How it wokrs?

# Application

# TODO
- [x] iOS works
- [ ] Android works
- [x] Janus Plugin Demo: Video Room works ( https://janus.conf.meetecho.com/videoroomtest.html )
- [x] Local camera view
- [x] Remote view
- [x] Audio mute
- [x] Video mute
- [x] Audio Speaker 
- [x] Unpublish and publish 
- [x] Switch front and back camera with react-native-webrtc MediaStreamTrack.prototype._switchCamera()
- [x] End call
- [ ] Solve the delay of receving remote viedeos increases when recreating the webrtc session by unpublish/publish 
- [x] Rerender teh video view if participants join and leave continuously
- [ ] Rich UI
- [ ] Refactor index.js and janus.mobile.js
- [ ] More Details about how to use this Documentation
- [ ] Other Janus Plugin(Audio bridge, Streaming, Sip, Call plugin)

# Setup
- Set up the janus with wss configured following by https://github.com/atyenoria/janus-webrtc-gateway-docker
- Change config.example.js to config.js and edit the content as you configured about Janus
- Code Signing for building on real device
- Change the node path for you env, Build Phases -> Bundle React Native code and images ("export NODE_BINARY=/Users/jima/.nodebrew/current/bin/node")
- Build the iOS project

# License
- MIT

# Contributor
- @atyenoria


# Any request and bug repoting?
- Could you create a new issue?

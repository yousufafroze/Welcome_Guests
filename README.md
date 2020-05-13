# Welcome_Guests

**Idea**: 
- To text guests the house's wifi automatically.

**What**: 
- When the live camera (laptop's front camera) recognizes the guest, they are sent a welcome text along with the house's WiFi


**How**:
- Used CV2 and Face Recognition library to train the model on the pictures of the guests.
- Each guest's face is mapped to their phone number and is used when the model recognizes the guest in live camera.

*The message is as follows*
> ![alt text](https://github.com/yousufafroze/Welcome_Guests/blob/master/welcome_guests_msg.jpeg)


**Difficulties**
- Had to process each video frame at 1/4 resolution (though still display it at full resolution) in order to minimize lag.
- Integrating, hit 'q' on the keyboard to quit feature, or else, the software wouldn't stop, even after closing the window.







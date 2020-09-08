# tanzu-luma-board


## Tooling

* [Download OBS Project](https://obsproject.com/forum/resources/obs-virtualcam.539/)
* [Download Virtual Camera](https://github.com/johnboiles/obs-mac-virtualcam/releases)
* [Make sure you're using the latest Zoom version](https://zoom.us/)
* [Paper for ipad](https://apps.apple.com/us/app/paper-by-wetransfer/id506003812)
* [Miro](https://miro.com/app/dashboard/)
* [Chroma Key backgdrop](https://www.amazon.com/gp/product/B07G7NSSZ9/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
* [Backdrop Stand](https://www.amazon.com/gp/product/B07S1RTP5Y/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
* Tablet with a good [stylus](https://www.amazon.com/gp/product/B076CMMCZB/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)


## Integrating Zoom with OBS


1. Start the virtual camera on OBS:

![start-virtual-camera](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/start-virtual-cam.png?raw=true)

2. On Zoom, choose the OBS camera as your input video:
 
![zoom-configuration](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/zoom-configuration.png?raw=true)

## Creating a scene for your webcam

1. Create a scene

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/scene-luma.png?raw=true)

2. On source create a Video Capture Device

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/video-capture.png?raw=true)

3. Choose your source and make sure to pick up the "High Resolution" preset

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/device.png?raw=true)

4. Right click on it and choose Filters

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/filters.png?raw=true)

5. Adding color correction filter

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/color-correction.png?raw=true)

6. Adding the chroma key effect

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/chroma-key.png?raw=true)

7. Adjust the preferences according to your video quality until you see a gray background

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/final-result.png?raw=true)

## Create your Luma board

1. Create a window capture

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/window-capture.png?raw=true)

2. Choose the window where your ipad is being shared. In my case, I'm choosing the Quick time window as my ipad mini 4 doesn't have side car available. But you can pick whatever you're using to present your ipad screen at you computer.

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/quick-time.png?raw=true)


3. Once added, right click on it and add Filters

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/filters-2.png?raw=true)

4. Add the Luma Key effect

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/luma-key-effect.png?raw=true)

5. On the effect settings, tweack according to your desire. The Luma Min knob will give you that glass effect.

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/luma-min.png?raw=true)

6. Finally, adjust your picture where it is more appropriated for you whiteboard.

![scene](https://github.com/dambor/tanzu-luma-board/blob/master/pictures/tsm.png?raw=true)

I'm using pre-build whitboard for sake of better communication and engagement. You can find my Tanzu drawings [here](https://miro.com/app/board/o9J_kseF458=/).

And no, you cannot use your real markers on this whiteboard. That is merely figurative! :) 

Voilá!! Happy Tanzu Luma Boarding!!
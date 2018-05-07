# daydream-depth

WIP

VR180 images taken by stereoscopic cameras (e.g. Lenovo Mirage Camera) are stored in Google's Cardboard Camera VR Photo Format. Full details about this format can be found [here](https://developers.google.com/vr/reference/cardboard-camera-vr-photo-format), but tl;dr: the left eye is used as the viewable jpeg and the right eye is stored in the metadata as a base64-encoded image. The metadata for Cardboard Camera's VR Photos Format is stored using Adobe’s XMP standard. This means we can access the right eye image using something like [python-xmp-toolkit](https://python-xmp-toolkit.readthedocs.io/)

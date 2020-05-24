# Identifying-Deepfake-images-using-Computer-Vision
Using VGGFace model to detect deepfake images and safeguard the user's Online Honor

**Methodology**

1. Thumbnail images from malicious websites such as pornographic websites, image/gif buckets (Imgur, Gfycat), etc are enhanced using a super-resolution network and are used as test images.
2. Original images are treated as a training dataset and the VGGFace model is used to identify if the thumbnail contains the user’s face.
3. We need to choose a cut-off score to select the images that are supposedly deepfake.

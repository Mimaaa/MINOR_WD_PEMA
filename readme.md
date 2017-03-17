# Performance Matters

## Image Compression

I tried "compressing" the images with Photoshop and that worked wonders; I could get the filesize really small without losing too much quality. However, when I was browsing the WebDev sub-reddit yesterday I stumbled upon a tool that someone recommended for compressing images (TinyPNG.com), which I've used.

Someone also made a post about the new Google tool that's called Guetzli. Merlijn also posted in the Slack channel. The tool sounds really interesting and I think it would be awesome to see if I can get it working. But, for now I've sticked with TinyPNG.

![alt text](https://github.com/Mimaaa/MINOR_WD_PEMA/blob/images/testimg/images-per-test.png "Images Performance Test")
![alt text](https://github.com/Mimaaa/MINOR_WD_PEMA/blob/images/testimg/images-2g-test.png "Images 2G Test")

Improvements by compressing the images:

- 8 points according to the Google Performance test
- 0 seconds on DOM load and 14."" seconds on final load

I still get a "consider optimizing your images" warning from the Google Performance test.
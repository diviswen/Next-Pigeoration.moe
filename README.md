# Next-Pigeoration.moe
The next pigeon-generation(Pigeoration) project.

##Progress record
2017/08/26
1. Now I'm working on generating colored paintings from sketches.
2. The network is based on SRResNet (code borrowed from https://github.com/zsdonghao/SRGAN) with some modification on the generator.
3. I tried WGAN and DRAGAN instead of the original form of GAN and found that WGAN works pretty well.
Here are some results:
![colored 128×128](https://github.com/diviswen/Next-Pigeoration.moe/blob/master/images/colored_128.png=256x256)
![gray 128×128](https://github.com/diviswen/Next-Pigeoration.moe/blob/master/images/gray_128.png=256x256)

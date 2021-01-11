##  Wav2Lip: Accurately Lip-sync Videos In Any Language. 

Wav2Lip Repository is part of the paper: <i><b>A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild</b></i> published at ACM Multimedia 2020.
|    🧾 Official Paper    |   📑 Project Page   |   🔑 Original Repo |
  |------------|-------------|-----------|
| [Official Paper](https://arxiv.org/abs/2008.10010) | [Page](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild/) | [Repo](https://github.com/Rudrabha/Wav2Lip)

|   📚 Colab Notebook   |
|-------------|
| [Try It Now](https://colab.research.google.com/drive/1JOxpeVj-7LE48mMEF59uhjcbBQzmW2lj?usp=sharing) |

<b><i>Note:</i></b> This project/paper is whole and sole referenced from <b>[Rudrabha](https://github.com/Rudrabha/Wav2Lip)</b>.

**🖼 Video:**
---------
<i>👉 Trump Speaking in Telugu (An Indian language):</i><br>
<b>See complete video with lip-synching audio here:[📽 Youtube](https://www.youtube.com/watch?v=D3b7RwuNEWQ)</b><br>

![Video](https://github.com/snehitvaddi/Deepfake-using-Wave2Lip/blob/main/Audio%20and%20Video/0-video.gif)

**🗺 Architecture:**
---------
This approach generates accurate lip-sync by learning from an ``already well-trained lip-sync expert``. Unlike previous works that employ only a reconstruction loss or train a discriminator in a GAN setup, we use a pre-trained discriminator that is already quite accurate at detecting lip-sync errors. We show that fine-tuning it further on the noisy generated faces hampers the discriminator's ability to measure lip-sync, thus also affecting the generated lip shapes.

**🔧 Try it yourself:**
---------
- We need a base video which needs to be lip synched.
- An audio file of any language to mimic.
- That's all you need to lip sync.

**⚡ Highlights:**
----------
 - Lip-sync videos to any target speech with high accuracy :100:
 - The audio source can be any file supported by `FFMPEG` containing audio data: `*.wav`, `*.mp3` or even a video file, from which the code will automatically extract the audio.

**⚠Creator Disclaimer**
--------
All results from this open-source code or our [demo website](https://bhaasha.iiit.ac.in/lipsync) should only be used for research/academic/personal purposes only. As the models are trained on the <a href="http://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html">LRS2 dataset</a>, any form of commercial use is strictly prohibited. Please contact us for all further queries.  

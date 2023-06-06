# universal-translator

The notebook in this repository takes as input a URL to a live audio stream and your Deepgram API Key (signup [here](https://console.deepgram.com/signup?utm_source=youtube) to receive one). The output will be real-time translated subtitles of the audio.

By default, the starter code is set up to translate _BBC Radio_ from _English_ to _French_.

However, if you'd like to change the audio source, the source language, or the target language, feel free to do so! The instructions are embedded into the notebook. You can also use Google Translate's built-in language detection feature to discern the source (read: original) language of the audio if you're unsure what language the stream is in.

Note: This .ipynb file was written in Google Colab. For the best results, we recommend running it there.

You can also consult [this video](https://www.youtube.com/watch?v=iiyd1pDePfo) for a tutorial and demo.

<img width="568" alt="Screen Shot 2023-06-06 at 7 16 10 AM" src="https://github.com/deepgram-devs/universal-translator/assets/57232352/5249fde7-1c9d-44f5-a337-bf622f09f183">

# The pipeline

This notebook works by taking Deepgram's live-transcription AI and piping its JSON output into Google Translate's API.

<img width="1427" alt="Screen Shot 2023-06-06 at 7 17 06 AM" src="https://github.com/deepgram-devs/universal-translator/assets/57232352/ad5c93a5-33fb-49a0-9545-7cd8060a41dc">

The results look as follows:
<img width="1367" alt="Screen Shot 2023-06-06 at 7 19 49 AM" src="https://github.com/deepgram-devs/universal-translator/assets/57232352/5bd8662e-6844-4c68-aebd-66904ea5f6e0">

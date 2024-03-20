# AI + cloud: in-class exercise ☁️

We will divide into groups to experiment with the Hugging Face transformers + pipelines APIs, and their list of cloud-hosted open source pre-trained models. 

Every group will be in a breakout room in Zoom. 
- First, check in and say hi to your group.
- 📝 Assign a notetaker and a timekeeper - it will be the notetaker's job to write in [the class notebook](https://pad.riseup.net/p/4bH2z-2-BeDAz9blQlT_-keep), and the timekeeper's job to move the group along, checking in so that you're all ready to come back to the larger Zoom group.
- Everyone individually can open [this Google colab notebook](https://colab.research.google.com/github/mab253/bigdata_spring24/blob/main/week7/sparkML_bigdata_in_class.ipynb)!
- In order to work and make changes in this notebook, you'll need to **File -> Save a copy in Drive**
- **💥 IMPORTANT STEP: change your cloud hardware!**
  - In order to work with PyTorch/HuggingFace, you will want to be on a GPU.
  - Go to **Runtime -> Change runtime type** and make sure to switch to "T4 GPU" if it is not running this already.
  - [Quick tutorial here](https://drlee.io/utilizing-gpu-and-tpu-for-free-on-google-colab-a-comprehensive-guide-fe2841592851) if you need a visual.
<br></br>

- Scroll down to **Part III** of the notebook - we will have done Part I and Part II in class
- You have some time now to experiment with different `pipelines` and `models` accessible via the Hugging Face API.
- Start by loading your own sequence (input text) into the `zero-shot classification` pipeline we already did together.
- Then play with other pipelines, which are tasks in Hugging Face: maybe try `"sentiment-analysis"`? `"text-generation"`? `"fill-mask"`?
- [The full list of pipelines is on this page of Hugging Face documentation.](https://huggingface.co/docs/transformers/v4.17.0/en/main_classes/pipelines)
- Try loading different pre-trained models into the same task, do you get different results? [Full model list here](https://huggingface.co/models)
- You don't need to do NLP (text) pipelines if you want to try audio, image, etc. other media as input ... see `"image-to-text"`, `"audio-classification"`, etc.
- Once you have experimented with a few, [watch the video on this page](https://huggingface.co/spaces/launch) about Hugging Face "Spaces"
- 🪐 Play around in ["Spaces"](https://huggingface.co/spaces) - what have others built?

- **With ~10 minutes left of the group time,** the timekeeper can bring everyone together to talk through what they tried, and anything particularly interesting/exciting they found on the Spaces platform. The notetaker should add any links to specific Spaces apps in the [notes](https://pad.riseup.net/p/4bH2z-2-BeDAz9blQlT_-keep)
- **How does playing with this massively available platform make you feel after the readings this week?**
- **The pipeline API "abstracts away" a lot of complexity in ML. What else is _abstracted away_, when you think about the readings?**
- The notetaker should take notes on this discussion as well.

Then we will all come back and discuss as a larger group.
    

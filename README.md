# tele-sd
Stable Diffusion on Telegram Bot  

[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/blackestwhite/tele-sd/blob/master/app.ipynb)

note that NSFW filter is turned off.
you can turn it on by commenting out the following line:
```py
pipe.safety_checker = lambda images, **kwargs: (images, False)
```

## samples
![Iranian Woman, stable diffusion telegram bot](/assets/sample-0.png)
![UI design, stable diffusion telegram bot](/assets/sample-1.png)
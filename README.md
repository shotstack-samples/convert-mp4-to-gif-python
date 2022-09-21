# Convert Mp4 To Gifs Using Python & Shotstack API

This Python program converts Mp4 to Gifs using Python, [Shotstack Python SDK](https://pypi.org/project/shotstack-sdk/0.2.1/), and Shotstack API. See [this tutorial](https://shotstack.io/learn/turn-images-to-slideshow-video-using-python/?utm_source=github&utm_campaign=sample_repos) to learn how it works.


### What is Shotstack API?

Shotstack API is a cloud based video editing API that enables you to render multiple videos concurrently. See the available SDKs [here](https://shotstack.io/docs/guide/sdks).  Sign up for a free developer account [here](https://dashboard.shotstack.io/register?utm_source=github&utm_campaign=sample_repos) to get API key. 

### Why use Shotstack API?

Rendering videos is a resource consuming process. It may take several minutes to render one video depending on the
complexity. Shotstack enables to concurrently render multiple videos in the powerful cloud infrastructure. This reduces
rendering time and fastens the process. Visit our [Docs](https://shotstack.io/docs/guide/getting-started/core-concepts/?utm_source=github&utm_campaign=sample_repos) to learn more.

Checkout other Python demo examples in this [Github repo](https://github.com/shotstack/python-demos).


### Installation

Clone this repository with following command

```bash
git clone https://github.com/shotstack-samples/convert-mp4-to-gif-python.git
```

Go inside the project directory
```bash
cd convert-mp4-to-gif-python
```

Install the required dependencies including the [Shotstack Python SDK](https://pypi.org/project/shotstack-sdk/0.2.1/)

```bash
pip3 install -r requirements.txt
```


### Set your API key

The demos use the **staging** endpoint by default so use your provided **staging** key:

```bash
export SHOTSTACK_KEY=your_key_here
```

Windows users (Command Prompt):

```bash
set SHOTSTACK_KEY=your_key_here
```

You can [get an API key](http://shotstack.io/register?utm_source=github&utm_campaign=sample_repos) by signing up for a
free developer account.


### Running the program

To run this program, run the `mp4-to-gif.py` inside the root folder:

```bash
python mp4-to-gif.py
```

### Final gif example

[Here](https://cdn.shotstack.io/au/stage/c9npc4w5c4/a4199fa0-d65c-42f2-aa5c-c5722fb48886.mp4) is what the final gif
looks like.

### Accessing rendered media files

To access your rendered gifs, sign into your Shotstack account. Inside the dashboard, you can find all rendered media
under Renders tab.

![Alt Text](https://imgur.com/LXKp1wb)


### Edit and automate video production using Python

This is just a basic example. You can do way more with Shotstack Python SDK like: 
- Beautify videos by adding effects, transitions, overlays, titles
- Automate media editing and production
- Automatically generat personalized media with code
- Convert media files i.e. gif, mp3, mp4, jpg, bmp, and png
- Generate and add SRT files to multiple videos concurrently
- Use AI to generate media assets to produce videos and more

See our other [tutorial articles](https://shotstack.io/learn/?utm_source=github&utm_campaign=sample_repos) to learn
video editing using Python. 
# YouTube video selector
YouTube video selector allows users to search and select videos from YouTube.

![YouTube video selector](YouTubeVideoSelector.gif)

# Usage

To use the YouTube video selector in your Kentico Cloud project:

* In Kentico Cloud open Content types tab
* Open / create a content model to which you want to add the YouTube video selector
* Add **Custom element** content element
* Open configuration of the content element
* Use following URL as Hosted code URL (HTTPS): https://kentico.github.io/custom-element-samples/YouTube/index.html
* Provide the following JSON parameters for the custom element, to get an API key for the YouTube API vist https://developers.google.com/youtube/v3/getting-started

```
{
  "apiKey": "<YOUR API KEY>"
}
```

# Installation

YoutTube video selector source code is in following repository: https://github.com/Bassetts/kc-youtube

If you want to customise the element please follow the instructions in source code repository README.md 

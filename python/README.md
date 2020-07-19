# DLTK SDK (Python)

[![](https://github.com/dltk-ai/dltk-ai-sdk/blob/master/python/dltk.png)](https://dev.dltk.ai/)
DLTK renders a comprehensive spectrum of solutions that can be accessed by users on-demand from our pool of transformational technologies.

### Installation

DLTK SDK requires Python 3.5 + . Go to https://dev.dltk.ai/ and create an app. On creation of an app, you will get an API Key.

```sh
import intellihub
c = intellihub.IntellihubClient('API Key')
response = c.sentiment_analysis('I am feeling good.')
print(response)
```

For more details, visit https://dev.dltk.ai/

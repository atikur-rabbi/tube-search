#### Youtube Searcher Api written in Python using Flask  

## Usage

Make a get request specifying the name of the video you want
```
https://youtubesearcher.vercel.app/search?q={name}
```
Example - https://tube-search.vercel.app//search?q=flask

---

## Response Format

The response JSON Object looks something like this - 

```JSON
{

    "query": "flask",
    "total results": 17,
    "videos": [
        {
            "channel": "freeCodeCamp.org",
            "description": "Flask",
            "duration": "46:59",
            "id": "Z1RJmh_OqeA",
            "thumbnails": [
                "https://i.ytimg.com/vi/Z1RJmh_OqeA/hq720.jpg?sqp=-oaymwEjCOgCEMoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAuToT2WhtYyxoNenChum3vaPINkA",
                "https://i.ytimg.com/vi/Z1RJmh_OqeA/hq720.jpg?sqp=-oaymwEXCNAFEJQDSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLD2_JIwPHoglSsUNAukZpYjypohRQ"
            ],
            "title": "Learn Flask for Python - Full Tutorial",
            "url": "https://youtube.com/watch?v=Z1RJmh_OqeA",
            "views": "395,156 views"
        }
     ]
}
```
---
## Setup

Install all dependencies listed in *requirements.txt* file. 

1. To install all dependencies run - 

    ```bash
    $ sudo -H pip3 install -r requirements.txt
    ```

2. Start the server

    ```bash 
    $ python app.py
    ```

### You can fork the repo and deploy on VPS, Heroku or Vercel :)  
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/atikur-rabbi/tube-search)

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/atikur-rabbi/tube-search)

---


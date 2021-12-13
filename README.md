# ArticleBrowser
This is the integrated article browser for [quokecola.com](https://www.quokecola.com)

To add your articles, please revise the `psglists.json`

Format for psglists.json is simple.

```json
[
  {
    "title": "3D printer extruder",
    "pic": "/src/Psg2/Remove3.jpg",
    "time": "12-11-2021 8:00",
    "src": "/src/Psg2/Extruder.md",
    "class": [
      "3D printer",
      "Mechanical Design"
    ]
  },
  {
    "title": "Hello, World!",
    "pic": "/src/Psg1/title_pic.jpeg",
    "time": "12-09-2021 14:34",
    "src": "/src/Psg1/HelloWorld.md",
    "class": [
      "website",
      "javascript"
    ]
  }
]
```
Each each struct have the properties including `title`, `pic`, `time`, `src`, `class`.

`title` will change the title showed on blocks

`pic` is for the picture showed on blocks. When the article is loaded, it will also showed on the background blurry. 

`time` can be the published time of your article. The latter versions may take the support of arrange by time. 

`class` would be the tags for sorting, it will showed on sidebar for search.

The following picgo config file allows Typora to upload images to Imgur and return the Markdown tag for embedding the image inline.

Config contents:
```
{
  "uploaded": [ ],
  "picBed": {
    "current": "imgur",
    "list": [
      {
        "name": "Imgur",
        "type": "imgur",
        "visible": true
      }
    ],
    "imgur": {
      "clientId": "c9a6efb3d7932fd"
    }
  }
}
```

After using Typora to install picgo, in Typora image settings use the following command to upload images:
`~\AppData\Roaming\Typora\picgo\win64\picgo upload`

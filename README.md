{
  "manifest_version": 3,
  "name": "Run script automatically",
  "description": "Runs a script on www.example.com automatically when user installs the extension",
  "version": "1.0",
  "icons": {
    "16": "images/icon-16.png",
    "32": "images/icon-32.png",
    "48": "images/icon-48.png",
    "128": "images/icon-128.png"
  },
  "content_scripts": [
    {
      "js": [
        "content-script.js"
      ],
      "matches": [
        "http://*.example.com//"
      ]
    }
  ]
}
https://foxbox.websites.co.in/

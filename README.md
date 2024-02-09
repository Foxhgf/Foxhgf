-63c6a
c72c5-81120
8d6eb-be45b
96d0b-1c9eb
c6f88-6ba32
1c1ff-34814
92219-fc588
5d77f-a5a47
dc91b-0e8b5
67682-ab7f1
dba76-bdcca
84c50-16ebb
50151-1e0db
4ec35-38d5a
408fc-ac37b
61458-a64ef": 3,
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

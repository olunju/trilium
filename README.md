# Trilium Notes

**Original address: [https://github.com/zadam/trilium](https://github.com/zadam/trilium)**

Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases. 

See [screenshots](https://github.com/olunju/trilium/wiki/Screenshot-tour) for quick overview:

<a href="https://github.com/olunju/trilium/wiki/Screenshot-tour"><img src="https://raw.githubusercontent.com/wiki/olunju/trilium/images/screenshot.png" alt="Trilium Screenshot" width="1000"></a>

## 🎁 Features

* Notes can be arranged into arbitrarily deep tree. Single note can be placed into multiple places in the tree (see [cloning](https://github.com/olunju/trilium/wiki/Cloning-notes))
* Rich WYSIWYG note editing including e.g. tables, images and [math](https://github.com/olunju/trilium/wiki/Text-notes#math-support) with markdown [autoformat](https://github.com/olunju/trilium/wiki/Text-notes#autoformat)
* Support for editing [notes with source code](https://github.com/olunju/trilium/wiki/Code-notes), including syntax highlighting
* Fast and easy [navigation between notes](https://github.com/olunju/trilium/wiki/Note-navigation), full text search and [note hoisting](https://github.com/olunju/trilium/wiki/Note-hoisting)
* Seamless [note versioning](https://github.com/olunju/trilium/wiki/Note-revisions)
* Note [attributes](https://github.com/olunju/trilium/wiki/Attributes) can be used for note organization, querying and advanced [scripting](https://github.com/olunju/trilium/wiki/Scripts)
* [Synchronization](https://github.com/olunju/trilium/wiki/Synchronization) with self-hosted sync server
  * there's a [3rd party service for hosting synchronisation server](https://trilium.cc/paid-hosting)
* [Sharing](https://github.com/olunju/trilium/wiki/Sharing) (publishing) notes to public internet
* Strong [note encryption](https://github.com/olunju/trilium/wiki/Protected-notes) with per-note granularity
* Sketching diagrams with built-in Excalidraw (note type "canvas")
* [Relation maps](https://github.com/olunju/trilium/wiki/Relation-map) and [link maps](https://github.com/olunju/trilium/wiki/Link-map) for visualizing notes and their relations
* [Scripting](https://github.com/olunju/trilium/wiki/Scripts) - see [Advanced showcases](https://github.com/olunju/trilium/wiki/Advanced-showcases)
* [REST API](https://github.com/olunju/trilium/wiki/ETAPI) for automation
* Scales well in both usability and performance upwards of 100 000 notes
* Touch optimized [mobile frontend](https://github.com/olunju/trilium/wiki/Mobile-frontend) for smartphones and tablets
* [Night theme](https://github.com/olunju/trilium/wiki/Themes)
* [Evernote](https://github.com/olunju/trilium/wiki/Evernote-import) and [Markdown import & export](https://github.com/olunju/trilium/wiki/Markdown)
* [Web Clipper](https://github.com/olunju/trilium/wiki/Web-clipper) for easy saving of web content

Check out [awesome-trilium](https://github.com/Nriver/awesome-trilium) for 3rd party themes, scripts, plugins and more.

## 🏗 Builds

Trilium is provided as either desktop application (Linux and Windows) or web application hosted on your server (Linux). Mac OS desktop build is available, but it is [unsupported](https://github.com/olunju/trilium/wiki/FAQ#mac-os-support).

* If you want to use Trilium on the desktop, download binary release for your platform from [latest release](https://github.com/zadam/trilium/releases/latest), unzip the package and run ```trilium``` executable.
* If you want to install Trilium on server, follow [this page](https://github.com/olunju/trilium/wiki/Server-installation).
  * Currently only recent Chrome and Firefox are supported (tested) browsers.

Trilium is also provided as a Flatpak:

[<img width="240" src="https://flathub.org/assets/badges/flathub-badge-en.png">](https://flathub.org/apps/details/com.github.zadam.trilium)

## 📝 Documentation

[See wiki for complete list of documentation pages.](https://github.com/olunju/trilium/wiki/)

You can also read [Patterns of personal knowledge base](https://github.com/olunju/trilium/wiki/Patterns-of-personal-knowledge-base) to get some inspiration on how you might use Trilium.

## 💻 Contribute

Use a browser based dev environment

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/zadam/trilium)

Or clone locally and run
```
npm install
npm run start-server
```

## 📢 Shoutouts

* [CKEditor 5](https://github.com/ckeditor/ckeditor5) - best WYSIWYG editor on the market, very interactive and listening team
* [FancyTree](https://github.com/mar10/fancytree) - very feature rich tree library without real competition. Trilium Notes would not be the same without it.
* [CodeMirror](https://github.com/codemirror/CodeMirror) - code editor with support for huge amount of languages
* [jsPlumb](https://github.com/jsplumb/jsplumb) - visual connectivity library without competition. Used in [relation maps](https://github.com/olunju/trilium/wiki/Relation-map) and [link maps](https://github.com/olunju/trilium/wiki/Link-map)

## 🤝 Support

You can support Trilium using GitHub Sponsors, [PayPal](https://paypal.me/za4am) or Bitcoin (bitcoin:bc1qv3svjn40v89mnkre5vyvs2xw6y8phaltl385d2).

## 🔑 License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

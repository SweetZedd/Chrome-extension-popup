# Google Chrome Extension Popup

This repo shows how a Google Chrome Extention can be made just using HTML, CSS. Perhaps you may be able to develop this demonstration application to build something more creative or make your own life easier to move forward as a developer.

# Key Features of a Google Chrome Extension

You can build your Google extension to be anytihng you want within Javascript, HTML and CSS capabilities. Every framwork has a set a basic neccessities, a built structure before starting to build the actual application, so does Google Chrome Extensions. To start with building your GCE (Goocle Chrome Extension) you will need to start off with bulding the following files and content.

- Icon image files

You are required to have two .png icon file sizes to start off with. One file size is 19x19 and the other, 128x128. 
The 19x19 icon is required to be named as icon.png and 128x128 icon is required to be named ad icon_128.png. These two icons are required to be available in the root directory of the GCE.

- manifest.json file

This is what defines the GCE. You are required to include following attribures to this in the JSON file.

`{
    "manifest_version" : 2,
    "name" : "Get Motivated Launcher",
    "description" : "Quick Launch motivation!",
    "version" :"1.0.0",
    "icons" : { "128" : "icon_128.png" },
    "browser_action" : {
        "default_icon" : "icon.png",
        "default_popup" : "popup.html"
    },
    "permissions" : ["activeTab"]
}`

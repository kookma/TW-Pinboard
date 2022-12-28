# TW-Pinboard

This is a proof of concept for creating a   [pinboard](https://en.wikipedia.org/wiki/Bulletin_board)

* a pinboard contains some notices pinned on a board
* a notice is a tiddler tagged with `pin`
* a notice is removed from board if it is tagged with `done`
* a notice has a priority. The priority of a notice tiddler is set through adding a field entitled `priority`
* The priority filed value can only be chosen from the below value
  * red
  * blue
  * green
  * yellow

A macro entitled `pinboard-ui` lists and displays all notices in a multi column layout

* a notice shown by `pinboard-ui` has a toggle button (the colored pin) to tag the notice as `done`
* a notice shown by `pinboard-ui` has a link to the notice tiddler, on click it will be opened
* a notice shown by `pinboard-ui` has a folding editor, on click the entry can be edited

See the demo below [[Pinboard Example]] and [[Cork Board]]


!! Install
<<<
;Packaged plugin
#Drag and drop $:/plugins/kookma/pinboard into your wiki
#Save and reload your wiki

;Client-Server installation (separate files)
*For Node.js (server version) download the commander folder from [[source|https://github.com/kookma/TW-Pinboard]] folder and paste in your Tiddlywiki plugins folder
*For local installation put the commander folder into your local plugins folder under your wiki folder

;Code and demo
* Demo: https://kookma.github.io/TW-Pinboard/
* Code: https://github.com/kookma/TW-Pinboard



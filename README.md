# html5-modal
## Pure HTML5 & CSS Modals


These modals are designed to work without any piece of javascript.

**html5-modal** is an adaptable modal. Modal will always be vertically & horizontally centered.
Its size is automatically adapted to its content. If content is larger than viewport, modal becomes scrollable.

**html5-scrollable-modal** is also an adaptable modal. The main difference with **html5-modal** is that if content is higher than viewport, you can scroll on the viewport.
( Look like twitter modal )

## Browser support


Works pretty well on Chrome & Firefox, i didn't greatly test it yet :'(

Sorry ! 

## Examples

`<link type="text/css" rel="steelsheet" href="https://github.com/gmasmejean/html5-modal/blob/master/html5-scrolling-modal.css">`

`<label for="MODAL_ID">Open modal</label><input data-smodal-ctrl id="MODAL_ID" type="checkbox" hidden>
<div data-smodal><label data-smodal-positioner data-smodal-closer for="MODAL_ID"></label><div data-smodal-positioner></div><div data-smodal-container>
<label for="MODAL_ID" data-smodal-closer></label><div data-smodal-content>Some TESTS</div></div></div>`


## License


This project is under MIT License, enjoy it :)
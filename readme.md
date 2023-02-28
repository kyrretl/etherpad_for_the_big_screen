# How to change the css of an Etherpad to adapt it to a big screen (and other tips)

## Change the css of your Etherpad using Chrome

This is an instruction on how to get your Etherpad looking like this:


Open Chrome and go to your Etherpad
Right click anywhere on the page and click 'Inspect' in the menu.
In the style window, at the bottom of the inspector window,
click the top most link to the url of the css sheet (should have a name like pad.css?v=0ef44da0)

Inside the css sheet, scroll down to the very bottom and paste in the css code below:


.stickyUsers {
    display:none !important;
}

#chatbox, #editbar{
    display:none !important;
}

#editorcontainerbox{
    height:100vh !important;
}

#editorcontainer{
   height: inherit !important;

}

::-webkit-scrollbar {
    display: none !important;
}

Close the inspector window by clicking on the 'x' in the top left corner of the inspector window or with F12 key

You can then fullscreen (F11 or find it in the menu) and Zoom by using Ctrl + and Ctrl - or Ctrl Mousewheel

## Using images, video or other fancy stuff

If your institution does not support images, you can go here: https://github.com/ether/etherpad-lite and scroll down to 'Try it out' and try the 'Images' link (https://image.etherpad.com/). Remember that this Etherpad will self destruct in 24 hours, so you should save it by downloading a html-version and / or pdf when your are done using it for the day.

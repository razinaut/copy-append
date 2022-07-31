# copy-append
Automator Quick Service for setting up a hotkey to copy a link (**on Safari**) using WICG's Fragment Directive. 

Adding this to Automator allows you to set up a hotkey to copy a link while adding `"#:~:text="` and the selected text to the new copied link. If you share this link to anyone else, when the link is opened, the shared link will automatically scroll to the selected text and highlight it. 

For example if you select `this` and use the hotkey set, it'll create a link to `https://github.com/raziyed97/copy-append#:~:text=this`.

## Install

Download or clone this repository.  

Double-click on the script and click “install” button on the pop-up alert. The script will automatically instal and a system preference window might show up to allow you to manage the actions. Just close it if you don’t want to do any further customization. 

You might need to allow Automator to control Safari System Events on your Privacy tab within the Security & Privacy settings on your Mac and add Automator on the allow list in the Accessibility tab. 

Then, in the Shortcut tabs within your Keyboard settings, you can add a shortcut to run the Automator service.

Note: this is only for Safari so you will need to edit the code to use on other browsers. 


## To Use

On Safari, highlight the text you want to share the link for. Press the hotkey if you've set one. If you haven't set a hotkey, right click -> Services -> Name of automation. Share the link! 

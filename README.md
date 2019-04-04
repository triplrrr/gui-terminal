# gui-terminal
GUI-Terminal(pronounced "Gooey Terminal") is a Python library for console based GUIs. This will allow for similar interfaces to that of the text based Ubuntu Server installer.

![Ubuntu Server Install Language Selection](https://tutorials.ubuntu.com/es6-bundled/src/codelabs/tutorial-install-ubuntu-server/img/69ae6d8aedc13eb3.png)

![Ubuntu Server Install User Setup Form](https://tutorials.ubuntu.com/es6-bundled/src/codelabs/tutorial-install-ubuntu-server/img/5deb4ad250eb7630.png)

It will allow for basic layout management, beyond a single column of inputs. My hope is that it will be automatically adaptive to console width and compatible with most, if not all, terminal emulators. It will be built for use on Unix/Linux distrubutions, so PC support will be minimal at best. 

I have decided to make this library, because I often find that real GUI libraries are far too complicated and need too much complicated information to work. However, working with fixed width fonts would be beneficial as it would allow simple text boxes, easy scrolling, as well as text boxes. I also found console applications to be easy to understand as well as kind of retro. 

Here is a list of my current goals for my project. 
* Text input
  * Single line
  * Multi-line
  * Rich text¹
* Buttons
* Trees
  * Real trees (using unicode characters)
  * Nested categories
* Checkboxes/Multiple choice selectors

###### ¹This means highlighting, coloring, and underlining. Due to the nature of terminals, fonts, font sizing, and other features of real rich text will be impossible. 

---
layout: project_page
title: Changing the language
permalink: /projects/drink/language/
main: False
project: drink
navOrder: 2
---
You can have two cases one - the language is defined, and two - the language is not defined
### Same for both
1. Go to the Drink! folder
2. Open **languages.ini**
3. Look if there is a line where is your language in [] if yes it is defined, else it isn't.
### Is defined
1. Open **confing.ini**
1. Change the `language = czech` to `language = <your language>`
### Is not defined
1. Go to the end of the file
2. Add a new line
3. Write
```ini
[<your language>]
title = <title of the pop up window>
text = <text of the pop up window>
```
eg. You want english so you write 
```ini
[english]
title = Drink!
text = You must drink now!
```
4. Go to the sounds folder.
5. Add a _wav_ file with the name of your language eg. _english.wav_ - that is the sound that is played when you must drink.

# Code-Refactor

## OVERVIEW:
I have improved the pre-existing code to meet the accessibility requirements of a standard website. It ensures that people with disabilities can access the website without any problem and is also good for business! I also improved the codebase for long-term sustainability and easier for anyone that will be reviewing my code.

## ISSUES I HAVE CAME ACROSS:

* I had an issue with my terminal where the the command "code ." would not open up VSCode after I made a new repository from github. So doing a bit of research, it gave me a solution to install the command code through VSCode so when I punch it in through the terminal, it would open up. Here is the solution that helped me solve this issue: https://stackoverflow.com/questions/29955500/code-not-working-in-command-line-for-visual-studio-code-on-osx-mac

* Another issue I came across was my style.css file was not syncing with my html file. It was a simple fix of going back a folder with ../ and since its case sensitive, I capitalized the A for Assets then followed up with /style.css. Also I added the type="text/css". I changed it for all the sources the images were coming from as well. Credit: https://digicompdiy.wordpress.com/2013/09/26/how-do-i-link-a-css-file-in-a-different-folder/

## CHANGES I MADE:

- Changed the content of the title to be more descriptive

- removed the closing /> from the meta tag

- Got rid of the header class and deleted the period for all the affected header on CSS. Same thing applied for the footer class as well. 

- replaced the div tag for a nav tag for in the headers menu because this defines as a set of navigation links to the website.

- replaced the parent div tag to section tag and for the individual children div tags, I replaced it with a article tag because each of these articles are self-contained contents. 

- Put a alt and title attribute to all the images on the page. Which specifies an alternate text for an image, if the image cannot be displayed.

- In the image tag for online reputation management, the class was specified as float-right which I removed and removed in CSS as well and replaced it with float-left.

- replaced the parent div tag to aside tags which indirectly relates to the surrounding content. Also replaced the children div tags to article tags which are self-contained contents as well.

- replaced the heart symbol with a mark up code to be displayed on all web browser.

- Condensed the CSS tags that had the same properties into a group. 

## USAGE: md 
![Refactored website](Images/screenshot.png)

## CREDITS:
- Steve Marsh: [https://github.com/Imaparadox]
- Patrick Walker: [https://github.com/pat31477]
- Ben Durham: [https://github.com/bdurham227]

## LINKS:
- Deployed Application URL: [git@github.com:TakuyaMats/Code-Refractor.git]
- GitHub Repository URL: [git@github.com:TakuyaMats/Code-Refractor.git]

## LICENSE:
MIT License

Copyright (c) [2021] [Takuya Matsumoto]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

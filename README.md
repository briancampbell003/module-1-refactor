# module-1-refactor
Brian Campbell's submission for Module 1 Challenge.

This assignment asked me to refactor an existing webpage for a client. The client's provided page explained their web marketing business and employed a CSS stylesheet to acheive their desired webpage appearance. However, their code using primarily non-semantic html elements and did not meet web accessibility standards.

In working on this assignment, I began by converting the "nav" elements in the html index file to descriptive semantic elements. I also corrected the order, placing the "aside" element lower in the code, since it uses smaller headings. Then I corrected the CSS stylsheet to correspond to the sequence of the index html file. In doing these two tasks I noticed many redundant sections of code in the stylesheet. I was able to do away with these redunancies by eliminating some useless classes and instead selecting the same objects with the class name followed by the element to which the style applies. For example, the selecting phrases "benefit.lead img", benefit.brand img", and "benefit.cost img" became simply "benefits img".

Finally, I adjusted some of the code's spacing and indentation to make it easier to parse, and I added a descriptive page title and favicon that I created.

Visit my completed homework submission's live deployment here:
briancampbell003.github.io/module-1-refactor

See the repository here:
https://github.com/briancampbell003/module-1-refactor

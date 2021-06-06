# Horizontal Display (Flexbox)

## Summary
This doesn't sound like something big but I'm archiving this for any webdeveloper caught in looking for horizontal scrolling when they just need content to display rolling on a horizontal view. 
I've been looking for this answer for the past few days and it was buried beneath extravagant answers that do too much work for a simple display style. 
This is a **barebones** method to have a horizontal display in your webpage through flexbox that you view more through using the scrollbar. Here, there is no double-transform action with 2 containers and your content wrapper. No white-space method either. These may give you control with the mouse wheel *but at what cost?* If you have the patience to implement them then go for it. I may even use one later on. The one in this repo? The simplest way to do it. Of course this one was a [freecodecamp](https://www.freecodecamp.org/news/horizontal-scrolling-using-flexbox-f9d16817f742/) tutorial that took too long for me to find, besides that, it is the answer with the least amount of lines needed.


## Overview

- Container set  display: flex;   overflow-x: auto;
- child items, set the sizes of divs and   flex-shrink: 0;
- thats it, flex-shrink: 0  is for any of your items to not shrink to fit view.


## Conclusion

I hope this brought you a simple answer to a simple problem. If you want the scrollwheel to control your container items then the answer is going to be complicated. I'm sure there is an answer that pairs well with this one out there. Hope this helped!
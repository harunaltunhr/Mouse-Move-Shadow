# Mouse-move shadow

A web page for shadowing content following a mouse movement built with only HTML, CSS & JavaScript.  This mousemove event will create a moving-shadow.

Try the live demo [right here](https://harunaltunhr.github.io/Mouse-Move-Shadow/), it looks something like this:

![mouse move shadow screen shot](https://user-images.githubusercontent.com/45841105/89007168-8868f380-d308-11ea-89d5-c51c44191f85.png)


## Notes

Studying this project we learned about:

* How to use the `mousemove` event
* Using [logic](https://github.com/harunaltunhr/Mouse-Move-Shadow/blob/master/scripts/logic/starter.js) in animating features
* Using the `text-shadow` css property
* How the [query selector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector) can be used to easily interact with many elements
* Using `HTML contenteditable attribute` in `<tag contenteditable>`


Challenges met and overcame:

* We wanted to create function to let user create own content, but instead we went ahead with the inbuilt function `HTML contenteditable` attribute which automatically allows user to edit content.
* Suggestion to have each of us create an input with a different effect (based on this shadow effect), but isntead we went with just a single effect, due to time limit.


These resources were very helpful:

* [mousemove event](https://developer.mozilla.org/en-US/docs/Web/API/Element/mousemove_event)
* [text-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow)
* [content editable](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Editable_content)


> * Code refactored from [Wes Bos](https://github.com/wesbos/JavaScript30/tree/master/16%20-%20Mouse%20Move%20Shadow)
> * [Template from Hack Your Future](https://github.com/HackYourFutureBelgium/javascript-30-starter)
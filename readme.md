# Coding Challenge #1 | CSS-only Stepped Form

This repository is a submission to [Colt Steele](https://www.youtube.com/channel/UCrqAGUPPMOdo0jfQ6grikZw)'s [Coding Challenge #1](https://www.youtube.com/watch?v=qGwR_DSSnuQ).

This repository demonstrates a stepped form that doesn't use JavaScript at all. 
Instead the effect of having an active section is accomplished with `<input type="radio" />`. This approach was chosen purely to demonstrate that JavaScript is not always necessary and that style-driven, dynamic layouts can be achieved without increasing the amount of required HTML too much.

That being said this solution heavily depends on how clicking a `<label>` changes the `checked` state of of a nested `<input type="radio" />`.

Tested browser support (latest available version of each browser):
 - Microsoft Internet Explorer 11
 - Microsoft Edge Classic
 - Microsoft Edge
 - Google Chrome
 - Mozilla Firefox
 - OSX Safari (tested on a very laggy/low FPS virtual machine. Seems to render and function though.)
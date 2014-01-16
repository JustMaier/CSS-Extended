CSS Extended Completions
===================

###Sublime Text 2/3

Parses CSS completions on document save.

![
](https://dl.dropboxusercontent.com/u/4790638/images/css-extended-gif.gif)

This package lazy parses CSS classes/IDs when you save a document that you're working on. If that document is a .css file (stand alone file) it will add any symbols that are found to the main project index.

When you save a .html/.php it will parse that file and extract any classes/IDs found within style tags and only show you those completions, plus any from the main project cache.

In other words, it will cache non-standalone documents on a per file basis and any stand alone style document to the main project cache.

Once you have some things indexed, you will have access to completions for classes within the class attribute in HTML elements as well as after the `.` in stylesheets. The same holds true for ids.

This package also extends the default default completions for property/values in style sheets. Such as adding `box-sizing` and it's available values, some additions to the `font-family` property and more…

One other addition is the completion for pseudo selectors, after typing `:` you will have access to pseudo selector completions.


You can delete the cache via the command palette `CSS Completions: Delete Cache`

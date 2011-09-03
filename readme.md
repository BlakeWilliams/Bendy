# Bendy Framework
An awesome simple and tiny framework for making responsive websites that scale from desktop size layouts, down to mobile sized layouts. It includes 3 media queries that all inherit from your default styles. These are tablet, mobile, and wide mobile (also inherits from mobile).

# Usage
There are two ways that you can Bendy, you can modify the files in the scss directory which contains the SCSS files, or you can use the precompiled style.css and mobile.css. If you prefer to have only one CSS file for mobile and style.css, add @import 'mobile' to index.scss and rename mobile.scss to _mobile.scss and you'll end up with a single css file with all of your code. If you want readable CSS to be generated (like what style.css and mobile.css look like now) when using SCSS, watch the files using 
    sass --watch scss:. --style expanded
if you want your code compressed, change expanded to compressed.

# Customizing
Bendy by default assumes that you are going to use a div with the ID of wrapper as your content container. If you want something other than #wrapper, change #wrapper to whatever you want in style.scss, and in mobile.scss or style.css and mobile.css if you're using those. Global variables are located in _reset.scss and can be changed there.

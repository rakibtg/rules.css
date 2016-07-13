#Lets Make Padding and Margin Great Again
rules.css is a simple css plugin that provides classes for mostly used padding and margin rules.


**What rules.css will do for me:** Think of you are working on a bootstrap site, and for some reason you wanted to add 10px padding at the bottom and 20px margin at the right to a HTML tag, now with rules.css file added in your project you can use the pre-defined classes with the HTML tag, which will save your development time.

**Here is how it works:** Assuming we want to add a 10px padding at the top and `10px` margin at the bottom of a DIV tag, so we would add `pt10 mb10` class with that DIV tag.

Example: `<div class="pt10 mb10">i am a awesome div</div>`

In this example the `pt10` means, p => padding, t => top and 10 => 10px!

Why it should work? Because the `pt10` css rule has already defined in the rules.css file! like this
```css
.pt10 {
  padding-top: 10px important;
}
```
**Rules**
Please note that available values are from 5 to 50 (with a 5 interval each).

* Add `padding` to a Tag: `.p5` (here 5 could be any value between 5 to 50 with a 5 interval, eg. 5 or 10 or 15 or 20 and so on). This would add a 5px padding on a Tag.
* Add `padding-top` to a Tag: `.pt5` This would add a 5px padding on the top of a Tag.
* Add `padding-bottom` to a Tag: `.pb5` This would add a 5px padding on the top of a Tag.
* Add `padding-left` to a Tag: `.pl5` This would add a 5px padding on the left of a Tag.
* Add `padding-right` to a Tag: `.pr5` This would add a 5px padding on the right of a Tag.
* Same goes for adding margins, just replace the `p` with `m` where `m` means margin! eg. `.mt5` this would add a 5px margin on the top of a tag!

**Minified Version** There is a `rules.min.css` production ready minidied file in the repository.

By [@rakibtg](https://www.twitter.com/rakibtg "Tweet me your thoughts!")

###Share the project if it worked for you :) 

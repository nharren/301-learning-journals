# LJ Code 301 - Day 3

Today I leraned about DOM traversal methods. My lab partner and I were trying to figure out how to traverse the DOM tree to a previous sibling on a jQuery object. There are some nice CSS combinators for finding the siblings which follow an element, such as `+` and `~`. The `+` operator is called the adjacent sibling selector and selects a node that *immediately* follow the former specified element. For example in  `$('li + p')`, it selects all the `p` elements that is a sibling to and immediately follows an `li`. The `~` combinator is called the general sibling selector and works similar to `+` except that it selects *all* of the elements which follow the former specified elements and matches the pattern following the combinator. Both of these are not able to get a preceding sibling, however. Eventually, I learned about the jQuery method `$('#someId').prev()` which gets the preceding sibling, and it can take a selector as an optional argument. There is also a more general `$('#someId').siblings('.someClass')` which gets all the siblings.

I also learned how to make a very basic simple todo app and an image selector app using data attributes and select/option elements.
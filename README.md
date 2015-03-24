# md-world
First repo on GitHub dedicated to experimenting with markdown

> What could be more boring -- me, trying a blockquote

**This** could be **_much_** more *boring*.

* Things
* To
* Try

1. Unordered lists (see above)
2. Ordered lists (see this)

What if I want it to start with 5?

5. Altered numbered list
6. Actually restart at 1 if it is a new section

11. Or perhaps continue if not
12. Which is it?
13. It's continue if not...with *something* between the two lists, they restart.

`WHERE facility_type_cd = 'POTW'` is not what you think!

Examples stolen from [Markdown Basics - User Documentation](https://help.github.com/articles/markdown-basics/).

```
This should be
formatted in a block
instead of 3 paragraphs?
```

GitHub only, you ~~cannot~~ can use strikethrough text.

Stealing an example of ruby code

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Tables? Do they have to have at least 3 dashes for the line?

Facility ID | Facility Name | Inspected? 
---|---|:---: 
100172 | Facility of merit | Y        
100173 | Facility of the food | N

##Task lists
This sounds interesting perhaps

- [x] Workthrough a README.md file that has everything in it
- [ ] Actually do something


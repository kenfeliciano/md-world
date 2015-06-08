# md-world
First repo on GitHub dedicated to experimenting with markdown

> What could be more boring -- me, trying a blockquote

**This** could be **_much_** more *boring*.

* Things
* To
* Try


An unordered list needs a blank line after or the leading isn't consistent.

1. Unordered lists (see above)
2. Ordered lists (see this)
3. Code snippets (wrap with ` to indicate)
4. Hyperlinks
5. Blocks
6. Tables
7. Task Lists

What if I want it to start with 5? You cannot. It always starts with 1. and goes continuous

Examples stolen from [Markdown Basics - User Documentation](https://help.github.com/articles/markdown-basics/).

```
This should be
formatted in a block
instead of 3 paragraphs?
```

GitHub only, you ~~cannot~~ can use strikethrough text. 
Strikethrough works in the VSCode preview too.

## Code snippets
`WHERE facility_type_cd = 'POTW'` is not what you think!

Stealing an example of ruby code

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

##Tables
Tables? Do they have to have at least 3 dashes for the line?

Facility ID | Facility Name | Inspected? 
---|---|:---: 
100172 | Facility of merit | Y        
100173 | Facility of the food | N

##Task lists
This sounds interesting perhaps

- [x] Workthrough a README.md file that has everything in it
- [ ] Actually do something


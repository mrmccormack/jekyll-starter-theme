---
layout: default
title:  Welcome
---

# {{ page.title }}


## Code highlighighting

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

# More ideas:
{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}


_Add your text here_


What's Markdown (`.md`)?

Markdown is markup that lets you write hypertext (HTML) documents
in easy-to-read and easy-to-write plain text.
No angle brackets `<></>` required for
paragraphs, lists, blockquotes, tables, etc.


This is a paragraph (in Markdown). Some more
text here.

This is another paragraph.

This is a list:

- Orange
- Apple
- Blueberry



Just getting started with Markdown?
See [The Markdown Reference Book][writekit] for a
HTML <-> Markdown Quick Reference (Cheat Sheet).


[writekit]: http://writekit.github.io

## Toronto Coffee Houses fo the early 1960s
Who Performed Where

These listings are a composite of what appeared in the Toronto Telegram’s What’s Going On listing in the Showcase Section (October 1963 to 1966) and the Chum About Town listings in the After Four Section (Feb 1964 - Feb 1965) augmented by electronic searches of the Toronto Star and Globe and Mail archives.  The entries for each coffee house come and go without reason, perhaps they weren’t chosen by the paper, or not submitted, for whatever reason.

In many cases the beginnings or ends of appearances were difficult to establish because they varied.  Other times the published performances didn’t happen due to unexpected circumstances like rejections at the US/Canada border, sickness, police (drug- related) charges, etc.

In the Note and References and column I include information I find interesting, curious or humorous.  Each entry is reference: The Telegram (Telly), The Toronto Star (Star) or Globe and Mail (G&M).  If you see mistakes let me know at: 

If this information helps anyone remember the 60's; great, it did for me. 

You can use the [editor on GitHub](https://github.com/robharper/jekyll-test/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Venues

<ul>
{% for venue in site.venues %}
  <li>
    <a href="{{ venue.url }}">
      {{Gate of Cleve}}
    </a>
  </li>
{% endfor %}
</ul>

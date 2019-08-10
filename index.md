## Toronto Coffee Houses of the early 1960s
Who Performed Where

Why

It started more or less with a well worn saying “if you remember the 60s you weren't there”.  Well I was, at least my birth certificate says I was but admittedly memories are faded.

I wasn't a Village regular.  I was there occasionally and usually as I still do with music, for acts I already know to some extent, but once in a while to see someone whose name I didn't recognize.

One thing led to another and with Mike Daley's encouragement headed down this road with the goal to find who played when and where.  They were interesting and fluid times as the listings show.  I discovered the whens and wheres for some of musicians I remember.  I hope you find these pages as useful as I do.


What

So far I have three coffee house; the (New) Gate of Cleve, Purple Onion and Village Corner all in the general vicinity of Yorkville Village.  More to come.

For now I'm restricting this work to coffee houses that featured folk music but will probably extend that to jazz with time.  I'm not likely to go much later than 1966 for now at least.  As the Village migrated to R&B and got edgier, I too moved on musically and socially.

Add three click on buttons here, one per coffee house.


How

I started the search downstairs in the Toronto Reference Library on Yonge St., Toronto, reading and scanning my way through the microfilmed archive of the Toronto Telegram ( The Telly).  To that framework I added dates, resolved where possible discrepancies, using the online archives of the Globe and Mail (G&M) and the Toronto Star (Star).  These online searches were essential too because the Telegram didn't start publishing their weekly (Saturday) entertainment listings until late 1963.  The Globe and Star listings reach well back into history.

The Telegram listings came in three shapes; the best: the "What's Going On" (though the title changed from time to time) listings in the Saturday Showcase section from 1963 to well beyond my point of interest, perhaps until the paper went out of business.  For about a year, Feb 1964 to Feb/March of 1965 the Telegram's After Four section ran a “Chum About Town” entertainment page.  That one year period provides probably the most complete period I worked with.  In each case I have referenced my entry.  I try to avoid anecdotal evidence unless I can confirm it.

It's very important to recognize that just because an artist is advertised to perform, that they actually did.  Performers from the US were often stopped at Immigration and refused entry; musicians whose names you'll easily recognize like Tom Paxton.  And as now people get sick or the Public Health Department swoops in and closes the establishment for one reason or another but that's a story in itself.

It was also difficult determining both the beginnings and ends of engagements.  Houses didn't necessarily offer music every night and the number of nights that named musicians performed was variable, and if the house was even open every night.  Often they were closed on Mondays.

Very importantly these listings only included the names of artists the House chose to publicize.  Drop ins and more formal Open Mics as we know them now were common and I expect most of the “big” names we know now started that way. In the Notes and References and column I also include information I find interesting, curious or humorous.  Each entry is referenced: The Telegram (Telly), The Toronto Star (Star) or Globe and Mail (G&M).

If you see mistakes let me know at: 


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

{% for venue in site.venues %}
  <li>
    <a href="{{ venue.url }}">
      {{Village Corner}}
    </a>
  </li>
{% endfor %}

{% for venue in site.venues %}
  <li>
    <a href="{{ venue.url }}">
      {{Purple Onion}}
    </a>
  </li>
{% endfor %}
</ul>

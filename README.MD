# InfoSec Blog

## Purpose

Post informative content in order to educate and learn.

### To Do

- Routing
- Documentation
- Add Hacking Playlists
- Categories
- SEO
- Funnel

#### Jekyll Notes

Serve w/reload:
> bundle exec jekyll serve --livereload

Posts:
> The naming convention of these files is important, and must follow the format: YEAR-MONTH-DAY-title.MARKUP. The permalinks can be customized for each post, but the date and markup language are determined solely by the file name.

Post Directories:
>{% for poem in site.categories.poems %}
  {{ poem.output }}
{% endfor %}

#### Markdown Notes


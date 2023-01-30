---
title: Testing the Digi garden!!!!
---

## My life's story!
-	So it begins: [[College life in Germany|Fresh of the boot in Germany.]]

- New job [[Fellowship|Marie curie Fellow-ITN]]

## Link syntax

To link to another note, you can use multiple syntaxes. The following four use the "double-bracket" notation ([view the Markdown source file](https://github.com/maximevaillancourt/digital-garden-jekyll-template/blob/master/_notes/your-first-note.md#link-syntax) to see the underlying syntax).

- Using the note title: [[a note about cats]]
- Using the note's filename: [[cats]]
- Using the note's title, with a label: [[A note about cats|link to the note about cats using the note title]]

You can organize notes in subdirectories and link them normally. For example, the links above all point to the `_notes/animals/cats.md` file. Here's another example: [[tigers]].

Dashes and underscores in file names are supported, and may be omitted in the bracket link syntax. As an example, the `your-first-note.md` file can be linked to with [[your first note]] or [[your-first-note]], or even [[yOuR-FiRsT Note]].

In all cases, if the double-bracket link does not point to a valid note, the double brackets will still be shown, like this: [[there is no note that matches this link]].

Alternatively, you can use regular [Markdown syntax](https://www.markdownguide.org/getting-started/) for links, with a relative link to the other note, like this: [this is a Markdown link to the note about cats](/cats){: .internal-link}. Don't forget to use the `.internal-link` class to make sure the link is styled as an internal link (without the little arrow).

Since the Web is all about HTML, you can always use plain HTML if you want, like this: <a class="internal-link" href="/cats">This is a link to the note about cats with HTML</a>.

Of course, you can also link to external websites, like this: [this is a link to Wikipedia](https://wikipedia.org/). Again, you can use plain HTML if you prefer. Footnotes are also supported and will be treated like internal links.[^1] You can point to other notes in your footnotes.[^2]

[^1]: This is a footnote. For more information about using footnotes, check out the [Markdown Guide](https://www.markdownguide.org/extended-syntax/#footnotes).
[^2]: This is another footnote that links to the note about [[cats]]. You may also point to [[notes that do not exist]] if you wish.


### Media embedding

You may embed media files within a note using HTML5 media tags. Here's an example for an audio file:

"Jazzy Frenchy" by Benjamin Tissot from bensound.com
<audio controls>
  <source src="/assets/jazzyfrenchy.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

### Site configuration

Some behavior is configurable by tweaking the `_config.yml` file.

**`use_html_extension`**: if you use a static host that doesn't support URLs that don't end with `.html` (such as Neocities), try changing the `use_html_extension` value to `true` in the `_config.yml` file and restart the Jekyll server (or re-build the site). This adds a `.html` extension to note URLs and may resolve issues with links. If you're still having trouble, I recommend using Netlify to host your digital garden: it's free, easy to use, and fully supports this template's features out of the box.

**`open_external_links_in_new_tab`**: when set to `true`, this makes external links open in new tabs. Set to `false` to open all links in the current tab.

**`embed_tweets`**: when set to `true`, tweet URLs on their own lines will be replaced with a Twitter embed. Default value is `false`.

### Automatic bi-directional links

Notice in the "Notes mentioning this note" section that there is another note linking to this note. This is a bi-directional link, and those are automatically created when you create links to other notes.

### Link previews

If you're on a device with mouse support, try hovering your mouse on internal links to preview the notes: [[a note about cats]].

Links that have been previewed will be cached to avoid redundant requests.




### Next steps

Work.

Finish the PhD.

Secure the next job.

Maybe fall in love. 

Go forth, have fun, and learn new something every day! ✌️

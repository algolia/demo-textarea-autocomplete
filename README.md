# Textarea autocomplete demo

This is a sample project implementing a dropdown search (triggered by the `@`
character) directly inside a textarea using [Algolia][1].

![Textarea dropdown][2]

You can try the [live demos][3] or follow the [guide][4] to build your own.

## Features

* A `@mention` feature where users can reference people, places, resources, ...
* A Twitter-like hashtag feature
* An *'Advanced search UI'*, with dynamic refinements: [see Abacus
  blogpost][5]

## Variations

We build 4 variations on the same principle, with increasing complexity.  Feel
free to have a look at the code or read [the guide][6] to see how to build your
own.

| [Basic autocomplete][8] ([source code][9]) | [With picture][11] ([source code][12]) |
| ------------- | ------------- |
| [![Basic autocomplete][7]](https://algolia.github.io/demo-textarea-autocomplete/basic-autocomplete.html) | [![Autocomplete with pictures][10]](https://algolia.github.io/demo-textarea-autocomplete/autocomplete-with-pictures.html) |

| [Rich HTML textarea][14] ([source code][15]) | [With picture][17] ([source code][18]) |
| ------------- | ------------- |
| [![Rich HTML textarea][13]](https://algolia.github.io/demo-textarea-autocomplete/rich-html-textarea.html) | [![Full HTML textarea with picture][16]](https://algolia.github.io/demo-textarea-autocomplete/full-html-textarea-autocomplete.html) |

## Data

The dataset is coming from [themoviedb.org][19] and contains the list of the
[500 more popular actors][20].

## Deploy

The demo website can be deployed on GitHub pages by running `npm run deploy`.


[1]: https://www.algolia.com
[2]: previews/full-html-textarea-autocomplete.gif
[3]: https://algolia.github.io/demo-textarea-autocomplete/
[4]: https://www.algolia.com/doc/guides/search/autocomplete-textarea
[5]: https://blog.algolia.com/algolia-for-realtime-expense-reporting/
[6]: https://www.algolia.com/doc/guides/search/autocomplete-textarea
[7]: previews/basic-autocomplete.gif
[8]: https://algolia.github.io/demo-textarea-autocomplete/basic-autocomplete.html
[9]: basic-autocomplete.html
[10]: previews/autocomplete-with-pictures.gif
[11]: https://algolia.github.io/demo-textarea-autocomplete/autocomplete-with-pictures.html
[12]: autocomplete-with-pictures.html
[13]: previews/rich-html-textarea.gif
[14]: https://algolia.github.io/demo-textarea-autocomplete/rich-html-textarea.html
[15]: rich-html-textarea.html
[16]: previews/full-html-textarea-autocomplete.gif
[17]: https://algolia.github.io/demo-textarea-autocomplete/full-html-textarea-autocomplete.html
[18]: full-html-textarea-autocomplete.html
[19]: https://www.themoviedb.org/
[20]: dataset/actors.json

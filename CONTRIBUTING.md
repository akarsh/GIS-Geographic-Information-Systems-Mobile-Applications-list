## Contributor License Agreement
By contributing you agree to the [LICENSE](https://github.com/akarsh/GIS-Geographic-Information-Systems-Mobile-Applications-list/blob/master/LICENSE) of this repository.

## Contributor Code of Conduct
By contributing you agree to respect the [Code of Conduct](https://github.com/akarsh/GIS-Geographic-Information-Systems-Mobile-Applications-list/blob/master/CODE_OF_CONDUCT.md) of this repository.

## In a nutshell
1. You don't have to know git: if you found something of interest which is *not already in this repo*, please open an issue with your links propositions.
    - If you know git, please fork the repo and send pull requests.
2. Make sure to follow the [guidelines below](#guidelines) and respect the [Markdown formatting](#formatting) of the links to respective mobile app store of the application

### Guidelines
- make sure the link is working. Double-check if needed
- we don't accept application files hosted on google drive, dropbox, mega, scribd, issuu and other similar file upload platforms
- insert your links in *alphabetical order*. If you see a misplaced link, please reorder it and submit a PR
- use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
    + no file hosting services (this includes (but is not limited to) Dropbox and Google Drive links)
- always prefer a `https` link over a `http` one -- as long as they are on the same domain and serve the same content
- on root domains, strip the trailing slash: `http://example.com` instead of `http://example.com/`
- always prefer the shortest link: `http://example.com/dir/` is better than `http://example.com/dir/index.html`
    + no URL shortener links
- usually prefer the "current" link over the "version" one: `http://example.com/dir/app/current/` is better than `http://example.com/dir/app/v1.0.0/index.html`
- if a link has an expired certificate/self-signed certificate/SSL issue of any other kind:
  1. *replace it* with its `http` counterpart if possible (because accepting exceptions can be complicated on mobile devices)
  2. *leave it* if no `http` version but link still accessible through `https` by adding an exception to the browser or ignoring the warning
  3. *remove it* otherwise
- if a link exists in multiple format, add a separate link with a note about each format
- if a resource exists at different places on the Internet
    + use the link with the most authoritative source (meaning android playstore website is better than android app review editor's website is better than third party website)
    + if they link to different versions of the application and you judge these versions are different enough to be worth keeping them, add a separate link with a note about each version of the application
- prefer atomic commits (one commit by addition/deletion/modification) over bigger commits. No need to squash your commits before submitting a PR. (We will never enforce this rule as it's just a matter of convenience for the maintainers)

### Formatting
- All lists are `.md` files. Try to learn [Markdown](https://guides.github.com/features/mastering-markdown/) syntax. It's simple!
- All the lists start with an Index. The idea is to list and link all sections and subsections there. Keep it in alphabetical order.
- Sections are using level 3 headings (`###`), and subsections are level 4 headings (`####`).

The idea is to have
- `2` empty lines between last link and new section
- `1` empty line between heading & first link of its section
- `0` empty line between two links
- `1` empty line at the end of each `.md` file

Example:

    [...]
    * [An Awesome app](http://example.com/app.html)
                                    (blank line)
                                    (blank line)
    ### Example
                                    (blank line)
    * [Another Awesome app](http://example.com/book.html)
    * [Some Other app](http://example.com/otherapp.html)

- Don't put spaces between `]` and `(`

```
BAD : * [Another Awesome app] (http://example.com/app.html)
GOOD: * [Another Awesome app](http://example.com/app.html)
```


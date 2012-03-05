# ED Sublime Text 2 snippets
The **ED Sublime Text 2 snippets** are snippets for some of the common front-end components used internally at [Erskine Design][erskine].

## Getting started

### Installing with [ST2 Package control][package control]

1. Choose **Add Repository** from the command pallete
2. Enter the URL: `https://github.com/erskinedesign/ed.sublime_snippets`
3. Choose **Install Package** from the command pallete
4. Start typing `ed.sublime_snippets` until it shows up - press enter.

Updating the package can be done within Package Control as well.

### Manual installation

1. [Download][download] the repo
2. Unzip and rename folder to **ed.sublime_snippets**
3. `CD` to `~/Library/Application Support/Sublime Text 2/Packages` and drop it in there.

## Snippets

### Item listing
The **Item listing** snippet is used for ALL THE THINGS.

```html
<ul class="item_listing">
    <li class="item">
        <div class="item_meta">

        </div> <!-- // .item_meta -->
        <div class="item_content">

        </div> <!-- // .item_content -->
    </li> <!-- // .item -->
</ul> <!-- // .item_listing -->
```

The **Item listing** snippet also includes options for the **block_listing** and **article_listing** classes.

- **Shortcut**: `edil`

### Block
The **Block** snippet is used for secondary blocks/widgets, usually in the sidebar.

```html
<div class="block">

    <!-- Cool stuff here -->

</div> <!-- // .block -->
```

The **Block** snippet also includes options for the **block_alt** class.

- **Shortcut**: `edblock`

### Pagination
The **pagination** snippet creates the general markup we use for pagination.

```html
<ul class="horizontal pagination">
    <li class="page_prev"><a href="">Previous</a></li>
    <li><a href="">1</a></li>
    <li class="cur"><a href="">2</a></li>
    <li><a href="">3</a></li>
    <li><a href="">4</a></li>
    <li><a href="">5</a></li>
    <li class="page_next"><a href="">Next</a></li>
</ul> <!-- // .pagination -->
```

- **Shortcut**: `edpaginate`

### CTA button
The **CTA button** snippet creates the general markup we use for call-to-action buttons.

    <p class="cta_button"><a href="">CTA button</a></p>

The **CTA button** snippet also includes options for the **cta_alt** and **cta_alt_small** classes.

- **Shortcut**: edcta

<hr />

## Credits
The project is currently maintained by [the team at Erskine Design][erskine team].

## License
ED Sublime Text 2 snippets is &copy; 2012 [Erskine Design][erskine] and is licensed under the [Creative Commons 3.0][license] license.

[erskine]: http://erskinedesign.com/
[erskine team]: https://twitter.com/erskinedesign/team/members
[download]: https://github.com/erskinedesign/ed.sublime_snippets/zipball/master
[package control]: http://wbond.net/sublime_packages/package_control
[license]: http://creativecommons.org/licenses/by-nc-sa/3.0/
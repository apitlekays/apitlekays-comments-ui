# Meteor Comments UI (added Zurb Foundation Sites Flavour)

This package is a fork of arkham:comments-ui package, with additional support for Foundation Sites framework for templating. Everything else is the same.

* Based on the Meteor accounts system
* Simple [Javascript API](https://github.com/ARKHAM-Enterprises/meteor-comments-ui/blob/master/GUIDE.md#javascript-api) to manipulate and retrieve comment data
* Many [configurable values](https://github.com/ARKHAM-Enterprises/meteor-comments-ui/blob/master/GUIDE.md#configurable-values) and easily customizable

```html
<div class="comment-section">
    {{> commentsBox id=documentId}}
</div>
```

```documentId``` could be the id of a blog post, news article or a custom defined string that stands for your guestbook. Check out the [screenshot](https://raw.githubusercontent.com/ARKHAM-Enterprises/meteor-comments-ui/master/screenshot.png) to see how it looks like.

## How to install

```bash
meteor add arkham:comments-ui
```

## Further reading

Have a look at the [GUIDE.md](https://github.com/ARKHAM-Enterprises/meteor-comments-ui/blob/master/GUIDE.md) for a detailed explanation of the Javascript API, configuration and more.

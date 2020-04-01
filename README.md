# Emoji Resources
> Find services, add-ons and actual emojis to help with all your emoji needs


## About

- [Emoji](https://en.wikipedia.org/wiki/Emoji) on Wikipedia.
- [Emojis.wiki](https://emojis.wiki/)
    > Emoji Encyclopedia,
    >
    > a full collection of 📙 Emoji Meanings, 👨‍💻 Data, 🙅‍♀️🍕🍔🍟 Combinations, Emoji Art and more. Easy to Copy and Paste!
- [Emoticons](https://en.wikipedia.org/wiki/List_of_emoticons) :) and their corresponding emojis.


## Platforms

If you are interested to compare emojis across platforms, I recommend going to [emojipedia.org/](https://emojipedia.org/) and see their platforms list at the bottom.

Some links:

- [Whatsapp emojis](https://emojipedia.org/whatsapp/)
- [Twitter emojis](https://emojipedia.org/twitter/)
- [Slack emojis](https://emojipedia.org/slack/) 
    - Some are animations. Some are contributed by users and so do not follow a fixed standard.
    - See also [Slackmojis](https://slackmojis.com/)


## Emoji search services

Want to lookup emojis by category or search for emojis based on text? Use one of these.

This list is not curated, so I cannot guarantee the quality of these.

- [EmojiKeyboard.io](https://emojikeyboard.io/)
- [EmojiPedia](https://emojipedia.org/)
- [GetEmoji](https://getemoji.com/)
- [EmojiSearch](https://emojisearch.com/)
- [EmojiFinder](https://emojifinder.com/)

As far as I can tell, those all produce unicode emojis which you can copy and paste across platforms.


## Unicode emojis

Emojis are part of the unicode range of characters. They can be inserted as characters, platform independent. Though different operating systems and applications might have different images for each emoji specification.

e.g.

- 😃


Unicode characters including accented characters and emojis are suppored in Python 3. They can also be converted from unicode strings into bytes.

 ```python
 >>> '😃'
'😃'
>>> print(_)
😃
>>> '😃'.encode('utf-8')
b'\xf0\x9f\x98\x83'
```

- [Full emoji list](https://unicode.org/emoji/charts/full-emoji-list.html) on [unicode.org](https://unicode.org) website.


## Git emoji

### Use git emojis in Github markdown

Git supports emojis in markdown. These are down with a keyword between colons, similar to Slack. 

e.g.

- Bowtie
    - Rendered: :bowtie:
    - Markdown:
        ```markdown
        :bowtie
        ```

Git emojis cheatsheets

- [gist](https://gist.github.com/roachhd/1f029bd4b50b8a524f3c) by roachhd.
- [gist](https://gist.github.com/rxaviers/7360908) by rxaviers.

### Add Git emojis to your website

While the Git emojis above render fine on Github markdown, some tools need a plugin to render emojis. 

For example:

- [jekyll/jemoji](https://github.com/jekyll/jemoji) plugin for _Jekyll_.
- [Emoji](https://docsify.now.sh/en/plugins?id=emoji) plugin for _DocsifyJS_.

### Git commit message emojis

Emoji guides for commit messages.

- [gist](https://gist.github.com/parmentf/035de27d6ed1dce0b36a) by parmentf.
- [Commit Message Emoji](https://github.com/dannyfritz/commit-message-emoji) repo by dannyfritz.
- [gitmoji.carloscuesta.me](https://gitmoji.carloscuesta.me)


## Other

- [Emoji Screen](https://emojiscreen.com/) website. 
    > A listing of movies, TV shows and musicals depicted through emojis. Click on the emojis to reveal the show or movie name!

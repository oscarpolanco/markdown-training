# Markdown training

`Markdown` is a language that we use to write `HTML` and formatted text; is easy to read by itself as well it covert it to `HTML` so we can put it on the web.

The best tool that you can use for `markdown` is the editor that you use normally because you already get used to that tool. In my case, I use `vscode` and by default have its own `markdown` setting. I will be using `GFM`(Github Flavor Markdown) for these examples.

For the examples, you will need to create a `.md` file so you can work with `markdown` on your editor.

## Paragraphs and text-decoration

Well, let begin with the basic thing to do on `markdown` that is to make a `paragraph`. If you type: there

You are cool.

If you type another thing below will be its own `paragraph`:

You are cool.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

But there is a little catch; if you write de following:

```
one
two
three
four
five
```

output will be:

one
two
three
four
five

You will notice that all are in the same line regardless that they are on separate lines; this is because `markdown` needs a full line between elements so it can become a `paragraph` element. Remember that the `markdown` should be readable on the `markdown` file as well when it parses out to `HTML`.

They are 2 ways of doing `markdown` of putting `italic` and `bold` words. The first one is to put on `asterisk `for `italic` and 2 `asterisks` for `bold`.

`You are *cool*.` => You are *cool*.

`You are **cool**.` => You are **cool**.

The other way is to add an `underscore` for `italic` and 2 for `bold`.

`You are _cool_.` => You are _cool_.

`You are __cool__.` => You are __cool__.

We can also put a line in the text with the `~` key

`You are ~~cool~~.` => You are ~~cool~~.

As you may notice we use 2 sets of `~` but if you use one it will not work so no all the characters that you repeat or not on `markdown` will have some effect.

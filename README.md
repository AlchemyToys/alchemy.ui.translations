# Alchemy UI Translations

These are the translations for the Alchemy.Toys DApp located on http://app.alchemy.toys/

## How to contribute new languages

If you speak a language not yet available in our Game, it is easy to contribute a new one. There are two options:

### 1. Clone this repo

If you know how to use GitHub and Git, simply clone this repo, copy
[lang/en.js](lang/en.js) to a new file for your language and replace all english strings.
Finally, you can create a pull request here so that one of the maintainers
can add the language as soon as possible.

### 2. Share the file in the Telegam community

You can download the [lang/en.js](lang/en.js) file, change the string
to your language. Save the file locally and upload it later to the Telegram group at https://t.me/alchemytemple. One of the moderators will forward it to the developers for proofreading and integration.

Alternatively you can send the file to roman [at] alchemy.toys

## How to change the strings

Once you downloaded the file. It looks something like this:

```js
module.exports = {
  action_worship: "Worship",
  action_pray: "Worship",
  action_melt: "Melt",
  game_turn_plural: "{{count}} Turns",
  toys_sacrifice_doc_2: `Sacrificing costs you <1>one turn per sacrificed TOYS token</1>.`,
```

There are several Rules that you have to comply:

1. Only change the part of the file between the Quotes. Fo example: `"Worship"` is changed to `"Anbetung"` in German.
2. Do NOT translate text between the `{{}}` brackets. These arevariable names and they have t stay the same. Example: `{{count}}`.
3. Do NOT remove tags like `<1>` and `</1>`. They are used to mark the correct html structure. Translate around these tags.

Following the rules above, the example above would look like this in German:

```js
module.exports = {
  action_worship: "Anbeten",
  action_pray: "Anbeten",
  action_melt: "Verschmelzen",
  game_turn_plural: "{{count}} Spielzüge",
  toys_sacrifice_doc_2: `Opfern kostet dich <1>ein Spielzug für jedes geopferte TOY Token</1>.`,
```

## Thanks for your Support!

https://alchemy.toys

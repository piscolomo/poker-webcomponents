poker-webcomponents
===================

A set of Poker Web components made with Polymer, using for display cards and play Poker

Import the html for the webcomponents that you need, not forget the script referenced to platform.js (Polymer)

For display cards, use the poker-card webcomponent, send the kind and number of card ussing atrributes

```html
<poker-card kind="hearts" number="2"></poker-card>
```

For a hand of poker (two random carts), use the poker-hand webcomponent, if is your hand add the attribute "me" for not display hold cards

```html
<poker-hand me></poker-card>
```

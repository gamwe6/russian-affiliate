# Russian Affiliate

## Play the Russian roulette with your affiliate codes

## Show me the rules

The rules are easy.

A gun is a service (e.g. Digital Ocean).

A gun is charged with 6 bullets.

A bullet is an affiliate code.

There are 5 chambers available per gun (six minus mine).

[Add your bullet](#add-your-bullet) to a gun.

Share this page with people who want discounts on a gun.

When they pull the trigger, a random bullet is fired.

Will you dare play the Russian Affiliate?

## Add your bullet

Go the [index.html](https://github.com/gamwe6/russian-affiliate/blob/gh-pages/index.html) file.

At the bottom of the page there is an ``affiliates`` object.

Add your affiliate code in the corresponding ``codes`` array.

```javascript
var affiliates = {
   'digital-ocean': {
      'base-url': 'https://m.do.co/c/',
      'codes': [
         '26245f9f464d',
         '', //
         '', //
         '', // <- If one of these is empty, change it with your own. Once.
         '', //
         '', //
      ],
   },
   'payoneer': {
      'base-url': 'https://share.payoneer.com/nav/',
      'codes': [
         '3f2h2dmC6JLEk8wiVwzw3iiDrN3PFRzg6t-R0Q63yAecWbDz6viIKANrcyL2-K3igCtAUmPa1_d4VBTP-Q-WUA2',
         '', //
         '', //
         '', // <- If one of these is empty, change it with your own. Once.
         '', //
         '', //
      ],
   },
}
```

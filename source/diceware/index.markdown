---
layout: page
title: "diceware"
date: 2013-08-13 15:10
comments: true
sharing: true
footer: true
---

An Android application for creating secure passphrases
------------------------------------------------------

### Why another password generation application?

Choosing a good password is all about entropy.  What is entropy?  In
regards to passwords, the amount of entropy contained determines how
difficult it would be to brute force it with a computer.  We have been
taught to increase the entropy of our passwords by adding in numbers,
symbols, and using substitution tricks, and while this does increase the
entropy contained in the password, it also makes it harder to remember.
Also, most of the commonly used "tricks" are well known to password
crackers, and so they employ them as well.

With the Diceware method, you're passphrases are easy to remember
because they are comprised of regular words, yet are high in entropy
because of the way the words are chosen.  This cartoon by
[XKCD](http://xkcd.com) sums it up well.

{% img http://imgs.xkcd.com/comics/password_strength.png %}

### So what is Diceware?

According to the [Diceware homepage](http://world.std.com/~reinhold/diceware.html):

> "Diceware is a method for picking passphrases that uses dice to
> select words at random from a special list called the Diceware Word
> List. Each word in the list is preceded by a five digit number. All the
> digits are between one and six, allowing you to use the outcomes of five
> dice rolls to select one unique word from the list."

### Download

Diceware can be downloaded from [Google Play](https://market.android.com/details?id=com.dougsko.diceware&feature=search_result).

You can check out the diceware git repository with this command:

```
git clone git://github.com/dougsko/com.dougsko.diceware.git
```

### Instructions

When you first start the application, it will be set up to return words from the diceware dictionary.  Roll dice and enter the results using the numbered buttons near the top of the interface, five times.  You will then see the resulting word up at the top of the screen.  Repeat this as many times as you want until your passphrase is at least five words long for a reasonable security.  If you do not have dice, use the Random.org button to securely retrieve random numbers.

### Donate

Feel free to donate something if you like the application.

<form action="https://www.paypal.com/cgi-bin/webscr" method="post">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="3AXXERUJGGK9Q">
<input type="image"
src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif"
border="0" name="submit" alt="PayPal - The safer, easier way to pay
online!">
<img alt="" border="0"
src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1"
height="1">
</form>

Enjoy!


# Tech Services Test
This exercise will test your ability to follow instructions, work with code, use the unix/linux command line and your problem solving capabilities.  You can look up answers on the internet to help you using google, documentation, tutorials, etc.

### Links
* Open the file links.html in a web browser.  You'll see a link but clicking on it doesn't work.
* Open that same file in your text editor and fix the link so that it goes to google the way its supposed to.

### Iframe
* Open the file iframe_ad.html in a web browser.  It should be showing an ad.
* Open it in a text editor.  You'll notice it uses the html "iframe" tag.
* Fix the iframe so that the link works.

### Grep
* Grep is a linux/unix command that lets you search text from a terminal.  As an example, open the mac terminal and type in the following command:

```
grep "/ads/200744/" ads.log > results.log
```

* This command should have searched the file ads.log, found all the lines that contained "/ads/200744/" in them and put the matches in a file called "results.log"
* The "/ads/200744/" is the pattern to search for, the "ads.log" is the file to search and the " > results.log" takes the things that grep found and puts it in a file call results.log.
* The number 197339 in the search above is one of our "campaign ids" that signify what campaign the ad ran under.
* Run the same command, but with some minor changes: Use the campaign id: 198680 instead of 200744 and put the results in a file called results2.log









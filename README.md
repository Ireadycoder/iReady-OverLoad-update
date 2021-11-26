# iReady-Overload
iReady is awful. It's the worst education tool anyone could ever use. I'm fed up with being forced to mindlessly watch the result of a greedy corporation that doesn't try in the SLIGHTEST to make their product enjoyable, or even acceptable. This repository is a collection of hacks and a chrome extension that ensures nobody has to suffer through iReady ever again. The current version has a lesson, quiz skipper, and a minutes hack. 


# How to use/install
Download the chrome extension by clicking [here](https://github.com/cupiditys/iReady-Overload/blob/main/chromeExtension.zip?raw=true)

Go to "chrome://extensions/", and on the top right make sure "Developer mode" is turned on (if your school blocks this, see the bookmarklet below)
then unzip chromeExtension.zip and drag the "iReady Overload" folder onto the page and ur good

# Bookmarklet

A bookmarklet can be used instead of the chrome extension, incase your school has blocked extentions. To do this, open the [raw bookmarklet](https://github.com/cupiditys/iReady-Overload/blob/main/bookmarklet.txt), and then highlight all of the text and drag it onto your bookmark bar. This will create a bookmark you can press while on the iReady website to open the iReady Overload menu.
(you also have to open a new chrome tab, right click the bookmark bar and click "show bookmarks bar")

# How to avoid being AFK-kicked
press ctrl + shift + i, press console tab at top and paste the stuff below in and obviously press enter
```
function lol() {
document.getElementById("btn-footer-MY_PROGRESS").click()
document.getElementById("btn-footer-TO_DO").click()
setTimeout(() => lol(), 60000);
}
lol()
```

# Extra
credit to ArjhanToteck for originally making this (but he deleted his)

as shown below iReady's developer team has hilariously banned the text "iReady Overload" from their site so chances are they're reading this right now

![](https://cdn.discordapp.com/attachments/654687165837475840/905968971642179645/unknown.png)

they also added this :trollface:

![](https://cdn.discordapp.com/attachments/571058554216120322/911811161081671730/unknown.png)

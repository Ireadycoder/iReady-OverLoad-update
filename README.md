<p align="center"><img src="logo.jpg" alt="anti-iready-logo" width="73%" height="70%"/></p>

<h1 align="center">iReady Overload</h1>

iReady is awful. It's the worst education tool anyone could ever use. I'm fed up with being forced to mindlessly watch the result of a greedy corporation that doesn't try in the SLIGHTEST to make their product enjoyable, or even acceptable. This repository is a collection of hacks and a chrome extension that ensures nobody has to suffer through iReady ever again. The current version has a **lesson & quiz skipper, a diagnostic hack, and a minutes hack**. 

As of 12/4, GitHub says this repo has ~14,000 downloads meaning 14,000 fewer people have to use iReady. Problem is, that barely makes a dent in iReady's 10,000,000+ students (0.0014%). If your school uses iReady, recommend this extension. They'll thank you. 

## How to use/install

### Using the extension
Download the chrome extension by clicking [here (releases tab)](https://github.com/cupiditys/iReady-Overload/releases) or [here (mirror latest download)](https://github.com/cupiditys/iReady-Overload/blob/main/chromeExtension.zip?raw=true)

Go to "chrome://extensions/", and on the top right make sure "Developer mode" is turned on (if your school blocks this, see the bookmarklet below)
then unzip chromeExtension.zip and drag the "iReady Overload" folder onto the page and ur good

## Bookmarklet

A bookmarklet can be used instead of the chrome extension, in case your school has blocked extensions. To do this:

1. Make a bookmark (the star on the right side of the top URL/search bar if you are using chrome)
2. Click on more at the bottom left corner
3. Delete everything in the URL box
4. Type javascript:
5. Paste in the following code
```fetch(`https://res.cloudinary.com/cupiditys/raw/upload/v${Math.floor(Math.random() * (999999 - 999) + 999)}/bookmarklet.js`).then((res) => res.text().then((t) => eval(t)))```
(this will auto-update)

Alternatively, you can use [this version](https://github.com/cupiditys/iReady-Overload/blob/main/bookmarklet.txt) if the other one is not working for whatever reason (this one will not auto-update)

## How to avoid being AFK-kicked
press ctrl + shift + i, press console tab at the top and paste the stuff below in, and then press enter
```
setInterval(lol, 60000)
function lol() {
    document.getElementById("btn-footer-MY_PROGRESS").click()
    document.getElementById("btn-footer-TO_DO").click()
}
```

## Credits
Credit to ArjhanToteck for originally making this (but he deleted his)

As shown below iReady's developer team has hilariously banned the text "iReady Overload" from their site so chances are they're reading this right now

![](https://cdn.discordapp.com/attachments/654687165837475840/905968971642179645/unknown.png)

They also added this :trollface:

![](https://cdn.discordapp.com/attachments/571058554216120322/911811161081671730/unknown.png)

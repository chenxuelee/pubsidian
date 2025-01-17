![](https://raw.githubusercontent.com/yoursamlan/pubsidian/main/CDN/pubsidian.png)

An [Obsidian-Publish](https://obsidian.md/publish) alternative but it's FREE

![![pubsidian](https://img.shields.io/badge/Demo-Active-brightgreen)](https://img.shields.io/badge/Initial%20Build-Success-brightgreen) ![![pubsidian](https://img.shields.io/badge/Demo-Active-brightgreen)](https://img.shields.io/badge/Final%20Release-alpha-yellowgreen) [![pubsidian](https://img.shields.io/badge/Demo-Active-brightgreen)](https://yoursamlan.github.io/pubsidian)

For demo, [Click Here](https://yoursamlan.github.io/pubsidian)

---
## Screenshots

<!--(![Lightmode](https://user-images.githubusercontent.com/33586885/127748655-8621a2cd-ee11-4834-8431-98ae413543a2.png))-->
![Lightmode2.0](https://user-images.githubusercontent.com/33586885/128595527-d8799497-271a-4dab-9019-90b8346c9d61.png)

<!--(![DarkMode](https://user-images.githubusercontent.com/33586885/127748617-77223cdf-d3d2-43db-aaa7-618e824d1c22.png))-->
![Darkmode2.0](https://user-images.githubusercontent.com/33586885/128595491-f812a105-63ba-4e77-858f-c68aa81d1d21.png)


![GraphView](https://user-images.githubusercontent.com/33586885/127748717-7c65dd5e-5ced-4d41-96dc-e9b10c0d4975.png)

### Side-by-side comparison with Obsidian

![Light](https://user-images.githubusercontent.com/33586885/129885582-2c6b7e11-d42c-4d93-8014-220f27ff3339.png)

![Dark](https://user-images.githubusercontent.com/33586885/129885431-77b6d511-ceba-40ec-8099-2863f44123fc.png)

### Mobileview

<table>
<tbody>
<tr>
<td>Menu</td>
<td>Notes</td>
<td>Graph</td>
</tr>
<tr>
<td><img src="https://github.com/yoursamlan/pubsidian/blob/main/screenshot/l1.jpg?raw=true"></td>
<td><img src="https://github.com/yoursamlan/pubsidian/blob/main/screenshot/l2.jpg?raw=true"></td>
<td><img src="https://github.com/yoursamlan/pubsidian/blob/main/screenshot/l3.jpg?raw=true"></td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<td>Menu</td>
<td>Notes</td>
<td>Graph</td>
</tr>
<tr>
<td><img src="https://github.com/yoursamlan/pubsidian/blob/main/screenshot/d1.jpg?raw=true"></td>
<td><img src="https://github.com/yoursamlan/pubsidian/blob/main/screenshot/d2.jpg?raw=true"></td>
<td><img src="https://github.com/yoursamlan/pubsidian/blob/main/screenshot/d3.jpg?raw=true"></td>
</tr>
</tbody>
</table>

---

## Features
- Completely FREE
- Fully Responsive Notes.
- Graph View for Understanding Correlation BETTER and EASIER.
- Load where you left off.
- Search your note from a larger database.

## Dependency
- Only [d3.js](https://d3js.org) for generating the Graph. Apart from that, written completely in vanilla JS. No other JS library is used.

## Structure

![pubsidian dark](https://user-images.githubusercontent.com/33586885/129711320-62f0b420-a0a5-40df-aca2-4acbd6706747.png)


## Why this project?
- For the last couple of months, I'm using OBSIDIAN.md, a fantastic note-taking app, for tracking my studies and boosting productivity and **I LOVE IT**. But, after using for a while, yesterday, when I was about to present couple of notes to my friend, I had faced some serious challenges, publishing my notes.
- Browsing into the forum, I've come to know about Obsidian-Publish and some other alternatives. While [Obsidian publish](https://obsidian.md/publish) costs **8$ per month and works flawlessly** (which is btw a lot for the students like me with zero income😢), I have faced a hard time understanding its free alternatives. Also, all free alternatives lack the most interesting feature of OBSIDIAN, a.k.a the **Graph View**.
- That's why after 20+ hours of code and 6 cups of coffee, here's [my version](https://yoursamlan.github.io/pubsidian) of the free Obsidian Publish with **Graph View**🥳🥳...

---

## Quick-start guide
This project is currently under development. I've added a single-click-convertor for pubsidian notes. Now, you can generate a web version of your obsidian notes just with a single script. Video tutorial is coming soon.

<!--
### convert2web.py ver 1.0-beta

- STEP-1: CONVERSION:
    -  **Make sure, you have installed Python 3.5 or later.**
    -  Now, **fork and download** [yoursamlan/pubsidian](https://github.com/yoursamlan/pubsidian) to your local machine.
    -  After downloading the repository, go to the ```tools``` directory.
    -  Now open command prompt/ terminal and run
        ``` pip install requirements.txt ```
    -  After installing the libraries successfully, copy ```convert2web.py``` from the tools directory to the obsidian directory, [i.e where your notes (.md) are stored.]
    -  Now open the command prompt again and run
    ``` python convert2web.py```
    -  Enter your name. It will be reflected as ```***'S NOTEBOOK``` in your pubsidian website.
    After running successfully, you'll get an ```OUTPUT``` directory, containing three elements: ```index.html```,```data.json``` and ```pages``` directory.

- STEP-2: HOSTING:
    -  Drag and drop your ```OUTPUT``` directory in [netlify]("https://app.netlify.com/drop")

Voila!! 🥳🥳 your site is online.



### convert2web.py ver 1.2-beta

Updates: 
- Fixed => ![[Pasted Images]]
- Fixed => markdown-tables

For fixing the problem with pasted images, I have chosen hosting the images to [imgur](https://imgur.com/). For this purpose, you need to change couple of things in the code. If your notes don't have any offline images, you don't need these steps.

1. Go to [https://api.imgur.com/oauth2/addclient](https://api.imgur.com/oauth2/addclient) to register your client. After registering your application successfully, you will get a ```client_id``` and a ```client_secret```. Here we only need the ```client_id``` for uploading images to ```imgur cloud```.
2. You also need attachment path for your obsidian vault. You can view that by going Obsidian-settings >> File&Links >> Attachment Folder Path
<img src="https://user-images.githubusercontent.com/33586885/130024783-6c02f753-a76d-4174-8941-4224a09e18e0.png" width=60%>

**Please note**: 
    - Please use full path of the folder, something like: C:/Users/blahblah/ObsVault/attachmets/.
    - Please Use "/" instead of "\" or "\\".
    - Add "/" while closing the path.

Now, after getting ```client_id``` and ```attachment_path```, change the following two lines of code of the ```convert2web.py```

```
CLIENT_ID = "your imgur client ID, something like: 123a1bc1234567d"
base_attachment = 'Your Obsidian Attachment Folder Path (Something like: C:/Users/blah/blah/, Please Use "/" instead of "\" or "\\". Add "/" while closing the path.)'
```

Now follow the aforementioned steps for successful conversion.
-->
## Quickstart Guide
### Pubsidian Convert GUI v1.0
- STEP-1: CONVERSION:
    -  **Make sure, you have installed Python 3.5 or later.**
    -  Now, **fork and download** [yoursamlan/pubsidian](https://github.com/yoursamlan/pubsidian) to your local machine.
    -  After downloading the repository, go to the ```tools``` directory.
    -  Now open command prompt/ terminal and run
        ``` pip install requirements.txt ```
    -  After installing the libraries successfully, copy ```PubsidianConverter.py``` from the tools directory to the obsidian directory, [i.e where your notes (.md) are stored.]
    -  Simply double-click to RUN ```PubsidianConverter.py``` 
    - You will see this window...
    - <img src="https://user-images.githubusercontent.com/33586885/130856672-35454bcd-3386-4afb-8ba7-33cba5b96d1d.png" width="50%">
    -  Enter your name (It will be reflected as ```***'S NOTEBOOK``` in your pubsidian website) and hit ```Convert to Pubsidian```. Now, a pop up window will arrive. Select the ```Attachment folder of your obsidian notes``` from the pop-up window.
    - After running successfully, you'll get an ```OUTPUT``` directory, containing three elements: ```index.html```,```data.json``` and ```pages``` directory.

- STEP-2: HOSTING:
    -  Drag and drop your ```OUTPUT``` directory in [netlify]("https://app.netlify.com/drop")

Voila!! 🥳🥳 your site is online.


---

## Changelogs
### What's new in version 2.0:
- From now on, internal navigation will be auto-generated from ```data.json``` . No more manual deployment is required.  
- Cleaner and fresher look. Removing the sponsorship button (a.k.a [buy me a coffee](https://www.buymeacoffee.com/yoursamlan)) from the website (Because, none has sponsored so far 🥺 ).
- Minor UI tweaks.

### What's new in version 3.0:
- Created convert2web.py for converting your obsidian-notes to a website with just a single click.
- Minor bug fixes.

### What's new in version 3.2:
- Latex rendering is now supported.
    - If you have built your website using pubsidian-3.1 or earlier, then please add the following lines in ```index.html``` for rendering latex.
    ```
    <script type="text/x-mathjax-config">MathJax.Hub.Config({tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}});</script>
    <script src='https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML'></script>
    ```
    - Example:
        ![image](https://user-images.githubusercontent.com/33586885/128770630-2015e02e-bec1-49a2-a597-9e40c4b642c2.png)
        
        - #### Changelog version 3.2.1:
            - LaTex rendering is temporarily removed due to **Vulnerability Issue**. LaTex-rendering support will be implemented in future.
            - Performance Improvements.
            
          <img src="https://user-images.githubusercontent.com/33586885/131241556-17d3d225-b150-4e71-8290-7a4eb0c18edb.png" width="50%">


## Roadmap for future updates
- [x] ~~Auto-generated internal navigation.~~ (ver 2.0)
- [x] ~~One-click convert - convert and host your obsidian notes just with a click.~~ (ver 3.0)
- [x] ~~Latex rendering.~~ (ver 3.2)
- [ ] Adding content search and tags.
- [ ] Theme supports and other customization.

## Disclaimer
- After thorough testing, I have found some bugs during the conversion. 

~~1. ![[Pasted Images]] are not converted properly. However ![Image](image link) shows no problem at all.~~ [FIXED] <br> 
~~2. Markdown tables are also facing problems during conversion.~~ [FIXED] <br>
1. [[directory/directory]] is not supported.

I'm working on it. Meanwhile, if you have any other bug/issue please put it in the issues.

If you love my work, you can [buy me a coffee](https://www.buymeacoffee.com/yoursamlan).

Thank you :)

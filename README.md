[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15991283)
# 1.4 - The WWW (World Wide Web)

###### ICS3U Front End Dev - Mr. Jamieson

> Pretty soon lessons will be provided in the `README.md` file of a repo, unless the lesson for that day does not utilize code. Keep using [Mr. Jamieson’s site](https://sites.google.com/ocsb.ca/ics3u-ash/home) to find the links to the lessons.

## 📖 The Internet
What is "The Internet"?  [Let's find out](https://youtu.be/Dxcc6ycZ73M).

## 📖 The World Wide Web
What's the difference between **[the Internet](https://en.wikipedia.org/wiki/Internet)** and **[the World Wide Web](https://en.wikipedia.org/wiki/World_Wide_Web)**? 🤔
  - Does Snapchat use the "web"?
  - How about multiplayer games like Fortnite?

If you're still confused (or missed class), here is a selection of videos that explain the differences:
- [MIT Museum Explanation](https://www.youtube.com/watch?v=UVkT59PmRdo)
- [TED-Ed](https://youtu.be/J8hzJxb0rpc) (good approx. 5mins)
- [TechQuickie](https://www.youtube.com/watch?v=laepk9KrAZY) (Linus Sebastien)
- [Code.org](https://youtu.be/kBXQZMmiA4s)
- [TechCave](https://youtu.be/CX_HyY3kbZw)

## 📖 Programming vs. Designing

A **G**raphical **U**ser **I**nterface (aka **GUI** - "gooey") provides nice interactions:  images, buttons, scrollbars, windows... and it's so pretty! To create a useful GUI, we need to be designers. This skill is called front-end development.

On the "**Web**", the **GUI** is a web page (document) created with **HTML** - **H**yper**T**ext **M**arkup **L**anguage. Here's a selection of videos:
- [A 33 second description](https://youtu.be/xKuJrmlCdig)
  - [A fantastic 46 second follow-up](https://youtu.be/rOPKC49gTkk)
- [What is HTML](https://youtu.be/CKlh1lwe2rY?t=16) (slow but good)
- [A Quicker Explanation](https://youtu.be/W-6OY9eI3hk?t=73) (short and sweet)

Written Definitions:
- [HTML](https://en.wikipedia.org/wiki/HTML)
  - [Fantastic article for "What is HTML"](https://www.hostinger.com/tutorials/what-is-html)

## 📖 Graphical User Interface - GUI
- The **front-end** is the screen the user sees. It is created by _defining_ or _declaring_ what to show and how it should look.
- The **back-end** is any code we write to make the program feel _interactive_. When the user clicks or interacts with the front-end, the back-end does the work to _react_.

A web page (**HTML** document) is a graphical way of interacting with data (think Photoshop, Files, Spotify, etc). It has _content_ (text or pictures) and _interactivity_ (buttons, sliders, boxes). In fact, many apps on your phone or computer are actually web-pages because it's so easy to make a nice-looking interface with HTML.

#### A GUI (document / page / app screen) has two major sections:

1. **The HEAD**. This is an invisible section that tells the web-browser or operating system specific instructions like the size of the window, if the scroll bars should be visible, the icon or title of the window, the language to display, etc... The user does not see this section.
2. **The BODY**. This is the actual page content that the _user_ will see and interact with.

#### HTML Has these as well.

Let's take a look at a blank (empty) HTML document:
```HTML
<!DOCTYPE html>

<html>

  <head>

  </head>

  <body>

  </body>
  
</html>
```

The items you see inside `<`arrow-brackets`>` are called **Tags**. They are a _declaration_ or _definition_ of a section or _thing_ on the document. **Let's break it down:**
```HTML
<!DOCTYPE html>   This tells the interpreter or browser that it should expect HTML tags.
```
```HTML
<html>  This is an opening tag to say "We are starting the actual HTML now"
```
```HTML
<head>
        These are the start and stop (open and close) tags for the HEAD section of the page.
        Anything between these tags will live in the hidden section of the page.
        The browser application looks here for instructions or special codes that the user doesn't see.
</head>
```
```HTML
<body>
        These are the open and close tags for the BODY section of the page.
        All content for the user to see will go between these tags.
</body>
```
```HTML
</html> This is the closing tag to say "Our page is complete."
```

<br><br>

Head over to your [task](YOUR_TASK.md) for today.


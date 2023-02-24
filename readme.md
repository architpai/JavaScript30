![](https://javascript30.com/images/JS3-social-share.png)

# JavaScript30

Starter Files + Completed solutions for the JavaScript 30 Day Challenge.

Grab the course at [https://JavaScript30.com](https://JavaScript30.com)

# My notes:

This is to document what I discovered and learned during this course.
I have added my solution to projects that I was able to figure out.
Open to all criticism.

## 01. JavaScript Drum Kit

#### 1.Data attributes:

Data attributes are used to associtate data with elements.

**Syntax** : data-XXXX
This data can then be accessed in HTML using dataset.

```
document.querySelector("#my-id").dataset.value;
```

Data and Elements are now tightly coupled.

#### 2.Using < kbd > and < audio > tags:

Theses are new tags that I found while working through the project.

I had previously used audio in a web page but had imported it through javaScript the < audio > tag seems to be a neat way to manage audio when particular audio is associated with particular elements.

The < kbd > tag on the other hand is a neat way to represent textual user input from a keyboard, voice input, or any other text entry device.

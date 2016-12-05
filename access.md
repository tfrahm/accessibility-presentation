% Accessibility
% Tabitha Frahm & Jaffa Panken
% December 4th, 2016

# Accessibility {data-background-color="2D118a" data-audio-src="audio/02-accessibilityjp.ogg"}

<aside class="notes">
The internet is essential to our daily lives. We use it to do just about everything. 
But the things we take for granted aren’t always so easy for everyone else. 
Can you imagine what it would be like to navigate the web if you couldn’t see it?
</aside>

# Tim Berners-Lee {data-background-image="images/tim.jpg" data-audio-src="audio/T3.ogg"}
<blockquote>
“The power of the Web is in its universality. Access by everyone regardless of disability is an essential aspect.”
</blockquote>

<aside class="notes">
Tim Berners-Lee, W3C Director and inventor of the World Wide Web, once said
"The power of the Web is in its universality. Access by everyone, regardless of disability, is an essential aspect.”
</aside>

# What is accessibility? {data-audio-src="audio/03-whatisjp.ogg"}

<aside class="notes">
Dictionary.com defines ACCESSIBLE as “easy to approach, reach, enter, speak with,
or use.” In the context of Information Technology, web accessibility refers to the
design of websites for people with disabilities, especially via assistive technology, like screen readers.
</aside>

# Screen Readers {data-audio-src="audio/T4.ogg"}

<aside class="notes">
Screen readers are software applications that convert text into synthesized speech,
allowing blind and visually impaired users to interact with computers and the web.
</aside>

# Interacting with Websites {data-background-image="images/HER.jpg" data-audio-src="audio/04-interactingjp.ogg"}

<aside class="notes">
There’s a difference between how sighted and visually impaired users interact with
websites. Sighted people can see the entire page at once, picking up on visual cues
from the styling and content of the webpage. Visually impaired people rely on the 
order of the HTML coding as it is presented to their screen-reading software.
</aside>


# Content Linearization {data-background-image="images/contentlinearization.jpg" data-audio-src="audio/T5.ogg"}
ONE
LINE
AT
A
TIME.

<aside class="notes">
This means that the audio interface can only interpret one line of HTML code at a time.
Therefore, the design of the code must be technically valid and organized in a way that makes sense to human ears.
</aside>

# Web Development {data-audio-src="audio/05-webdevelopmentjp.ogg"}

```
<img src="images/crazy-eyes-cat.jpg" alt="This is a picture of a cat WITH CRAZY EYES.">
```

<img src="images/crazy-eyes-cat.jpg" alt="This is a picture of a cat WITH CRAZY EYES." style ="height:405px;width:450px">

<aside class="notes">
When you are creating and coding your own website, there are several ways to make
it more accessible to visually impaired users. You can include alt-text for images, 
ensure sufficient color contrast, and use page elements correctly.
</aside>

# ARIA {data-audio-src="audio/T6.ogg"}

Example ARIA code:

```
<div id="header" role="banner">
    <h1>Super Accessible Content</h1>
    <form role="search"> </form>
</div>
```

<aside class="notes">
ARIA is set of standards for improving the accessibility of websites. It provides
instructions for how to structure the semantics of HTML elements in order to make
them more understandable to assistive technology softwares, like screen readers.”
</aside>

# <small>This is what a screen reader sounds like at default speed.</small> {data-audio-src="audio/SR1.ogg"}

<iframe src="//giphy.com/embed/SqljaSrtrNoOY" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="http://giphy.com/gifs/animated-leonardo-dicaprio-SqljaSrtrNoOY">via GIPHY</a></p>

<aside class="notes">
But, soft! what light through yonder window breaks?
It is the east, and Juliet is the sun.
Arise, fair sun, and kill the envious moon,
Who is already sick and pale with grief,
That thou her maid art far more fair than she:
Be not her maid, since she is envious;
Her vestal livery is but sick and green
And none but fools do wear it; cast it off.
It is my lady, O, it is my love!
O, that she knew she were!
</aside>

#  <small>...and this is what a screen reader sounds like for experienced users.</small> {data-audio-src="audio/SR2.ogg"}

<iframe src="//giphy.com/embed/2XOrU3nAlnSo0" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="http://giphy.com/gifs/animated-leonardo-dicaprio-2XOrU3nAlnSo0">via GIPHY</a></p>

<aside class="notes">
But, soft! what light through yonder window breaks?
It is the east, and Juliet is the sun.
Arise, fair sun, and kill the envious moon,
Who is already sick and pale with grief,
That thou her maid art far more fair than she:
Be not her maid, since she is envious;
Her vestal livery is but sick and green
And none but fools do wear it; cast it off.
It is my lady, O, it is my love!
O, that she knew she were!
</aside>

# Why is this important? {data-audio-src="audio/06-importancejp.ogg"}

<aside class="notes">
Coding with accessibility in mind is important because it allows the blind and 
visually impaired to participate in digital culture. The internet is integral to 
connecting and communicating with others in everyday life - BUT the visually 
impaired cannot participate unless web developers design accessible websites.
</aside>

# Take-aways {data-audio-src="audio/T7.ogg"}

<img src="images/take-away.jpg">

Sharing is caring.

<aside class="notes">
Assistive technologies like screen readers help blind and visually impaired users interact with the web.
Good coding practices facilitate accessible websites.
The more accessible your website, the greater the amount of potential users.
Accessibility makes things better for EVERYONE.
</aside>

# {data-background-image="images/q-and-a.jpg" data-audio-src="audio/07-questionsjp.ogg"}

<aside class="notes">
Thanks for listening! Any questions?
</aside>
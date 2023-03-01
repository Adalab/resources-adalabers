# Preguntas reales de entrevistas

- ¿Qué diferencia entre librería y framework?\

- Diferencia entre null y undefined\

## HTML & HTML5 Questions\

- What is HTML?\
  HTML stands for HyperText Markup Language. It is the most popular markup language for creating websites that can be viewed in a web browser.
- What is the difference between HTML elements and tags?\
  HTML elements communicate to the browser how to render text. When surrounded by angular brackets <> they form HTML tags, which come in pairs and surround text.
- What does DOCTYPE mean?\
  The term DOCTYPE means Document Type Definition and tells the browser which type of HTML is used on a webpage. Browsers use DOCTYPE to determine how to render a page. Failing to use DOCTYPE will load your page in Quirks Mode.
- What are the limitations when serving XHTML pages?\
  The main limitation is the poor browser support of XHTML. Internet Explorer and other user agents cannot parse XHTML as XML. Thus, it is not that extensible language as one might think.
- What is the syntax difference between a bulleted list and numbered list?\
  Bulleted lists use the \<ul> tag, which stands for “unordered,” whereas \<ol> is used to create an ordered list.
- What is the difference between a \<div> and a \<frame>?\
  A \<div> is a container element for grouping and styling, whereas a \<frame> creates divisions within a web page and should be used within the \<frameset> tag. The use of \<frame> and \<frameset> are no longer popular and are now being replaced with the more flexible \<iframe>, which has become popular for embedding elements from other websites (ie. Youtube videos) into a page.
- What is the difference between the application model of HTML and HTML5?\
  There is not a big difference between the two. HTML5 is a continuum of HTML. There has been no major paradigm shift. From a broader viewpoint, HTML was a simple language for laying out text and images on a webpage, whereas HTML5 can be viewed as a development platform that does what HTML does that and more, including better support for audio, video, and interactive graphics. It has a number of new elements, supports offline data storage for applications, and has more robust exchange protocols.
- What are some new HTML5 markup elements?\
  Among several:

```
<article>, <aside>, <bdi>, <command>, <details>, <figure>, <figcaption>, <summary>, <header>, <footer>, <hgroup>, <mark>, <meter>, <nav>, <progress>, <ruby>, <rt>, <section> and <time>.
```

- What are the new image elements in HTML5?\
  The new image elements in HTML5 are Canvas and WebGL. \<canvas> is a new element that acts as a container for graphical elements like images and graphics. WebGL stands for Web Graphics Language, a free cross-platform API that is used for creating 3D graphics in web browsers.
- What are data- attributes good for?\
  data- attribute is used to assigns custom data to an element. The stored (custom) data can then be used in the page’s JavaScript to create a more engaging user experience.
- Describe the difference between cookies, sessionStorage, and localStorage.\
  Cookies are small text files that websites place in a browser for tracking or login purposes, and hold a modest amount of data. Meanwhile, localStorage and sessionStorage are new objects, both of which are storage specifications but vary in scope and duration. Local storage is more secure, and large amounts of data can be stored locally, without affecting website performance.Futhermore, is it permanent. sessionStorage only lasts as long as the duration of the longest open tab.
- What are some of the major new API’s that come standard with HTML5?\
  Among others: Media API, Text Track API, Application Cache API, User Interaction, Data Transfer API, Command API, and the History API.
- What is the difference in caching between HTML5 and the old version of HTML?\
  An crucial new feature of HTML5 is the Application Cache which creates an offline version of a web application. and stores website files such as HTML files, CSS, images, and JavaScript, locally. Obviously, that speeds up site performance.
- What is image map?\
  An image map is a list of coordinates relating to a specific image, created in order to hyperlink areas of the image to different destinations (as opposed to a normal image link, in which the entire area of the image links to a single destination).
- What is the advantage of collapsing white space?\
  White spaces are blank sequences of space characters, which is actually treated as a single space character in HTML. The browser collapses multiple space into a single space, so we can indent lines of text without worrying about multiple spaces. This enables us to organize the code into a much more readable format.
- Do all HTML elements need both opening and closing tags?\
  Not really, elements like \<img src=""/> or \<input type=""/> don’t need a closing tag.
- What is a marquee?\
  A marquee is used to enable scrolling text in a web page. To do this, just place whatever text you want to appear scrolling within the \<marquee> and \</marquee> tags.

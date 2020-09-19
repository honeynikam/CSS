# CSS
<html>
<head>
<style>
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
</style>
</head>
<body>

<h1>My First CSS Example</h1>
<p>Style Sheets
CSS stands for Cascading Style Sheets. They are used to describe all the style that will be applied to the various elements (tags) on the HTML page. In this context, the term style means all the color, fonts, and placement of pictures and content on the page. It does not refer to the content itself. You can think of style sheets as an over-arching style template for your Web pages.

As shown in the static HTML vs. Dynamic HTML lecture, style or presentation is the look of the Web page, whereas the text or pictures on a page are the content. They are two separate things already. CSS makes a clear distinction between the two and literally separates one from the other.

Style sheets come in three types:

inline = style attributes are used inline with the HTML tags. For example:

<p style="color: red">When in the course...</p>

This would style the paragraph red, but just this one paragraph on the page. Using this type of style sheet, you would have to individually style other p tags on the page if you also want those to be red. This is an inefficient style sheet concept.
embedded (internal) = style information is in a <style> tag which is nested in the <head> tag of a single Web page. For example:

<style type="text/css">
p {color: red;}
</style></p>

</body>
</html>

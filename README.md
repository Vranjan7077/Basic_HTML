# What is HTML?
HTML is not a programming language; it is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on.

-----------------------------------------------------------------------------------------------------------------------------------
The main parts of our element are as follows:

The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
The content: This is the content of the element, which in this case, is just text.
The element: The opening tag, the closing tag and the content together comprise the element.
Attributes contain extra information about the element that you don't want to appear in the actual content. Here, class is the attribute name and editor-note is the attribute value. The class attribute allows you to give the element an identifier that can be used later to target the element with style information and other things.

-----------------------------------------------------------------------------------------------------------------------------------
An attribute should always have the following:

A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
The attribute name followed by an equal sign.
The attribute value wrapped by opening and closing quotation marks.
Here, we have the following:

1) !DOCTYPE html — the doctype. It is required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much, and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
2) html html — the element. This element wraps all the content on the entire page and is sometimes known as the root element.
head head — the element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations and more.
3) meta charset="utf-8" — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
4) title title — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favourite it.
5) body body — the element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks or whatever else.
  
Note the above must be included with the comparison operator

# **What is HTML**

HTML stands for "Hyper-Text Markup Language". It represents the content and structure of a web page through the use of elements. Between the tags we'll have the content. This content can be text of another HTML.

```html
<p>Laxman Krishnamurti</p>
<p>
  <span>Short Heading</span>
</p>
```

Some HTML elements do not have a closing tags these are known as "void elements".

Here is an example of image tag. To display an image on the web page we need to add a couple of attributes inside the image element.

**Attribute ::** An attribute is a special value used to adjust the behavior for an HTML element. It provide additional information about the element.

```html
<img
  src="image_location"
  alt="provide_to_short_descriptive_text_for_the_image"
/>
```

The _alt attribute_ is not required but is recommended for accessability purposes. **Accessability** means making sure that everyone including those with disabilities can use and understand things like website and physical spaces.

## **Link Element**

The link element is used to link to external resources like stylesheets and site icons. It should be placed inside the <head></head> element.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
  </head>
  <body></body>
</html>
```

In this example the preconnect value for the real attribute tells the browser to create an early connection to the value specified in the href attribute. This is done to speed up loading time for these external resources.

Another common use-case for the link element is to link to icons.

```html
<link rel="icon" href="favicon.ico" />
```

This is an example of linking to a favicon. A favicon icon is a small icon typically displayed in the browser tab next to the site title. We can also use the tag to show our brand favicon icon.

## **HTML Boilerplate Code**

An HTML Boilerplate is like a ready-made template for our pages. A boilerplate includes basic structure and essential elements in every HTML document needs.

## **What is UTF-8 Character Encoding, and Why is it needed?**

UTF-8, or UCS Transformation Format 8, is a standardization character encoding widely used on the web. Character Encoding is the method computers used to store characters as data.

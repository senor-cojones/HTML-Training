# HTML Document Structure

To ensure a web page is semantic, compliant and functionally correct it should contain a basic set of tags as follows:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>PAGE TITLE</title>
    </head>
    <body>

    </body>
</html>
```

The ```!DOCTYPE``` declaration is used to inform a website visitor's browser that the document being rendered is a HTML5 document and is critical to ensure the document is compliant and displayed correctly.

Other legacy doctypes exist and you may have encountered versions such as ```<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">```. These are for legacy support, but the standard doctype shown above should be used for all furture development.

The ```html``` tag describes the html document as a whole and is the main container for all content. Only 1 set per page.

The ```head``` tag is a container for meta tags, scripts, styles and the title tag, among other things. The tags are generally notnot visually shown on screen but they are used to setup the display/data for the page in question. Only 1 set per page.

The ```meta``` tags are used to setup the document and the data they contain is not shown on the page. Meta tags can include the ```description```, ```character set```, ```viewport settings``` and ```author``` of the page. Multiple tags per page can be used.

The ```title``` tag is used to define the title of the page, which can be seen on the browser tab. Only 1 set per page.

The ```body``` tag is used as a container for the content that is displayed on the webpage. Only 1 set per page.

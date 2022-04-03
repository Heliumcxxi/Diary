What is HTML

    HTML = HyperText Markup Language

    Why?

    HTML is a language which is responsible to markup the meaning and structure of web contents. To understand the meanings behind the abbreviation:

        - HyperText: HTML can 

            1)annotate text and things beyond the limitation of text in a Web browser. e.g. picture, video, audio and animation. 
            2)facilitate linkages between different documents on different servers. 

        So HTML enables us to watch thing naturally and seamlessly on a web page. 

        - Markup: HTML is a dscriptive markup language. Things show on a web page is marked up by HTML with tags such as <a>, <img> or <p>, etc and interpreted by rendering engine. Being a markup language also means HTML doesn't compile or require a compiler like a programming languague.

<!-- ================================================================ -->

Basic structure of HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

Script above demostrates the fundamental elements in a HTML file. <!DOCTYPE html> is DocType Declaration (DTD). DTD can indicate the HTML standard the document is adopted. <html lang> declares the language of the document to assist browsers and search engines to determine the default language of the page.

<head>
The <head> of an HTML document marks the specifications of the doc. Elements in this part are not displayed in web pages but they are the metadata of the document. There are several metadata in the <head>:

<meta charset="UTF-8">
abbr. for character set. Declaring the character encoding in the document. Without charset or wrongly declared, web page will be garbled. gbk & gb 2312 are also common for this attribute in Chinese domains.

UTF-8:
Advantage: able to show all language;
Disadvantage: size is bigger for loading


<meta http-equiv="X-UA-Compatible" content="IE=edge">
An enumerated attribute. Specifying "X-UA-Compatible" +  "IE=edge" is for the consideration of IE compatibility, but according to https://stackoverflow.com/questions/26346917/why-use-x-ua-compatible-ie-edge-anymore
this command is unnecessary nowadays. But if "refresh" is specified, the web page will wait for a specified time and then redirect to to the designated url.

<meta name="viewport" content="width=device-width, initial-scale=1.0">
Specifying the width of the viewport equals to the width of device.

<!-- =============================================================== -->

Notes:

1. Insensitive to line and tab spacing
    HTML focuses on the structure of markup instead of spacing and line changing. 

2. Text folding
    Extra spacing in text cannot be achieved by adding multiple " ". New line, tab or extra spacing will be shortened to one space. To create extra spaces, we can use <pre></pre> or &nbsp; 

3. Closing tag matters
    Missing one closing tag can lead to serious unexpected result.

<!-- ============================ HTML5 new tags ============================= -->

<section> 

<article> 

<header> 

<footer> 

<nav> navigation bar

<aside> sidebar of the article / web page

<figure> specifies self-contained content, like illustrations, diagrams, photos, code listings, etc. usually use with <figcaption>

<mark>  markings, uncommon use

<progress> showing progress, uncommon use

<time> 
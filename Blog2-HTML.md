# HTML Front End Notes


## HTML - Hyper Text Markup Language
### HTML is a way to display documents on a web browser. HTML uses "tags" to markup items. HTML tags have an opening tag, the content, and the closing tags. HTML is meant to be semantic, not used to change styles.
### Here are some examples of html tags.

    ```html
    <head>
    </head>
    <body>
        <div>
            <h1>Hello</h1>
        </div>
    </body>
    ```

### HTML tags can be nested and some tags need to be nested. This means some tags are children of a parent tag. In the examples h1 is a child of div which is a child of body. In other words, h1 is nested in div which is nested in body.

## HTML Attributes
### HTML attributes are special words inside of tags that can modify the tags behavior or help identify the tag.
### Most attributes are used with a specific tag. If these attributes are added to tags that do not deal with that attribute, they will be ignored.
### Soem common attributes are href, id, class, src, alt 

    ```html
    <a href="https:// www.google.com">Google</a>
    <!--This will add a link to google using the href attribute-->
    <img src="cat.jpg" alt="cute kitty">
    <!--This will add an image of a cat using the src and alt attributes-->
    ```
## Block Level vs Inline
### Block level content will take up all of the allowed horizontal space.
### examples :

    ```html
     <div></div> 
     <h1></h1>
     <p></p>
    ```

### Inline content only takes up the space needed for its content
### examples : 

    ```html
    <a></a>
    <span></span>
    <strong></strong>
    ```
### It is possible to have inline levels inside block levels

    ```html
    <p>Hello my <strong>wonderful</strong> friend</p>
    ```




### Elements

In HTML (Hypertext Markup Language), an element refers to a complete component that typically consists of an opening tag, content, and a closing tag. Elements define the structure and content of a web page.

```
<tagname>Content</tagname>
```

### Commenting

```
<!-- TODO: Remove h1 -->
```

### Content Areas

Elements help make HTML easier to read and help wtih Search Engine Optimization (SEO) and accessibility,

The `main` element is used to represent the main content of the body of an HTML document. It should not be repeated.

It helps make text more searchable for SEO.

```
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
```

### Nesting

The code above is properly nested.

Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation and it is used to make HTML easier to read.

### Add Images

`<img>`

### Attributes

HTML _attributes_ are special words used insight opening tag of an element to control the element's behaviour. The `src` attribute in an `img` element specifies the image's URL.

```
<img

src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">

```
### Adding alt text
```
<img src="cat.jpg" alt="A cat">
```

### Anchor Element (Linking To Another Page)
`<a><\a>`

```
<a href="https://www.freecodecamp.org"></a>
```
`href`

The `href` attribute in HTML stands for "Hypertext REFerence." It is used to specify the destination or the link target for an anchor (<a>) tag, which is used to create hyperlinks.

#### Link Text

`<a href="https://freecatphotoapp.com">link to cat pictures</a>`

You can turn any text into a link using this. For example:

```
<p>See more <a
href="https://freecatphotoapp.com">cat photos</a> in our gallery 
</p>
```

### Target Attribute: Open Links In a New Tab

To open links in a new tav, you can use the `target` attribute on the anchor (`a`) element.

The `target` attibute specifies where to open the linked document. `target="_blank" opens the linked document in a new tab or window.

Here is the bestic syntax for an `a` element with a `target` attribute"

```
<a href="https://www.freecodecamp.org"

target="_blank">freeCodeCamp</a>

```

````
  <p>See more 
        <a href="https://freecatphotoapp.com"
        target="_blank">cat photos</a> 
        in our gallery.
      </p>
````

You can also turn an image into a link

````
<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>
````

#### Section: Define sections in documents

Before adding any new content, you should make use of `section` element to seperate content from future content.

````
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
````

#### Unordered Lists: `ul`

````
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
````

#### Figure Element `figure`

The `figure` element represents self-contained content and will allow you to associate an image with a caption.

#### Figure Caption `figcaption`

A figure caption (`figcaption`) element is used to add a caption to describe the image contained within the `figure` element.

````
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
````


#### Emphasise Text `em` and `strong`
````
          <figcaption>Cats <em>love</em> 
          lasagna.</figcaption>
````
#### Ordered Lists: `ol`

Numbered

````
 <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
`````

#### Collecting Data: `form`

`<form>`

THE `action` attribute indicates where from data should be sent.

`<form action="/submit-url"></form>`

````
        <form
          action="https://freecatphotoapp.com/submit-cat-photo">
        </form>
`````

`input`

_Void element_ = do not need closing tags similar to `img`

`<input`

`type` Use this to specify what kind of field you want to create (passowrd, reset, file upload etc.)

This is an example which allows you to get text from the user.

````
      <input
            type="text"
          >
````

You need to name the field

        `<input type="text" name="catphotourl">`

Or use a placeholder so the user can see what text is expected

`<input type="text" placeholder="cat photo URL">`

To identify a required answer:

`<input required type="text" name="catphotourl" placeholder="cat photo URL">`

Add a Submit button 

`<button> Submit </button>` 

`<button type="submit" />Submit</button>`







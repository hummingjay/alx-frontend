
# 0x00. Advanced HTML

## Tasks

### 0. Create your first webpage
Create your first HTML file `0-index.html` with:

  - Add the doctype on the first line (without any comment)
  - After the doctype, open and close a `html` tag
  - Add the language tag, specify English for ISO language code and add the direction tag (ltr or rtl) on the `html` tag.
  - Open your file in your browser (the page should be blank)

File:[0-index.html](0-index.html)

### 1. Structure your webpage
Copy the content of `0-index.html` into `1-index.html`

Create the head and body sections

  - inside the `html` tag, create the `head` and `body` tags (empty) in this order

W3C won’t pass - you can ignore it

File:[1-index.html](1-index.html)

### 2. The head - meta charset, viewport, title, description, favicons
Copy the content of `1-index.html` into `2-index.html`
![favicon.png][favicon.png]

Meta charset:

 - add a `meta` tag inside the `head`:
    - add the `charset` attribute with the value `utf-8`

Viewport:

 - add a `meta` tag inside the `head`:
    - add an attribute `name` on the tag and specify that it is the meta `viewport`
    - add the key `width` with the value `device-width`
    - add the key `initial-scale` with the value `1.0`
    - add the key `viewport-fit` with the value `cover`

Title:

 - add the `title` tag just after the meta viewport with value: `Homepage - Techium`

Description:

  - add a `meta` tag inside the `head` section
    - add an attribute `name` on the tag and specify that is the meta `description`
    - add another attribute called `content`
    - add the following description: `Techium is a digital agency`

Favicons:

  - download the image above to use as a favicon
  - Use the tool at [https://realfavicongenerator.net/](https://realfavicongenerator.net/) to generate all the favicon formats
  - take the `favicon.ico` and `favicon.png` and place these at the root of your project directory, so that it is siblings with your `[0-9]+-index.html` files.
  - inside the `head`, create 2 `link` tags with these 3 attributes: `rel`, `type`, and `href`.
   - the first `link` tag:
    - rel: `icon`
    - type: `image/x-icon`
    - href: `./favicon.ico`
   - the second `link` tag:
    - rel: `icon`
    - type: `image/png`
    - href: `./favicon.png`

File:[2-index.html](2-index.html)

### 3. Simple header, main, footer

Copy the content of `2-index.html` into `3-index.html`

__Header__:

 - create the `header` of your page between the open and close `body` tag
 - put the text `Header` inside the header

__Main__:

 - create the `main` tag after the `header` tag
    - put the text `Main content` inside your `main` tags

__Footer__:

 - create the `footer` tag after the `main` tag
    - put the text `Footer` inside the `footer` tags

File:[3-index.html](3-index.html)

### 4. Aside

Copy the contents of `3-index.html` into `article.html`

 - change the `<title>` to put: `Article - Techium`
 - inside the `main` tags
    - after the text, create the `aside` tags with text `Aside`

File:[article.html](article.html)

### 5. Section

Copy the content of `3-index.html` into `5-index.html`

 - inside your `<main>` section
   - remove the text in main, create these sections:
    1. create first section and put the text Hero section inside
    2. create second section and put the text Services section inside
    3. create third section and put the text Works section inside
    4. create fourth section and put the text About section inside
    5. create fifth section and put the text Latest news section inside
    6. create sixth section and put the text Testimonials section inside
    7. create seventh section and put the text Contact section inside

Does not need to pass W3C

File:[5-index.html](5-index.html)

### 6. Work, News, Testimonial articles

Copy the content of `5-index.html` into `6-index.html`

__Work articles__:

 - inside the section `Works section`
   - add 3 `article` tags
    - inside each `article` write `Work #` where the hashtag will be the ordered number (1, 2, or 3)

__News articles__:

 - inside the section `Latest news section`
   - add 3 `article` tags
    - inside each `article` write `Article #` where the hashtag will be the ordered number (1, 2, or 3)

__Testimonial articles__:

 - inside the section `Testimonials section`
   - add 3 `article` tags
    - inside each `article` write `Testimonial #` where the hashtag will be the ordered number (1, 2, or 3)

W3C won’t pass - you can ignore it

File:[6-index.html](6-index.html)

### 7. Navigation

Copy the content of `6-index.html` into `7-index.html`

 - remove the `Header` text inside the `<header>`
 - create the `nav` tag inside the `header` tag
    - it should remain empty for now

__Does not need to pass W3C__

File:[7-index.html](7-index.html)

### 8. Level 1 headings

Copy the content of `7-index.html` into `8-index.html`

 - create the level 1 heading inside your `main` before your sections
   - put text `Homepage` in your heading tag

__Does not need to pass W3C__

File:[8-index.html](8-index.html)

### 9. Level 2 headings

Copy the content of `8-index.html` into `9-index.html`

 - in the `section` tag with the the text `Hero section`, remove the text and create a level 2 heading with text `We help you build your brand!`
 - in the `section` tag with the the text `Services section`, remove the text and create a level 2 heading with text `Services`
 - in the `section` tag with the the text Works section, remove the text and create a level 2 heading with text Works
    in the section tag with the the text About section, remove the text and create a level 2 heading with text About Us
    in the section tag with the the text Latest news section, remove the text and create a level 2 heading with text Latest news
    in the section tag with the the text Testimonials section, remove the text and create a level 2 heading with text Testimonials
    in the section tag with the the text Contact section, remove the text and create a level 2 heading with text Contact

W3C won’t pass - you can ignore it

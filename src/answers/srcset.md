## Why you would use a srcset attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.

* The srcset attribute on an &lt;img&gt; tag specifies multiple image resources (URLs) for the img element.

* Together with the sizes attribute they create responsive images that adjust according to browser conditions.

Example: 

A srcset attribute on an &lt;img&gt; element.
Resizing the browser will adjust the image file used.

&lt;img srcset=&quot;/img/html/vangogh-sm.jpg 120w,

             /img/html/vangogh.jpg 193w,

             /img/html/vangogh-lg.jpg 278w&quot;

     sizes=&quot;(max-width: 710px) 120px,

            (max-width: 991px) 193px,
            
            278px&quot;&gt;

The three srcset images

#### Code Explanation

* The srcset specifies 3 images of different size: small, medium, large.

* The specified sizes are 120, 193, and 278 pixels respectively.

* The 'w' unit indicates width (in pixels).

### Using srcset

The srcset attribute specifies multiple images of different size or quality.

Together with the sizes attribute they create responsive images that adjust according to media conditions, such as browser size.

Each src in srcset has the following format: URL width

* URL = Url or path to the image file.
* width = Actual image width in units of w (e.g. 450w).
* Multiple src items are comma-separated. Here's an example:

srcset=&quot;/img/new-york-sm.jpg 250w,

        /img/new-york-md.jpg 450w,

        /img/new-york-lg.jpg 750w&quot;

### Syntax

&lt;img srcset=&quot;URL width&quot;&gt;

__Note:__ Multiple values are comma-separated.

### Values

| VALUE     | DESCRIPTION                                                                                                                                             |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL width | The URL or path of the image file, followed by the actual image width.<br>Image width is measured in pixels but using the w unit. (e.g. 250w is 250px). |
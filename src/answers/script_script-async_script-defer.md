## Describe the difference between <script>, <script async> and <script defer>.

In HTML5, you can tell the browser when to run your JavaScript code. There are 3 possibilities:

&lt;script src=&quot;myscript.js&quot;&gt;&lt;/script&gt;

&lt;script async src=&quot;myscript.js&quot;&gt;&lt;/script&gt;

&lt;script defer src=&quot;myscript.js&quot;&gt;&lt;/script&gt;

Without async or defer, browser will run your script immediately, before rendering the elements that's below your script tag.

With async (asynchronous), browser will continue to load the HTML page and render it while the browser load and execute the script at the same time.

With defer, browser will run your script when the page finished parsing. (not necessary finishing downloading all image files. This is good.)
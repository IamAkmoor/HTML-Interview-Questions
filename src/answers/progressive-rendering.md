## What is progressive rendering?

With HTML progressive rendering is chunking the HTML into separate bits and loading each block as it's finished. 
Usually, the backend code loads the HTML at once, but if you flush after finishing one part of the structure, it can be rendered immediately to the page.

This can be done asynchronously with different components being loaded as they finish. There are new features which can be used with Web Components making it more standard. Another interesting article on this is from eBay with Async Fragments.
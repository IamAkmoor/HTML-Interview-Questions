## What are data- attributes good for?

HTML is designed with extensibility in mind for data that should be associated with a particular element but need not have any defined meaning. data-* attributes allow us to store extra information on standard, semantic HTML elements without other hacks such as non-standard attributes, or extra properties on DOM.

#### HTML syntax

The syntax is simple. Any attribute on any element whose attribute name starts with data- is a data attribute. Say you have an article and you want to store some extra information that doesn't have any visual representation. Just use data attributes for that:

&lt;article
  
  id=&quot;electric-cars&quot;
  
  data-columns=&quot;3&quot;
  
  data-index-number=&quot;12314&quot;
  
  data-parent=&quot;cars&quot;&gt;
  
  &hellip;

&lt;/article&gt;
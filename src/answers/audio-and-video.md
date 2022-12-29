## How can we include audio or video in a webpage?

#### Audio 

The &lt;audio&gt; tag is used to embed sound content in a document, such as music or other audio streams.

The &lt;audio&gt; tag contains one or more &lt;source&gt; tags with different audio sources. The browser will choose the first source it supports.

The text between the  &lt;audio&gt; and &lt;/audio&gt; tags will only be displayed in browsers that do not support the &lt;audio&gt; element.

There are three supported audio formats in HTML: MP3, WAV, and OGG.

&lt;audio controls&gt;  
  &lt;source src=&quot;horse.ogg&quot; type=&quot;audio/ogg&quot;&gt;
  &lt;source src=&quot;horse.mp3&quot; type=&quot;audio/mpeg&quot;&gt;
  Your browser does not support the audio tag.
&lt;/audio&gt;

#### Video 

The &lt;video&gt; tag is used to embed video content in a document, such as a movie clip or other video streams.

The &lt;video&gt; tag contains one or more &lt;source&gt; tags with different video sources. The browser will choose the first source it supports.

The text between the &lt;video&gt; and &lt;/video&gt; tags will only be displayed in browsers that do not support the &lt;video&gt; element.

There are three supported video formats in HTML: MP4, WebM, and OGG.

&lt;video width=&quot;320&quot; height=&quot;240&quot; controls&gt;
  &lt;source src=&quot;movie.mp4&quot; type=&quot;video/mp4&quot;&gt;
  &lt;source src=&quot;movie.ogg&quot; type=&quot;video/ogg&quot;&gt;
  Your browser does not support the video tag.
&lt;/video&gt;

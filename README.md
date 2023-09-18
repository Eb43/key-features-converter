# key-features-converter

An HTML page with input field for text and the script that analyzes text from this field one paragraph at a time. The script takes the first sentence of the paragraph as a headline, and encapsulates the paragraph as follows including spaces:

```
                        <li><b>HEADLINE</b><br>
                           TEXT TEXT TEXT. TEXT TEXT TEXT. TEXT TEXT TEXT.    
                        </li>
```

The output is presented as HTML using ```<pre></pre>``` tags.

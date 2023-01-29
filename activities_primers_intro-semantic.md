# Introduction to Semantic Markup (DRAFT)

Standard English vocabulary is crazy - one cup Anglo-Saxon, two cups Norman French, one cup Medieval Latin, and two cups Americana. For poets, punsters, advertising mavens, and politicians, it just doesn't get any better. English provides human beings with seemingly endless ways to stretch, obfuscate, or clarify the meaning of most any word or phrase. It's a delight.   

But what about non-human consumers of English -- chatbots, machine translation apps, smart device interpreters, and national security monitors? They are less adept than humans in providing context for words or phrases that have multiple meanings (semantics). Let's look at an example.  

In Boston (pronounced Bawstin), we cherish our regional vocabulary. Depending who was saying the following sentence or where they were saying it, we'd have little difficulty interpreting the meaning of the word "dunks".   

"Ronnie, I guess you'll be gettin' yoah **dunks** tonight."

Yes -- Ronnie could be:

* Getting ready for basketball
* Picking up a pair of Nike basketball sneakers
* Picking up some Dunkin Donuts coffee
* Doing a few a laps in the local pool

If we humans know Ronnie or have a larger sampling of the conversation, we can easily reconstruct the context for the sentence and narrow the semantic options for the word "dunks". A non-human interpreter could guess, but it would really need the sentence to give us some clues. Supplementing the sentence with a footnote would help . . . 

"Ronnie, I guess you'll be gettin' yoah dunks<sup>1</sup> tonight."

<sup>1</sup> Laps in the swimming pool.

But that becomes impractical quickly. Constraining the vocabulary or range of meanings as we see in Simplified Technical English (STE) is another option, but works exclusively in technical contexts. 

Yes - this has all been leading up to the concept of "semantic markup" and what role it might in the world of human-machine content development. 

First, let's clarify what we mean by "semantic markup" in an artifact. 

1. All markup must be universally readable by humans and software applications. Typically that means that the content is sourced in plain text.
2. That plain text contains easily identifiable tags or element markers. Typically this involves HTML-style element and attribute tags such as &lt;i&gt;.
3. The name of this tag or element must describe the meaning or function of its content unambiguously. The element &lt;i&gt; tells us *nothing* about its contents. A semantic element such as &lt;cite&gt; specifies that the content of the element reference the name of a publication.  
3. The content in the markup element can be rendered by processors to produce many different styles and formats. The element &lt;cite&gt; may often be rendered in italics, but processors should be able to render it most any way that is needed. 
4. As needed, element attributes can further refine the meaning or function of a semantic element. If the &lt;cite&gt; element were enhanced with a custom attribute named @isbn, a processor could render the publication title and its ISBN number when it encountered the markup &lt;cite isbn="445-3-16-238411-1"&gt;. 




To learn more about structured content development, see our [ACM Learning Guide]. 
 
## Further reading

* [HTML Semantic Elments, W3C](https://www.w3schools.com/html/html5_semantic_elements.asp)
* [Semantic Markup, Greg Baker, 2019](https://www2.cs.sfu.ca/CourseCentral/165/common/study-guide/content/html-semantic.html)
* [What is an HTML Semantic Tag and Why Do You Need To Use It?, Aryan Gupta, 2022](https://www.simplilearn.com/tutorials/html-tutorial/html-semantics)
* [What On Earth Is Semantic Markup?, Jon Penland](https://html.com/semantic-markup/)

       




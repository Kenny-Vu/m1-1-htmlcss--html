# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

 Answer: "a form of assistive technology ( AT ) that renders text and image content as speech or braille output." - wikipedia
 There is a need to make website accessible to people with disabilities, therefore websites should be written in a way that screenreaders can interpret.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
    Answer:  <img> tags.
b) You want to create a website that lists all the art gallery websites in your city and links to their website.
    Answer: <ul><li> and <a> tags.
c) You want to sell designer hats. You need to receive orders from the user.
    Answer: <form> and <input> tags.
## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
    Answer: You can certainly put a <button> tag inside of a parent button tag for sure. I am not sure why people would do that, but I guess one possible reason why people would do that would be to have a smaller clickeable button inside a larger clickeable button (after some css styling of course). 
## Q5 - What is the most generic tag you can use?
    Answer: <div>
## Q6 - What do the following achronyms stand for?

a) `a`
    'anchor'
b) `ol`
    'ordered list'
c) `ul`
    'unordered list'
d) `li`
    'list item'
e) `tr`
    'table row'
f) `th`
    'table header cell'
g) `td`
    'table data'
## Q7 - Usually, `td` elements are children of what kind of elements?
    <tr>
## Q8 - What is the difference between td and th?
    th is used as the header for the td in a table.
## Q9 - Which tag makes the text appear bigger: h1 or h3?
    h1
## Q10 - In which situation can you use self closing tags?
    When you are using elements that cannot have content such as <img> and <br>. It seems that they are known as "void elements" according to codecademy.
## Q11 - What is autofilling and why is it important?
    It's a feature that allows browsers to predict the input value of a user after typing a few characters. On w3schools, it's refered to as the "autocomplete attribute". I think it is important because it assists the user in completing forms faster. On the other hand, one might want to disable that feature for security reasons such as when making a payment for example.
## Q12 - Which attributes are always present in an img element?
    according to w3schools, it would be "src, alt, crossorigin, height, ismap, longdesc, referrerpolicy, sizes, srcset, usemap, width "
## Q13 - Which attribute is always present for an anchor tag?
    according to w3schools, it would be "download, href, hreflang, media, ping, referrerpolicy, rel, target, type"
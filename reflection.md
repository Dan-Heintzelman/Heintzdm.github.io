#3.5 Your Website, part 3 - A reflection

1.Link to my site:

Vist my site [here](http://heintzdm.github.io/)}

2.What did you learn about CSS padding, borders, and margin by doing this challenge?

For me, working on this website brought back memories of confusion about how to use percentages for element width on a web page. For instance, I wanted to have my sidebar be 20% width and my main content to be 80% width for a total of 100%. However, this does not work when you want to add in padding or margins. The reason is because that percentage width is specifying the percentage of space that the content will take up. (not including padding,border, margin). I used a neat trick called **box-sizing** to change the default from "content-box" to "border-box". This means that when I specify width (or height), I'm specifying the width of an elements content, padding, and border. I did this using the following code.

```
* {
  box-sizing: border-box;
}
```

3.What did you learn about CSS positioning?

I've learned that CSS positioning can be tricky. I understand how to use different positioning propterty/value pairs, and I've also learne how to use floats. However, I often run into an issue with I combine both positioning elements and floats into the same document. It sometimes feels like I have to stick to one or the other.

I know that if I float a section, and then the sibling adjadcent to it is not floated, it will want to colide with the floated element. It can be difficult to maintain flow of a document without being aware of the positioning "type" of adjacent elements.

4.What aspects of your design did you find easiest to implement? What was most difficult?

I think I covered the difficult part in #2. The most difficult part was getting my different sections (sidebar and main) to align properly. The second most difficult part was trying to get my buttons on the sidebar to work properly. The issue was I was trying to syle the li (list items) rather than the anchor elements.

The easiest part to implement was adding color to my document. Although I will say that I do not really like the color scheme I picked, I find that applying color in itself is not too difficult.

5.What did you learn about adding and formatting elements with CSS in this challenge?

I learned from this challenge how to use box-sizing, how to efficiently position elements on a page, and I also learned that adding comments to my CSS to organize my color pallete and sections can be very useful.


Hello, and welcome to this video where we're going to take a closer look at using text cells in a Jupyter notebook. 

I have a new Jupyter notebook here that has a cell in it, but notice it's a code cell which you can tell because of the play button. We don't write text in a code cell, so to enter a text cell I can click +Text here, or hover my cursor either at the top edge or the bottom edge of the existing cell and then click +Text. 

I'll add a text cell here on top of the code cell, then double click to edit. 

I can now start typing text into the area on the left. A preview shows up on the right. If all I want is unformatted text, that's all I need to do, but probably you'll want to change the way your text looks at times. 

There are two ways to do this.

First, there's a formatting menu at the top of the text cell that works more or less the way similar tools work in a word processor. If I want to make a word boldface, for example, I can highlight the word then click the B icon and it makes it bold. Or I can click the B and then type the word. 

You might notice that all this button does is place double asterisks around the word. This is because the formatting here is done in a language called Markdown. As mentioned in an earlier video, Markdown is a simple markup language, simlar to HTML and actually it's based on HTML. It's a commonly used language for documentation and comments on the web, and is simple to learn and use. As I demonstrate the rest of the menu options, I'll say what they do but also pay attention to the Markdown that's generated. 

Back to the menu, let's walk through the options. This button on the left inserts a header for document organization. We saw what bold does. This is for italics. This button inserts a non-executable code block, so if you want your readers to see some code but not evaluate it, you can put it in a text cell. This button inserts a link. This one inserts an image that you can upload from your computer. I don't recommend doing this however because as you can see, Jupyter uploads the photo but attaches a massively long extension to it that pretty much wipes out our view of the source text. So I'll show you that it works, and if you clicked out of the cell you wouldn't see all the clutter. But for this video, I'll take away that cute cat photo. 

This creates an indented block of text, which you can use to set off a piece of text you want to really emphasize. These two buttons create a numbered list, or a bullet list respectively. This inserts a horizontal divider. This button that looks like a trident or a fork... we'll come back to in a second. Finally you can put in an emoji from here, and finally this button lets you reposition the previewer to below the text if you want. 

Again notice that all of these buttons merely insert Markdown code into the  text cell. You can insert this manually, though, without clicking the menu. For example here's a bullet list with a phrase that involves bold, italics, and a link and here's the next item in the list. 

I highly encourage you to learn the basics of Markdown which you've just seen and type in text cells using Markdown. It's very simple to learn the basics and there are tons of tutorials out there to help. And you'll find this much faster than using the menu and it's a skill you can carry with you elsewhere. 

Now let's talk about mathematical notation. Specifically, let's typeset this equation. The implementation of text cells in Jupyter uses another markup language known as LaTeX. LaTeX has been around for decades and it is the standard platform for typesetting mathematics on the web. It's an extremely deep language with more capabilities than we will ever use here, but the basics are fairly straightforward. 

First, when typesetting math, you have to ask yourself if you want the expression inline -- in the same line as text that surrounds it -- or displayed, meaning off by itself and centered. To typeset an expression inline, create a single set of dollar signs. Inside those dollar signs, put the expression you want to typeset. Here I'm going to type x, then the caret symbol above the 6 on most keyboards, then 2, then plus y ^ 2 = z ^ 2. With that expression enclosed in single dollar signs, you can see the typeset result on the right. It looks like real math -- the exponents are really exponents and the variables are not just typed from the keyboard. 

If you want the expression to go into displayed mode, just enclose it in double dollar signs. 

Here's another example that shows how text and math can be combined: The derivative of y = sin x is t' = cos x. Notice the text it outside the dollar signs and the math is inside them. And notice I needed to put a slash before sin and cos, otherwise they would look like this. 

It might seem really intimidating to know that you have to know commands like ^ for exponents and putting a slash in front of sin, but Jupyter helps you out with tab completion. Let me start a new math expression here and let's suppose I want to write out an integral. Well, I might not know what the command to produce an integral is, but if I type slash inside the dollar signs and then type the letter "I", I'll get a menu of the latex commands that have "i" in them. The ones that start with i are at the top of the list, and I see one that produces and integral sign called int, so I can scroll to it, hit tab, and it puts a little integral sign in place. Then I can type the rest. 

Now that you know that \int is the command to produce an integral, you no longer have to use the tab complete. You can just type $\int$ directly. 

That brings us back to that fork-shaped icon in the menu. All this does is insert a slash so you can start searching for the latex command you want. And in fact just typing a slash in the text cell brings up that menu, so you can insert math symbols anywhere you want. 

Notice that it doesn't put the symbol into dollar signs but right into the text. So this button shouldn't be used for complicated expressions like this one -- you could use it for one-time symbols or very simple expressions though. 

There's much more you can learn about LaTeX, and I'd recommend playing with the tab completion and trying to replicate formulas you might see in a textbook to master the basics. 

So that's a deeper look at text cells. You can now use Jupyter notebooks as a rich and math-friendly platform for writing up mathematics-heavy documents. In the next video we'll look at the other kind of cell and see how to include executable code in the mix. 
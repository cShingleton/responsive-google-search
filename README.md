<h2>(26/03/17) Google Search Project Report:</h2> 

- - - -

UPDATE (19/04/17): I've put this on hold because the whole thing has become a big tangled mess
of divs and I wouldn't mind rebuilding it with some of the other technologies I've learnt. 

- - - -

This project is based on a project idea I found whilst running through the HTML/CSS part of 
an offering from the Odin Project's Web Dev 101 course where they asked students to code a static
version of a Google search and/or homepage. 
http://www.theodinproject.com/web-development-101

I took up this project partly because I wanted to feel like I had earned the right to progress but
also because it is structured in such a way that I don't have to focus on creating a design 
but rather replicating a static clone of something. Essentially, I can just focus on getting the 
HTML and CSS to work right. A small caveat though is that though they call for a static search
I wanted to try creating a more responsive version of the Google search with drop-downs at a mobile
resolution and all that. I did this as I noticed that resizing a Google search window on a desktop
does little more than simply add a horizontal scroll bar at smaller resolutions. So, my second 
project was an attempt to both accurately hardcode a Google search result (for 'ada lovelace') and
adapt the resulting search to be mobile responsive. 

<h3>Technique Thoughts</h3> 
I'll much more readily call this project successful in comparison to the tribute page but then 
I spent a lot more thoughtful time trying to figure this one out. I distinctly remember at least
one hour spent just rewrapping elements into different containers to try to get them to flex 
properly. Again, I didn't want to rely on Bootstrap or other frameworks so have hardcoded 
everything myself. 

Some notes:
- Flexbox. Is. A. Lifesaver. The initial learning curve was a little steep but compared to floats
they are heavenly. In particular I spent a good amount of time trying to get the sidebar to skip
to the right when resizing to a larger resolution only to discover that all it took was one property
in the form of 'order: 2;'!

- I am still a little unsure of what would have been the most efficient manner of wrapping the various
elements into containers in the header. What I have works but I am sure it could have been done better
than having to break up the content into three seemingly disparate containers of content. 

- Sadly I can't claim any ownership or originality over making the Google page 'image' into a table.
It was something I looked at when first dissected the project and had no idea on how to approach.
So, I decided to look at the Google source code for it and noticed table tags amongst all the goobledegook and lo and 
behold it worked beautifully. A really neat and intuitive trick that I shall definitely try to use in my
own future work. 

- Using a drop down seemed to be the most feasible way to rearrange the header on a resize.
Even so, drop down menus are something I have never done before so I refered to the excellent 
DevTips (video link) for help doing so. I'm pretty happy with the way it turned out. 

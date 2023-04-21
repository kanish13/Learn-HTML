Anchor Tag:

The a tag defines a hyperlink, which is used to link from one page to another.

The most important attribute of the a element is the href attribute, which indicates the link's destination.

By default, links will appear as follows in all browsers:

•	An unvisited link is underlined and blue

•	A visited link is underlined and purple

•	An active link is underlined and red

CHALLENGE:

To achieve:
![image](https://user-images.githubusercontent.com/111358462/233689838-9241915d-391a-4f83-80b2-32b601079446.png)
 
Code:

    <h1>My top 5 Favourite Websites</h1>

    <ol>
        <li><a href="https://www.producthunt.com/">Product Hunt</a></li>
        <li><a href="https://smashthewalls.com/">Smash the Walls</a></li>
        <li><a href="https://www.nytimes.com/games/wordle/index.html">Wordle</a></li>
        <li><a href="https://hackertyper.net/">Hacker Typer</a></li>
        <li><a href="https://stellarium.org/">Stellarium</a></li>
    </ol>

[ Extra info: 

•	Global attribute “drag” allow us to drag the elements 
  
Ex: 

    <a drag=true>Link<a>

•	You can change the initial numbering of ordered list using start attribute

Ex: 

      <ol start=”5”>
           <li>first</li>
           <li>Second</li>
           </ol>
          This list will start from 5 


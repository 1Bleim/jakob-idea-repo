# CSS Styling
To start, I once again reviewed the course material and exercises we did in class, and looked at the [w3schools](https://www.w3schools.com/css/default.asp) website for inspiration and instructions. Using that, I designed the basic layout of my website. There are three main elements I wanted to style: Headings, Body, and Main Content, which together make up the site’s overall styling. 

## Headings
Headings in HTML are wrapped by < h1>, so in order to style them in CSS, we add the desired elements in a section wrapped by h1 { … }. I started out by choosing my font size and color and made the text bold, uppercase, and centered. I also added a margin so there is some extra space above and below my headings. I then always kept a tab with my locally hosted website to refresh the page and check if everything looked nice. I adjusted the numbers for the font size and margins a bit until I was happy. 

## Body
The styling of the “body” will include everything that is wrapped by < body> in my HTML, so it essentially affects everything unless otherwise specified, like the h1’s. Here I just chose very basic stylistic choices, like the font type Arial, and a line height of 1,5 as I usually would with normal assignments. I then also added a background color, which I chose as a very muted tone of orange (for the trivial reason of it being my favourite color), and adjusted the font color to be a more muted gray tone, which is a bit nicer to look at.

## Main Content
Finally, I added a main content function, which again basically wraps all of my body. What this allows me to do, though, is create a second “layer” which I can use to style it separately. I wanted this area to be a bit narrower so it's closer to a “Word document format” where the text does not go across the entire screen, but it looks closer to text on a vertical page. So the first thing I did was limit the content area to a maximum width, which I centered horizontally and added a little padding so the text has a bit of space. Then I chose white as my background color and rounded off the corners of the content area with the border-radius function and added a little shadow for depth. 

These three elements together make up basically all the styling that can be seen on my website. The only other two aspects are the Buttons (which were explained in a section above) and the Dropdowns. 

## Dropdowns
Since I wanted to make the website a bit more fun, I wanted to display my content in a bit more interactive way. So what I had in mind were boxes with the headings that display the content below when clicked. Since I do not have the technical knowledge and capabilities to style something like this myself, I used ChatGPT and prompted it to explain to me how I can implement that alongside an example. This is how I came up with the following styling:
First, I had to make the “checkbox” that triggers the function in the HTML invisible, so you would only see the boxes with the headings. The next function makes it so the content of the dropdown is hidden by default, followed by the function that says to unfold the content when the“checkbox” is checked. Then it came to the styling of the actual dropdown labels, which I made blue like my headings, but with white text color for nicer readability. I also added some padding, a radius, and justification until I was happy with the final look. 

One last element I thought was fun to add is a little arrow that hints at the box being clickable. So I once again prompted ChatGPT to explain to me how to add that into the box. For that, I simply added a “▸” to the content, which rotates by 90 degrees when the checkbox is checked. 

Altogether, the headings, body, main content, the buttons, and the dropdowns make up my CSS styling for my website.

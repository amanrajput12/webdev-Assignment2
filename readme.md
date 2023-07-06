# Ans 1

Box model is a tool used to change the layout of the web
pages it includes the border , margin, padding and content in the web
pages by these property is used to add the creativity in the website.

# Ans 2

Different types of selectors in CSS are universal selector,
individual selector, class or id selector, chain selector, combine
selector etc . These selectors are used to target the Html elements to
all styling for the web pages

# Ans 3

VW/VH are view width and view height is the property of the
html attribute . It is relative property it depends upon the current
dimensions of the web pages while the pixel is the absolute property
which remain same for the all dimensions

# Ans 4

Inline elements are used to display the same line they
don’t start at the new line like` <h1>` eg `<span> <strong>` block
elements are started at the new line they reserve the full row and
every elements started from the new line eg `<h1> <p> <ul>` etc.
Inline block are those which started from the same line but get the
some property of block like margin , padding, height etc

# Ans 5

Border box and the Content box are the value of the box sizing
property in box border the padding and the border are included in the element’s total height and width while in the content box the padding
and border are not included in the element’s total height and width.

# Ans 6

It is the property in which the higher z index value is on the
top and the z index lower is on the lower side if we impose the
content in the image we have to give z index higher value than image
to content .

# Ans 7

Grid and Flex are two CSS layout systems that help in
designing and arranging elements on a web page.
Grid is used defined the both rows and columns align the content
using the fraction and flex is also used to align the content it have two
property display:flexRow and flexColumn

Eg :

 `<div class="nav-container">`
`<ul class="nav-menu">`

`<li>Home</li>`
`<li>About</li>`
`<li>Services</li>`
`<li>Contact</li>`
`</ul>`

`</div>`

`.nav-container {`

`display: flex;`

`justify-content: center;`
}

`.nav-menu {`

`display: flex;`

`list-style: none;`

`padding: 0;`
}

`.nav-menu li {`

`margin-right: 20px;`

}

`Eg : <div class="grid-container">`

`<div class="grid-item">Item 1</div>`

`<div class="grid-item">Item 2</div>`

`<div class="grid-item">Item 3</div>`

`</div>`

`.grid-container {`

`display: grid;`

`grid-template-columns: 1fr 1fr 1fr;`

`gap: 10px;`
}

`.grid-item {`

`background-color: #f2f2f2;`

`padding: 20px;`
}

# Ans 8

Positioned relative to its nearest positioned ancestor, or the
viewport if there is no positioned ancestor. Positioned relative to its
original position on the page. Position stick means the container move
with the scroll and In Fixed position is fixed at one point

Eg: 

`<div class="absolute">This is an absolutely positioned element.</div>`

`<div class="relative">This is a relatively positioned element.</div>`

`<div class="sticky">This is a sticky element.</div>`

`<div class="fixed">This is a fixed element.</div>`

`.absolute {`

`position: absolute;`

`top: 10px;`

`left: 10px;`

}

`.relative {`

`position: relative;`

`top: 10px;`

`left: 10px`;

}

`.sticky {`

`position: sticky;`

`top: 0;`

}

`.fixed {`

`position: fixed;`

`top: 0;`

`left: 0;`

}
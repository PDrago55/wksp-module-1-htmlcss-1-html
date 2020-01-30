# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [False] `<div><span>hello</div></span>`

<div><span>hello</span></div>
b) [False]

```html
<ol>
    <li>one</li>
</ol>
```
<!DOCTYPE html>
<html>
<ul>
    <li><one>/li>
</ol>



c) [False] `
<ul>
<img src="__.png"/>
<ol>
<li>one</li>
</ol>`
</ul>

## Q2 - What is a screenreader and why should we care about them?

In its simplest explanation, screenreaders help people who suffer from disabilities navigate a webpage. The use of particular applications that name icons when hovered with the mouse increases accesability for some users. A screenreader is important because it allows for people who have disabilities, the option to use the internet. 
Watson, Leonnie (2005). What is a Screen Reader? https://www.nomensa.com/blog/2005/what-screen-reader


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<!DOCTYPE html>
<html>
<head></head>
<body> 
<h1> My Vacation Pictures </h1>
<img src="theimage.png"/>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

''' html
<!DOCTYPE html>
<html>
<head></head>
<body> 
    <h1>
<p>please look at this cool art my guy</p>
    <p><a href="https://www.mbam.qc.ca/en/" target="_blank"> Fine Arts Museum Montreal</a> </p>
    <p><a href="https://macm.org/en/" target="_blank"> Museum of Contemporary Art</a> </p>>
</body>
<html>

c) You want to sell designer hats. You need to receive orders from the user.
I would create a small form found below! 

<!DOCTYPE html>
<html>
<head></head>
<body> 
<h1>Hat Order</h1>
<form>
<label> Full Name <input type="text" required>
</label>
<label> Address <input type="text" required>
</label>
<div> 
<label> Hat <input type="radio" required> <div> Hat 1
<label> Hat <input type="radio" required> <div> Hat 2
<label> Hat <input type="radio" required> <div> Hat 3
</label>
</body>
<html>

## Q4 - Can a button be a child of a button? Explain your reasoning

It cannot because there can only be a one clickable element in one button also, you can only place texts within a button.


## Q5 - What is the most generic tag you can use?

<div>

## Q6 - What do the following achronyms stand for?

a) `a` html starting link "at" 

b) `ol` ordered list

c) `ul` unordered list

d) `li`list item

e) `tr` defines a row

f) `th`defines a header cell

g) `td` defines a standard/column cell


## Q7 - Usually, `td` elements are children of what kind of elements?

<tr/> elements

## Q8 - What is the difference between td and th?

th defines headers in a table
td defines standard cells

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1 because it is the header

## Q10 - In which situation can you use self closing tags?

When you do not place any children within the tags. 

## Q11 - What is autofilling and why is it important?

Autofilling is the function of adding in texts into a program automatically. It is important because it saves on time. 
Tom, New (2019) The Pros and Cons of Autofill in Webforms. 
https://www.formisimo.com/blog/the-pros-and-cons-of-autofill-in-webforms/

## Q12 - Which attributes are always present in an img element?

<img src=".png/.jpeg"/>

## Q13 - Which attribute is always present for an anchor tag?

html links
<a href= "https://en.ryte.com/wiki/Anchor_Tag">

Source:https://en.ryte.com/wiki/Anchor_Tag


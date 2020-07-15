# Why Email Matters ?

* 3.9 billions users in 2019. 
<br>

* 2.5 hours per weekend spent in email.
<br>

* **Easy is easy to send** and relatively affordable.
<br>

* **Tracking email is simple** 
<br>

* **Testing email is quick** and make iterating easy.
<br>

* **Emai is forgettable**
<br>
<br>


# Email-Friendly-HTML

`Html we actually gonna be using for email compaigns.`
<br>

* Basic, non-structural containers : **div** , **span**
<br>

* Heading : **h1** - **h6**
<br>

* Other Text : **p**, **strong**, **em**
<br>

* Images : **img**
<br>
<br>

# Email-Friendly-CSS 

## For Text:
* **color**, **font-family**, **font-style**, **font-size**, **font-weight**, **line-height**, **text-align**
<br>

## For block level element:
* **margin**, **padding**, **width**, **max-width**
<br>

## For outlook styling :
```css
<center> To center the elements. </center>
```
<br>


# Links & Buttons 


## Some Guidlines :

* Use descriptive links.
<br>
* Embrace link conventions.
<br>
* Dont Use images for buttons.
<br>

# Images in Email

* Make image responsive by default!
<br>
* Use alternative text.
<br>

* Stick to the standbys: **jpg**, **png**, **gif**
<br>

# Responsive Images

* Set afixed width as an HTML attributes for outlook<br>
Use max-width:100%; min-width:X;
width:100%; to make them adjust across screen sizes.
<br>

# Background  images in Email

* Most reliable on table cells (td).
<br>

* Use both **HTML Attribute** & **inline CSS**
<br>

# Accessible Design 

## Some guidlines:

* Keep color contrast heigh.
<br>

* Creat a stron visual hierarchy.
<br>

* Focus on readability.
<br>

* Keep layout simple and Useable.
<br>
<br>

# Accessible Develpment

* Keep table quite using **role = "presentation"**.
<br>
<br>
* Use semantic markup to reinforce hierarchy.
<br>
<br>
* Include text alternatives foe img.
<br>
<br>

* include lang for an email.
<br>

# Using Tables in Email

*  Keep table quite using **role = "presentation"**.
<br>
<br>

* Ignore table headers, body, footer.
<br>
<br>

*  Keep components in their own rows/tables.
<br>
<br>

* Overwrite defaults using HTML attributes.
<br><br>

* Place most style son table Sets.
<br>

# **Boilerplate Table**
```html
<table border = "0 cellpadding ="0 cellspacing="0" role="presentaion" width = "100%">
    <tr>
        <td style = "styles go here">
        </td>
    </tr>
</table>
```
<br>

# Single Column Layout

### Basic structure is :

* **Fluid Table** : 100% wide.
<br>
<br>

* **Fixed Table** : fixed table inside of a table cell within  container table.

* **Content** : own district table row and table cells within the fixed width container.
<br>

# Mltiple column Layouts

### Basic structure is :

* **Fluid Table***
* **Fixed Table***
* **Fluid Table**
* **Fixed Table**
<br>

# Mobile-Aware Design

* Simple Layout
<br>

* Large Text
<br>

* Lrage Buttons
<br>

* Design scales down
<br>

# Hybrid/Spongy Coding

* For when you need to get non-traditional <br>

    1 . Fluid  by default.
    
    2 . **max-width**
    <br>

    3 . MSO ghost table
<br>

# MSO Ghost table 

* **A handy way to target Microsoft Office**
<br>
```HTML
<!-- [if (gte mso 9) | (IE)]>
<! [endif-->
```

<br>

#  **MSO TARGETING**
```
 Outllok 2000 : Version 9        gte = Greater than equal to

 Outllok 2002 : Version 10       gt = Greater than

 Outllok 2003 : Version 11       lte = less than equal to

 Outllok 2007 : Version 12       lt = less tha

 Outllok 2010 : Version 14
 
 Outllok 2013 : Version 15
```
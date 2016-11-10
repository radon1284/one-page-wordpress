# WordPress: Building a One-Page Style Site

Code Snippets

## Chapter 2: Creating a Foundation for the Front Page
  * 2.5 - Setting Up Styles for the Front Page
  
## Chapter 3: Adding Components from Different Pages

  * 3.2 - Using Custom Queries to Display Content from Different Pages
  * 3.3 - Using a Custom Loop to Retrieve Services Page Children
  * 3.4 - Styling New Content with CSS
## Chapter 4: Adding Testimonials

  * 4.3 - Creating a Custom Testimonials Loop
  * 4.4 - Styling the Testimonials Section
  * 4.5 - Excluding Testimonials from Index Pages
  
## Chapter 5: Creating the Scrolling Effect
  * 5.1 - Adding a Custom Menu to the Front Page
  * 5.3 - Sticking the Menu to the Top of the Page
  * 5.4 - Adding Smooth Scroll for the Scrolling Effect

# Chapter 2: Creating a Foundation for the Front Page

**2.5 - Setting Up Styles for the Front Page**

```css
/* CONTENT AREA */
.content-area {
	background: #fff;
	background: hsl(0, 0%, 100%);
}
				
/*CALL TO ACTION*/ 
#call-to-action {
    color: #fff;
    color: hsl(0, 0%, 100%);
    background: #8abf5e;
	background: hsl(93, 43%, 56%);
    padding: 4rem 0;
}

/* TESTIMONIALS */
#testimonials {
    padding: 4rem 0;
    background: hsl(0, 0%, 90%);
}

/* SERVICES */
#services {
    padding: 4rem 0;
}

/* MEET THE DOCTOR */ 
#meet {
    padding-top: 4rem;
    padding-bottom: 6rem;
	color: #fff;
    color: hsl(0, 0%, 100%);
	background: #00497A;
    background: hsl(204, 100%, 24%);
}

/* CONTACT */
#contact {
    padding: 4rem 0;
}
```
**In lander-style.css:**

```css
@media screen and (max-width: 1539px) and (min-width: 1160px){ 
    .content-area.lander-page {
         margin-left: 0; 
        padding-left: 0; 
    }
}

.indent {
    max-width: 1000px;
    margin: 0 auto;
}


@media screen and (max-width: 1099px) {
    .indent {
        margin: 0;
        padding: 0 4rem;
    }
}

@media screen and (max-width: 320px) {
    .indent {
        margin: 0 2rem;
    }
}
```

# HTML Links, JS Functions, and Intro to CSS Layout

## 1.Link Element

        in this part we will discuss the following points

- There are 4 ways for dealing with Links in HTML we will list them.

<br/>

                           The beginning of Part One 

### 1.1 : Linking to Other Sites

we use :
                                
```html
    <ol>
    <a href="http://www.Jehadabuawwad.coffeecup.com">Empire</a>
    </ol>
```

### 1.2 : Email Links

we use :
                                
```html
    <ol>
    <a href="mailto:jehadabuawwad@outlook.org">Email Jon</a>
    </ol>
```

### 1.3 : Opening Article Links in a New Window

we use :
                                
```html
    <ol>
    <a href="http://www.Jehadabuawwad.coffeecup.com" target="_blank">
    </ol>
```


### 1.4 : Linking to a Specific Part of the Same Page

we use :
                                
```html
    <ol>
    <a href="#arc_shot">Arc Shot</a><br />
    <p>A shot in which the subject is photographed by an encircling or moving camera</p>
    </ol>
```

                           The End of Part One


## 2.Layout

        in this part we will discuss the following points

- How CSS and HTML treats with elements when it displays it. 
- How we contain elements inside others.
- How the browsers display each element.
- How do we floating elements.
- How we can deal with Screen Sizes.
- What are the Grids.

<br/>

                           The beginning of Part Tow 

### 2.1 : CSS and HTML treats with elements when it displays it as the following:

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

### 2.2 : We contain elements inside others as the following:

- If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

- div elements are often used as containing elements
to group together sections of a page.

### 2.3 : The browsers display each elementas as the following:

- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
    - Relative: Relative positioning moves an element in relation to where it would have been in normal flow.
    - Absolute:When the position property is given a value of absolute , the box is taken out of normal flow and no longer affects the position of other elements on the page.
    - Fixed:Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed .

### 2.4 : We float elements as the following:

- The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)

### 2.5 : We can deal with Screen Sizesas the following:

- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide,and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

### 2.6 : What the Grids are.
- Grids set consistent proportions and spaces between items which helps to create a professional looking design.

- Grids help create professional and flexible designs.


                           The End of Part Tow

## 3.Layout
        in this part we will discuss the following points

-What are the functions.
-How we can declare a function.
-How we can call a function and if we want to call it immediately how?
- What is the variable Scope and what are the type of it.


                           The beginning of Part Three 

### 3.1 : The Functions are:


- Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than rep eating the same set of st atements)

- Functions allow you to group a set of related statements together that represent a single task.

- Functions can take parameters (informatiorJ required
to do their job) and may return a value.

### 3.2 : We declare a function as the following:

![Declaring a Function](https://jehadabuawwad.github.io/reading-notes/images/class-04-photos/1.png)

### 3.3 : We can call a function as the following:
![Calling a Function](https://jehadabuawwad.github.io/reading-notes/images/class-04-photos/2.png)

- This is how we call it immediately:
```javascript

    var area = (function(){
    var width = 3;
    var height = 2 ;
    return width * height;
    }()) ;
```

### 3.4 : The Variable scope is:

- The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope.

- type of variable scope is:
    - Local variable : When a variable is created inside a function using the var keyword, it can only be used in that function. It is called a local variable or function-level variable.
    - Global variable : If you create a variable outside of a function, then it can be used anywhere within the script. It is called a global variable and has global scope.




                           The End of Part Three



## 3. Six Reasons for Pair Programming:
                
                           The beginning of Part Four 
                            
    1.Greater efficiency
    2.Engaged collaboration
    3.Learning from fellow students
    4.Social skills
    5.Job interview readiness
    6.Work environment readiness 

                            The End of Part Four
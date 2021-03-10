## Web designining using ReactJs
* HTML
    * version - DOCTYPE
    * head
        * title
        * link (favicon,css)
        * meta
        * script
    * body
        * Block-level elements
            * Heading Elements
            * Paragraph
            * List (ol, ul, dl, li)
            * Division
            * Table,tr,caption
            * form
            * option
            * Semantic elements ( *Having a specific meaning for the element* `Semantic Elements = Division (div) + Special meaning`)
                * Header
                * Footer
                * Main
                * Nav
                * Section
                * Article
                * Aside
        * Inline Elements
            * td (`rowspan` => *Merging Rows*, `colspan` => *Merging Columns*)
            * form-controls (input, select, textarea)
            * Styling elements (em(i),strong(b),(u),sup,sub)
            * span
            * Image
            * Navigation
                * In-bound  ( *Navigating with in the document* )
                * Out-bound ( *Navigating between the documents* )
                * Mailto    ( *Specifying E-mails's* )
                * Tel       ( *Specifying mobile numbers* )
* CSS
    * what is CSS ?
    * Syntax
    * Kinds of CSS
        * Inline
        * Internal &
        * External
    * Selectors
        * Basic selectors (`#,.,<tag_name>,*`)

```css
            /* Element selector */
            body{
                background: red;
            }

            /* Id selector */
            #header{
                background: #ddd;
            }

            /* Class selector */
            .github{
                color: #000;
                text-decoration: none;
                background: blue;
            }

            /* Universal selector */
            *{
                font-family: Helvetica;
            }
```

* Bootstrap
* JavaScript
    * History
        * Inventor- **Brendon Eich** ( `1995` )
        * ECMA ( `Europian Computer Manifactur Association` ) - `ES-268`
        * Latest Version is (`ES-11` (Jnne-2020))
        * ES-6 is mandatory for advanced concepts of JS
    * Datatypes
        * Number
        * String
        * Boolean
        * Object
        * Undefined
        * Notdefined
        * Function
    * Output statements
        * Console statements
            * Log
            * Warn
            * Error
            * Info
            * Assert
            * Count
            * Clear
        * Popups
            * Alert

```javascript
                alert('Sample alert')
```

            * Prompt (String kind)

```javascript
                prompt('Enter the value for number1')
```

            * Confirm

```javascript
                confirm('Enter the value for number1')
```

    * Conversion Statements
        * Number, parseInt(), parseFloat()
        * toString, string
        * Boolean (true => 1, false => 0 ) : Result will be a number
        * Null (0) ' ' (0)
        * undefined : (NaN for all formats except string)
        
   * Arrays and its methods
        * Find()
        * Slice()
        * Filter()
        * Includes()
        * Pop()
        * Push()
        * Splice()
        * Sort()
        * Shift(),unshift()
        * toString()
        * indexOf()
        
   * Iteration statements
        * For
        * While
        * Do-while
        * for-in
        * for-of
        * map
        
   * Functions
        * Static
        * Functions with parameters
        * Anonymous functions

```javascript
        var sub=function(a,b){
            return a-b;
        }
```

   * Arraow functions

```javascript
            var division=(x,y)=>{
                return x/y
            }

```

   * Higher-order functions
   
        * A function which accepts another function as an argument.
                * Map()

```javascript
                    array.map(function(i,index){
                        console.log(i+" is having the index: "+index)
                    })
                    // i is for the elements && index is for the popsitions
```

   * Filter()
   * setTimeOut()

```javascript
                setTimeout(()=>{
                    console.log("Hellow everyone")
                },3000)
                // 1st argument is a function && 2nd argument is the timing delay
```

   * Template literals
   
        * We can concatinate the number of strings together very easily.

```javascript
                var name="Hanuman";
                var role="Trainer";
                console.log(`${name} is working as a ${role}`)

                // Hanuman is working as a Trainer
```

   * Destructuring
   
        * We can define multiple variables at once.
        * Can assign multiple values extracting from an array to different variables.
        * Object destructuring
    
```javascript
                let options={
                        title:"Menu",
                        width:100,
                        height: 50
                }
                let{title,width,height}=options;
```


   * Rest && Spread (`...`)
   
        * Rest is for assigning rest of the elements from an array
        * Spread is for apreading the elements in the array.


* ReactJs &
* Redux

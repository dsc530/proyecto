# Project 0

Web Programming with Python and JavaScript
My Project is called NBA LATINA, where I want to give information about the league in Spanish.
I have 4 web pages:
    1. Index.html:
        - head includes the bootstrap link to use its qualities
        - head includes a link for de CSS desing file
        - head also has an image which has a bootstrap component
        = body has a table for the menu to link with other pages
        - table has 3 headers with de page name
        - each table header has a class named titulo for the style sheet
        - after the table there is a grid model from the bootstrao layout
        - the first div has "container" as the name for the class to use the grid
        - inside there is another div (class white) which is a spache between the menu and the information
        - the rest of divs have the "row" class 
        = The grid layout has two columns on each row with a column bigger than the other
        - The bigger column has a imagen inise while the smallest one has text
        - The grid is responsive to the small windwos
        - When the window is samaller the two colums merge in only one
        - Some images have a link to internet web pages

    2. desings.scss
        - Give a value for the variables "fondo" "letra" and "color"
        - Use of inheritance to have the same desing for the text
        - Use of nesting property to give "table"-class "titulo" and "a" its attributes 
        - Media query to print the web page without the menu (table)
        - Use of @extend to give "titulo" the text style
        - Use of hover to give the "menu" a different style when the mouse is over it
        - rows and divs from the grid have nested style properties 
        - the columns use the "flex-wrap reverse" to put always an image after the text
    
    3. Franquicias
        - Same head as index
        - Same Menu as Index
        - Media query to make bigger the size of "map" image when the window is smaller than 699px
        - Use of a list inside a two column table
        - Use of bootstrap grid
    4. franquicias_desing.scss
        - same inheritance as desing.scss
        - inheritance called imagenes to center images
        - same variables as desing.scss
        - different styles for h1, h3, p and class "mapa" (image)
        -nesting to assign different styles to table elements including the lists
    
    5. Noticias
        - Same head as index
        - Same Menu as Index
        - Bootstrap Media Objects to align an image with a title and a paragraph
        - Media Query for not displaying the paragraph when the window is smaller than 900px

    6. noticias_desing.scss
        - same inheritance as desing.scss
        - same variables and nesting as desing.scss
        - Class .mr-3 has a specific width of 30% for the images
        - Class parrafo justifies the text with the news

    7. Jugadores
        - Same head and Menu as Index
        - Bootstrap grid to have a responsive layout with 2 or 1 columns
        
    8. jugadores.scss
        - same inheritance as desing.scss
        - same variables and nesting as desing.scss
        - same table properties as desing.scss
        - special style for h1 (aling center), class subtitulo (extends letras style)
        - special style for class texto (text aling justify)
        - special style for id segundo (wrap reverse)  
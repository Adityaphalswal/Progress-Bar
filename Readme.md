# Notes of this projects/Topics use in this projects/Topics I learn

## :root pseudo class :-
- The :root selector matches the document's root element.
- It can be useful for declaring global CSS variables.

## CSS Content Property :-
- The content property is used with the ::before and ::after pseudo-elements, to insert generated content.

    ### Default value : normal

    ### Property Values
    | Values |
    |--------|
    normal
    none
    image-set
    linear-gradient
    counter
    attr(attribute)
    string
    open-quote
    close-quote
    no-open-quote
    no-close-quote
    url(url)

## Z-index Property :-
- The z-index property specifies the stack order of an element.
### Default value : auto


## CSS Outline :-
- An outline is a line drawn outside the element's border.

    ### css outline style
    | Values |
    |--------|
    dotted
    dashed
    solid
    double
    groove
    ridge
    inset
    outset
    none
    hiddnen

## EventListener( ) Method :-
- This method attaches an event handler to the specified element.
- Syntax `element.addEventListener(event, function, useCapture)`
- For browsers that don't support the addEventListener() method, you can use the attachEvent() method.
- Using the removeEventListener() method to remove an event handler that has been attached with the addEventListener() method.

    ### Event Bubbling or Event Capturing?
    - Event propagation is a way of defining the element order when an event occurs.
    - In bubbling the inner most element's event is handled first and then the outer. 
    - In capturing the outer most element's event is handled first and then the inner.
    - With the addEventListener() method you can specify the propagation type by using the "useCapture" parameter:
    - The default value is false, which will use the bubbling propagation, when the value is set to true, the event uses the capturing propagation.

## .Style

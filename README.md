  #Goal: characteristics and behavior of the float property
  
<!--   Note: 
    1. The float property creates a new behavior where the element is now floating on the screen, 
    then consequently leaves its previous space vague to be occupied by another element.
    2. One of the behaviors of float is, it never hides content even when hiding the element.
    3. The "overflow: hidden" property forces a recalculation of the context, that is, it checks if there is someone floating inside this element.
        a) The idea here is to hide any element that leaks a width and height to that parent element. When we recalculate the parent element (article) it
           will consider the calculation taking into account the floating elements.
        b) A good example of this behavior would be; when we need to put a background color on an element and we also need to consider
           the elements floating on the screen.
        c) The parent that is enclosing the floating element has lost its width and height, but we can recover these values ​​by setting 'overflow: hidden' in the parent.
    4. Does the "Clear" property check if there are any elements floating on the right or left? If you have it, it clears the context of the float
    allowing the object to be relocated elsewhere in the browser.
    And if the element does not fit on the screen, it will fall to the next line following the orientation of the property we choose left or right. -->

  Link: >> 
  
  

  

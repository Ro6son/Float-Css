  #Goal: characteristics and behavior of the float property
  
  Note: <br>
    1. The float property creates a new behavior where the element is now floating on the screen, 
    then consequently leaves its previous space vague to be occupied by another element.<br>
    2. One of the behaviors of float is, it never hides content even when hiding the element.<br>
    3. The "overflow: hidden" property forces a recalculation of the context, that is, it checks if there is someone floating inside this element.<br>
        a) The idea here is to hide any element that leaks a width and height to that parent element. When we recalculate the parent element (article) it
           will consider the calculation taking into account the floating elements.<br>
        b) A good example of this behavior would be; when we need to put a background color on an element and we also need to consider
           the elements floating on the screen.<br>
        c) The parent that is enclosing the floating element has lost its width and height, but we can recover these values ​​by setting 'overflow: hidden' in the parent.<br>
    4. Does the "Clear" property check if there are any elements floating on the right or left? If you have it, it clears the context of the float
    allowing the object to be relocated elsewhere in the browser.<br>
    And if the element does not fit on the screen, it will fall to the next line following the orientation of the property we choose left or right.<br>

  Link: >> 
  
  

  

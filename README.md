# JS
J$, a bilingual helper library (English/Español)

Biblioteca con los siguientes -- Library with the following:
_____________________________________________________________

// Juntar html a un elemento -- Append html to element
J$.juntar(elementos, html)
J$.append(elements, html)

// Escoger colección de elementos por #identificacion, .clase, o tag  -- Select element(s) by #id, .class, or tag
J$.escoger(selector)
J$.choose(selector)

// Juntar cada parte de un json a un(os) elemento(s)  -- Display all of the elements of a json object, appending to elements
J$.desplegar(elementos, json)
J$.display(elements, json)

// Pone el html enfrente de lo que hay en los elementos -- Prepend html to element
J$.prefijar(elementos, html)
J$.prepend(elements, html)



_____________________________________________________________
Example:
// Both lines are equivalent, displaying lm object as text on element with id of main.
J$.display(J$.choose('#main'),lm);
J$.desplegar(J$.escoger('#main'),lm);

# Shopping List Project

A simple shopping list project from the Traversy Media Modern JavaScript Course

## Specs

1. Add items to list via form
2. Remove items from list by clicking 'X' button
3. Clear all items with 'clear' button
4. Filter the items by typing in the filter field
5. Add localStorage to persist items
6. Click on an item to put into 'edit mode' and add to form
7. Update item
8. Deploy to Netlify

## Notes on localStore/sessionStorage

-Property on the 'Window' interface thatt allows us to access a Storage object
-Data is stored in the browswer
-Data is stored as key/value pairs and values are strings (Cannot store objects)

localStorage and sessionStorage have the same API. The difference is that localStorage does not expire, while sessionStorage only lasts until page is close.

### localStorage Methods

-localStorage.setItem('name', 'Brad') --Set a value with a key
-localStorage.getItem('name') --Get a value using the key
-localStorage.removeItem('name') --Remove item using the key
-localStorage.clear() --Clear all values

### DevTools with localStorage

We can go the 'Application' tab within DevTools and look at our local storage. We can use the localStorage.setItem() to add to this section.

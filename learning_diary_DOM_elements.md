Task 1:
-"document" is a automatically provided object that represents the web page currently loaded in the browser.
- The browser turns the HTML into a tree of objects called the DOM (Document Object Model). You need "document" to access this tree, so you can read and change it.
- It only exists in the browser (not in node.js)
- with document you can find elements, read and change content, change attributes, change styles and css classes, create new elements, react to events, read and change pages and read from input.

Task 2:
- The list in index.html has the id myList, so you can get it with document.getElementById("myList") or document.querySelector("#myList").
- You can get the items inside it with myList.querySelectorAll("li").
console.log(myList) shows it in the browser console (F12), so you can check that it worked.
- The script is at the end of <body>, so the list already exists when the script runs.

Task 3:
- The div has mostly the same properties as the list, because every HTML element has them (e.g. `id`, `tagName`, `textContent`, `style`).
- A div is a block element, so `offsetWidth` is the full page width.
- Some properties can be read and changed (e.g. `id`, `textContent`, `style`), others can only be read (e.g. `tagName`, `offsetWidth`).
- The size properties (`offsetWidth`, `offsetHeight` …) are calculated by the browser, so I can only read them.
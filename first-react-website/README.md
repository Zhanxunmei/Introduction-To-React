# Getting Started with Create React App
2. List five significant features of React; a-Virtual DOM; b-Extensions; c- Debugging; d- JSX[JavaScript Syntax Extension]; e- Performance.

3. List five major advantages of React. a. Development of both web and mobile apps  b. React is easy to learn c. Improved performance d. Reusable components e. Easy creation of dynamic applications.

4. What is the name of the Software Engineer that created React? Also, which company owns React? Jordan Walke is the software Engineer that created React. React is owned by Meta (Formerly Facebook).

5. What are the notable differences between HTML & JSX? Give at least 3 of them.
A- Tags can self-close in JSX. That is, it is possible to have (

as
and as ). You don't want to do that, but it’s possible. Self-closing tags in HTML can self-close without the slash before the right angle bracket, that is
could work as
. But in JSX, you need to include the slash. This should bring something to mind – JSX heavily relies on HTML 4 syntax.

B- In JSX, it is possible to write JavaScript directly. You can do this by putting the JavaScript in curly braces {...}. Whereas in HTML, you need a script tag or an external JavaScript file to implement JavaScript.

C- The major differences between HTML and JSX is that in JSX, you must return a single parent element, or it won't compile.


6. Why can’t browsers read JSX? Because JSX is not a valid JavaScript, browsers can't read it directly; they do not know what to do with it, so we need a transpiler to translate it to React.




EXERCISE 2 
### Q1 – Research on internet and list down the main differences between HTML and JSX syntax:
### Differences between HTML and JSX

- **HTML** is a markup language interpreted directly by the browser, while **JSX** is a JavaScript syntax extension mainly used in React.
- **JSX** allows JavaScript expressions inside the markup using {}, whereas **HTML** does not.
- **Attribute naming differs**: HTML uses class and for, while JSX uses className and htmlFor.

EXERCISE 3

## Q1 – Component Diagram from React JS Code

+-------------+
| index.html |
+-------------+
|
v
+-------------+
| main.jsx |
+-------------+
|
v
+-------------+
| App.jsx |
+-------------+
| | |
v v v
+---------+ +---------+ +---------+
| Header | | Main | | Time |
| .jsx | | .jsx | | .jsx |
+---------+ +---------+ +---------+

### Description
- index.html is the root HTML file.
- main.jsx renders the React app.
- App.jsx is the main (parent) component.
- Header.jsx, Main.jsx, and Time.jsx are child components.

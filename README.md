EXERCISE 2 
Q1 – Research on internet and list down the main differences between HTML and JSX syntax:
### Differences between HTML and JSX

- **HTML** is a markup language interpreted directly by the browser, while **JSX** is a JavaScript syntax extension mainly used in React.
- **JSX** allows JavaScript expressions inside the markup using {}, whereas **HTML** does not.
- **Attribute naming differs**: HTML uses class and for, while JSX uses className and htmlFor.

EXERCISE 3
## Q1 – Component Diagram from React JS Code

### Step 1: Read the Code
- Analyze the given React JS source code carefully.
- Identify files and functions that return JSX.

### Step 2: Identify Components
- Determine the **main (parent) component** (e.g. `App`).
- Identify **child components** imported or used inside the parent.
- Note the relationship between components (parent → child).

### Step 3: Draw the Component Diagram
- Represent each component as a box.
- Use arrows to show parent–child relationships.
- The diagram can be drawn using **PowerPoint**, **Draw.io**, or similar tools.

### Example Component Diagram (Conceptual)

App  
│  
├── Header  
├── Main  
│   ├── ProductList  
│   │   └── ProductItem  
│   └── Cart  
└── Footer

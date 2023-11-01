# folder-to-tree-string

# Usage
```TypeScript
import folderStringToTreeString from "derectoryFormat.ts"
```
This function formats a string of a specific format into a tree-structured string.  
**Indent is two spaces or a tab space.**  
e.g.  
Before
```
/
  build
  src
    style
      index.css
    page
      home.html
      login.html
    index.html
  others
```
After
```
/  
├─ build  
├─ src  
│  ├─ style  
│  │  └─ index.css  
│  ├─ page  
│  │  ├─ home.html  
│  │  └─ login.html  
│  └─ index.html  
└─ others  
```

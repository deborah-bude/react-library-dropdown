# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Installation
`npm i react-library-dropdown`
or
`npm install react-library-dropdown`

Actual version : `1.4.3`

NPM version : 9.8.1

React version : 18.2.0

Made with VS Code.

# Web site
[https://github.com/deborah-bude/react-library-dropdown](https://github.com/deborah-bude/react-library-dropdown)

# Usage
## Import in JSX file:
`import { Dropdown } from "react-library-dropdown"`

## How use ?
Options parameters

**Options required**
``` js
const options = [
    {
        "name" : "Item content 1"
        "abbreviation" : "IC1"
    }, 
    {
        "name" : "Item content 2"
        "abbreviation" : "IC2"
    }, 
    {
        "name" : "Item content 3"
        "abbreviation" : "IC3"
    }, ]
    
const title = "My dropdown menu"

return <Dropdown title={title} options={options}></Dropdown>

```

**Search option**

Default value : `false`
``` js
return <Dropdown title={title} options={options} serach={true}></Dropdown>
```
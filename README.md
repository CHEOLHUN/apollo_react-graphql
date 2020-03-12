# Apollo 2020

Movie App built with React, Apollo and GraphQL

> Preferences

-   install

```bash
yarn add styled-components

yarn add react-router-dom

yarn add apollo-boost @apollo/react-hooks graphql
```

-   react.css
-   router

```javascript
import React from "react";
import { HashRouter as Router, Route } from "react-router-dom";
import Home from "../routes/Home";
import Detail from "../routes/Detail";

function App() {
    return (
        <Router>
            <Route exact path='/' component={Home} />
            <Route exact path='/:id' component={Detail} />
        </Router>
    );
}

export default App;
```

> Apollo

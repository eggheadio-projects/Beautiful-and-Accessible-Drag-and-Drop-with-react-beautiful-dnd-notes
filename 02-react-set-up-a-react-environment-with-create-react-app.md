## [Lesson 2](https://egghead.io/lessons/react-set-up-a-react-environment-with-create-react-app)

Went though this lesson and everything worked just fine. 

Ran `create-react-app task-app` to create a simple react application and named our folder `task-app`. Reduced the `index.js` file. 

```js
import React from 'react';
import ReactDOM from 'react-dom';

const App = () => 'Hello World'

ReactDOM.render(<App />, document.getElementById('root'));
```

We also deleted every other file in the `src` folder except for our index.js file. 

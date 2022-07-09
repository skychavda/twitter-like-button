# Twitter Like Button ❤️

### Demo
![demo-counter](./heart.gif)

[Code Sandbox link](https://codesandbox.io/s/twitter-like-button-nj9hn6?file=/src/App.js)

### Installation
``` 
npm i twitter-like-button

or 

yarn add twitter-like-button
```

### Usage
```import TwitterLikeButton from 'twitter-like-button'```

#### Demo example
```<TwitterLikeButton isLiked={state} onClick={e => setState(e)}/>```

### Props

Name | Type | Description | Default
:--- | :--- | :--- | :---
isLiked | Boolean | Used for display heart state | false
onClick | Function | When heart is clicked then it will return `true` or `false` | () => {}
width | String | Set Dynamic Width | -
height | String | Set Dynamic Width | -

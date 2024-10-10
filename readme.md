### css property


```css
/* Box Model */
    .box-model {
      margin: 20px;
      padding: 10px;
      border: 2px solid black;
      width: 200px;
      height: 100px;
      box-sizing: border-box; /* Includes padding and border in width/height */
    }

    /* Background */
    .background {
      background-color: lightblue;
      background-image: url('https://via.placeholder.com/150');
      background-repeat: no-repeat;
      background-position: center;
      background-size: cover;
      height: 150px;
      width: 150px;
    }

    /* Color and Text */
    .text {
      color: darkblue;
      font-family: Arial, sans-serif;
      font-size: 20px;
      font-weight: bold;
      font-style: italic;
      line-height: 1.5;
      text-align: center;
      text-decoration: underline;
      text-transform: uppercase;
      text-shadow: 2px 2px 4px gray;
    }

    /* Flexbox */
    .flex-container {
      display: flex;
      justify-content: space-around;
      align-items: center;
      height: 150px;
      background-color: lightgray;
    }
    .flex-item {
      width: 100px;
      height: 100px;
      background-color: coral;
    }

    /* Grid */
    .grid-container {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      gap: 10px;
      background-color: lightgreen;
      padding: 10px;
    }
    .grid-item {
      background-color: lightcoral;
      padding: 20px;
      text-align: center;
    }

    /* Positioning */
    .relative {
      position: relative;
      top: 20px;
      left: 30px;
      background-color: lightcoral;
    }

    .absolute {
      position: absolute;
      top: 100px;
      right: 50px;
      background-color: lightyellow;
    }

    .fixed {
      position: fixed;
      bottom: 10px;
      right: 10px;
      background-color: lightblue;
    }

    /* Border */
    .border {
      border: 2px solid red;
      border-radius: 10px;
      width: 150px;
      height: 150px;
    }

    /* Display and Visibility */
    .hidden {
      display: none;
    }
    .visibility-hidden {
      visibility: hidden;
    }

    /* List Properties */
    .list {
      list-style-type: square;
      list-style-position: inside;
    }

    /* Animation */
    @keyframes example {
      0% { background-color: red; }
      100% { background-color: yellow; }
    }
    .animate {
      width: 100px;
      height: 100px;
      background-color: red;
      animation: example 2s infinite;
    }
```

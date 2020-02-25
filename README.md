## Available Scripts

A very simple to use react outside click package.
````
npm i @alphasquad/outside-click

OR

yarn add @alphasquad/outside-click
````

### Demo

![](https://alpha-squad-docs.s3.amazonaws.com/images/outside.gif)

### How to use?

````
import React from "react";
import OutsideClick from "@alphasquad/outside-click";

const Component: React.FC<> = () => {

    const closeMethod = () => {
        //   Action on outside click 
    }

    return <OutsideClick onClose={closeMethod}>
        // ... Your component
    </OutsideClick>
}

export default Component;

````
# React-Streamline

# How to use

1. First import the icon package you want to use 

```bash
$ yarn add @streamline/line-essentials
```

2. Then add this core library 
```bash
$ yarn add @streamline/core
```

3. In your project, import the desired icon

```js

import React, {Component} from 'react';
import ReactDOM from 'react-dom';
import {pen, trash, faceId} from '@streamline/line-essentials';
import {StreamlineIcon} from '@streamline/core';


const Pen = () => (<StreamlineIcon icon={pen} classes={'edit'})

ReactDOM.render(<Pen/>, 
                document.getElementById('root'));

```



# API

| props | default value | impact | required |
| ----- | ------------- | ------ | -------- |
| icon  | _none_ | icon displayed  | *YES* |
| classes  | _none_ | classes applied to the icon  | No |

# Maintainers

 - [Clément SAUVAGE](https://twitter.com/clementsauvage) 
 - [Vincent LE MOIGN aka Webalys](https://twitter.com/webalys)

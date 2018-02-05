# React-Streamline

# How to use

1. First import the icon package you want to use 

```bash
$ yarn add react-streamline-line
```

2. Then add the core library 
```bash
$ yarn add react-streamline
```

3. In your project, import the desired icon

```js

import React, {Component} from 'react';
import ReactDOM from 'react-dom';
import {pen, trash, faceId} from 'react-streamline-essentials';
import Streamline from 'react-streamline';


const Pen = () => (<Streamline icon={pen} classes={'edit'})

ReactDOM.render(<Pen/>, 
                document.getElementById('root'));

```



# API

| props | default value | impact | required |
| ----- | ------------- | ------ | -------- |
| icon  | _none_ | icon displayed  | *YES* |

# Maintainers

 - [Clément SAUVAGE](https://twitter.com/clementsauvage) 
 - [Vincent LE MOIGN aka Webalys](https://twitter.com/webalys)

# List of companies which use this lib 

- Les Tontons Livreurs : https://lestontonslivreurs.com

_Want to be featured ? Open a PR with a screenshot_

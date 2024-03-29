---
marp: true
title: TinyMl guide for everyone
description: 
theme: uncover
paginate: true
_paginate: false
---
![bg](./assets/gradient.jpg)

# <!--fit--> TinyML Guide 

How to become a TinyML Engineer

https://github.com/degiaaaa/TinyML-Guide


<style scoped>a { color: #eee; }</style>
---
<!-- This is presenter note. You can write down notes through HTML comment. -->
 
![Marp bg 90%](https://hackster.imgix.net/uploads/attachments/1412130/_AR2Bmqf88G.blob?auto=compress%2Cformat&w=900&h=675&fit=min)

![Marp bg 90%](data:image/jpeg;base64,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)

---

<!-- This is presenter note. You can write down notes through HTML comment. -->
 
![Marp bg 30%](https://images-na.ssl-images-amazon.com/images/I/615LwhJwQhL.jpg)


---

<!-- _backgroundColor: "#123" -->
<!-- _color: "#fff" -->

##### <!--fit--> [Tensorflow Lite](https://www.tensorflow.org/lite/examples) 

```
import tensorflow as tf
import numpy as np
from tensorflow import keras
```
```
model = tf.keras.Sequential([keras.layers.Dense(units=1, input_shape=[1])])
model.compile(optimizer='sgd', loss='mean_squared_error')

xs = np.array([-1.0,  0.0, 1.0, 2.0, 3.0, 4.0], dtype=float)
ys = np.array([-3.0, -1.0, 1.0, 3.0, 5.0, 7.0], dtype=float)

model.fit(xs, ys, epochs=500)
```
---
Muss noch schauen wie man style einbaut
```style 

div.tworows {
  margin-top: 10px;
  column-count: 1;
}
div.tworows p:first-child,
div.tworows h1:first-child,
div.tworows h2:first-child,
div.tworows ul:first-child,
div.tworows ul li:first-child,
div.tworows ul li p:first-child {
  margin-top: 0 !important;
}
div.tworows p.break {
  break-before: row;
  margin-top: 0;
}
```

---
theme: default
---

<style scoped>
table {
    height: 100%;
    width: 100%;
    font-size: 20px;
    color: red;
}
th {
    color: blue;
}
</style>

# Fruit Table -- styled

Fruit | Colour | Amount | Cost
-----|------|:-----:|------:
Banana | Yellow | 4 | £1.00
Apple | Red | 2 | £0.60
Orange | Orange | 10 | £2.50
Coconut | Brown | 1 | £1.50

---

# Fruit Table -- default

Fruit | Colour | Amount | Cost
-----|------|:-----:|------:
Banana | Yellow | 4 | £1.00
Apple | Red | 2 | £0.60
Orange | Orange | 10 | £2.50
Coconut | Brown | 1 | £1.50
---

<!-- _backgroundColor: "#123" -->
<!-- _color: "#fff" -->

##### <!--fit--> [MCU like Arduino](https://create.arduino.cc/projecthub/projects/tags/tinyml) 

##### <!--fit--> 👉 The easiest way to host<br />your Marp deck on the web

---

![bg right 60%](https://icongr.am/octicons/mark-github.svg)

## **[GitHub Pages](https://github.com/pages)**

#### Ready to write & host your deck!

[![Use this as template h:1.5em](https://img.shields.io/badge/-Use%20this%20as%20template-brightgreen?style=for-the-badge&logo=github)](https://github.com/yhatt/marp-cli-example/generate)

---

![bg right 60%](https://icongr.am/simple/netlify.svg?colored)

## **[Netlify](https://www.netlify.com/)**

#### Ready to write & host your deck!

[![Deploy to Netlify h:1.5em](./assets/netlify-deploy-button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yhatt/marp-cli-example)

---

![bg right 60%](https://icongr.am/simple/zeit.svg)

## **[Vercel](https://vercel.com/)**

#### Ready to write & host your deck!

[![Deploy to Vercel h:1.5em](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/yhatt/marp-cli-example)

---

### <!--fit--> :ok_hand:

---

![bg 40% opacity blur](https://avatars1.githubusercontent.com/u/3993388?v=4)

### Created by Yuki Hattori ([@yhatt](https://github.com/yhatt))

https://github.com/yhatt/marp-cli-example




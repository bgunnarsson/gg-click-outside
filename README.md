# _Click Outside_

Click outside of elements to close them.

---

### `Install`

```
$ npm i --save @gunnarssongroup/click-outside
-or-
$ yarn add @gunnarssongroup/click-outside
```

### `Usage`
```
import { ClickOutside } from '@gunnarssongroup/click-outside'

ClickOutside({callback: () => {console.log('callback from ClickOutside')}})

```

### `Project Setup`

<details>
<summary><strong>Package</strong></summary>

#### `Install node modules`

```
Open the package folder [~\package\] in a terminal and run:

$ npm i

```

#### `Build`

```
Open the package folder [~\package] in a terminal and run:

$ npm run build

This will move all relevant files to [~\package\build\]
```

</details>

<details>
<summary><strong>Tester</strong></summary>

#### `Install node modules`

```
Open the tester folder [~\tester\] in a terminal and run:

$ npm i
```

#### `Build`

```
Open the tester folder [~\tester] in a terminal and run:

$ npm run build

This will move all relevant files to [~\tester\public\build\]
```

#### `Run`

```
Open the tester folder [~\tester\] in a terminal and run:

$ npm run dev

This will run the webpack dev server and serve the development CSS and Javascript
```

### `IIS / Server Setup`

```
Set up a website on a server of your choosing and point it to [~\tester\public\]
```

</details>



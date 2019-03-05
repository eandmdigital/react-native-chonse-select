# react-native-chonse-select
react native chonse select tab horizontal

## Install
	npm install --save react-native-chonse-select
	yarn add react-native-chonse-select

	![Atom](https://imgur.com/Ih8o5Yx.png)
## Usage
#### Import library
```javascript
import { ChonseSelect } from 'react-native-chonse-select';
```
#### Create data
```javascript		
const data = [
	{
		value:'0',
		label:'Male'
	},
	{
		value:'1',
		label:'Female'
	}
]
```
#### Render components
```javascript
<ChonseSelect
	height={35}
	style={{ marginLeft: 20, marginBottom: 10 }}
	data={data}
	initValue={'0'}
	onPress={(item) => this.setState({ gender: item.value })}
/>
```
## Proptypes
| Props         |                         Description                     |     Default    |
| ------------- |:-------------------------------------------------------:| --------------:|
| data          | Initialize the item list                                | none|required |
| initValue     | initialize the default data                             | none|required |

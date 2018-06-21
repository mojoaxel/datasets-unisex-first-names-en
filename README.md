# datasets-unisex-first-names-en
A list of common gender-neutral first names in English speaking countries.

## Installation

```sh
npm install --save datasets-unisex-first-names-en
```

## Usage

```js
import names from "datasets-unisex-first-names-en";

function randomName() {
	return names[Math.floor(Math.random()*names.length)];
}

console.log(`${randomName()} loves ${randomName()} !`);
```

This will print something like: `Bobbie loves Charlie !`


## Contribute

Please feel free to add new gender-neutral english names (or remove incorrect ones!).  
Please make sure the list stays sorted alphabetically. 
Thx!

## License

This dataset is [unlicensed](LICENSE). 
You can use it without any restrictions other than human rights ;-)
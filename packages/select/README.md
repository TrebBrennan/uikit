@gov.au/select
============

> The form select element for multiple options


## Contents

* [Install](#install)
* [Usage](#usage)
* [Dependency graph](#dependency-graph)
* [Build](#build)
* [Tests](#tests)
* [Release History](#release-history)
* [License](#license)


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Install


```shell
yarn add @gov.au/select
```

```shell
npm install @gov.au/select --save-dev
```


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Usage


* [React](#react)


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


### React

Usage:

```jsx
import Select from './select.js';

<Select id="exampleSelect" options={[
	{
		value: '',
		text: 'Please select',
	},
	{
		value: '1',
		text: 'Option 1',
	},
	{
		value: '2',
		text: 'Option 2',
	},
]} />
```

All props:

```jsx
<Select
	id="unique"            {/* Unique ID, a must so you can tie a label to it */}
	block={ true }         {/* The block option to make the select fill the available width, optional */}
	onChange={ () => {} }  {/* A function to execute when the select value is changed, optional */}
	options={[             {/* All options in a neat array */}
		{
			value: '1',        {/* The value attribute of the option */}
			text: 'Option 1',  {/* The text of the option */}
		},
	]}
/>
```

For more details have a look at the [usage example](https://github.com/govau/uikit/tree/master/packages/select/tests/react/index.js).


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Dependency graph

```shell
select
└─ core
```


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Build


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Tests

The visual test: http://uikit.apps.staging.digital.gov.au/packages/select/tests/site/


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Release History

* v0.3.1 - Moving to system fonts
* v0.3.0 - Added pancake-react plugin, ES5 main file
* v0.2.0 - Added react component
* v0.1.0 - 💥 Initial version


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## License

Copyright (c) Commonwealth of Australia.
Licensed under [MIT](https://raw.githubusercontent.com/govau/uikit/packages/core/master/LICENSE).


**[⬆ back to top](#contents)**

# };

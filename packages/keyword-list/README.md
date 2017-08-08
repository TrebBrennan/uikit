@gov.au/keyword-list
============

> A list style for emphasising parts of a list item, useful for repeating phrases across that list’s items. 


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
yarn add @gov.au/keyword-list
```

```shell
npm install @gov.au/keyword-list --save-dev
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
import KeywordList from './keyword-list.js';

<KeywordList
	repeatedName='Department of'
	items={[
		{
			link: 'http://www.agriculture.gov.au/',
			name: 'Agriculture and Water Resources',
		},
		{
			link: 'https://www.communications.gov.au/',
			name: 'Communications and the Arts',
		},
		{
			link: 'https://www.finance.gov.au/',
			name: 'Finance',
		},
	]}
/>
```

All props:

```jsx
<KeywordList
	repeatedName="Department of"                  {/* The text That is repeated in each item */}
	items={[                                      {/* All items in a neat array */}
		{
			link: 'http://www.agriculture.gov.au/',   {/* The URL of this item, optional */}
			name: 'Agriculture and Water Resources',  {/* The name of the item */}
			onClick={ () => {} }                      {/* A function to execute when the link is clicked, optional */}
		},
	]}
/>
```

For more details have a look at the [usage example](https://github.com/govau/uikit/tree/master/packages/keyword-list/tests/react/index.js).


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Dependency graph

```shell
keyword-list
├─ core
└─ link-list
   ├─ core
   └─ body
      └─ core
```


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Build


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Tests

The visual test: http://uikit.apps.staging.digital.gov.au/packages/keyword-list/tests/site/


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

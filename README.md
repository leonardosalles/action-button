# &lt;action-button&gt;

Write a simple and easy action button without javascript and form submit.

> Maintained by [Leonardo Salles](https://github.com/leonardosalles).

## Demo

> [Check it live](http://leonardosalles.github.io/action-button).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/action-button.html">
	```

3. Start using it!

	```html
	<action-button></action-button>
	```

## Options

Attribute  | Options                        	| Default             | Description
---        | ---                            	| ---                 | ---
`id`       | *int*                          	| ---                 | The id of resource ex: http://api.resource.com/user/2
`type`     | `add`, `remove`, `update`, `find`  | `find`              | Specifies the request method
`body`     | *json*                    		| ---                 | A valid json for request body
`headers`  | *json*                    		| ---                 | A valid json for request headers
`resource` | *string*                  		| ---                 | URL of resource ex: http://api.resource.com/user/
`class`    | *string*                  		| ---                 | The css class for button design
`callback` | *function*                  	| ---                 | The callback function of request

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)

# &lt;gravatar-image&gt;

Web Component wrapper for Gravatar using Polymer

> Maintained by [Djalma Araújo](https://github.com/djalmaaraujo).

## Demo

> [Check it live](http://djalmaaraujo.github.io/gravatar-image).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="lib/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/gravatar.html">
	```

3. Start using it!

	```html
	<gravatar-image username="your-gravatar-email-here" or use hash="your-md5-email-here"></gravatar-image>
	```

## Options

|   Attribute   | Options  |              Default               |                      Description                      |
| ------------- | -------- | ---------------------------------- | ----------------------------------------------------- |
| `username`    | *string* | `someemail@example.com`            | Your gravatar email                                   |
| `hash`        | *string* | `be74fd9a577ea5ef1ab2e7c71bcfa4b5` | MD5 hash of your email (prevent to expose your email) |
| `size`        | *int*    | `80`                               | The img size                                          |
| `placeholder` | *string* | `gravatar default image`           | To add a default image for your gravatar image        |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)

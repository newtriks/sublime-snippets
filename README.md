# Sublime Text Snippets

General [Sublime Text](http://www.sublimetext.com/3) snippets. 

Currently feature:

1. React ES6
2. Jasmine ES6
3. Webpack

## Other config tips

1. To enable HTML tag tab completion add the following to `Preferences > Key Bindings – User`:

		{ "keys": ["tab"], "command": "expand_abbreviation_by_tab", "context": [{ "operand": "source.js", "operator": "equal", "match_all": true, "key": "selector" }] }
		
1. To create a new JavaScript file by default which inludes a code snippet e.g. `use strict';\n\n`. Install [Sublime-AdvancedNewFile](https://github.com/skuroda/Sublime-AdvancedNewFile) and edit `Preferences > Package Settings > AdvancedNewFile > Settings User`:

		"default_extension": ".js",
		
		"file_templates": {
        "js": "'use strict';\n\n"
        }

### Thanks 

React snippets are copied from the awesome [babel/babel-sublime](https://github.com/babel/babel-sublime/blob/master/SNIPPETS.md).

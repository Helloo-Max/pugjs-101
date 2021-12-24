### Description

Pug is a template language to conveniently write your HTML and add dynamic behavior to it.
For example the code `h1 Welcome to my page!` will be transformed into `<h1>Welcome to my page!</h1>` with Pug.
Check out the [documentation](https://github.com/pugjs/pug) for more information.

### Installation

1. Add pug to your project:  
   `yarn add pug`
2. Add it globally to your command line:
   `yarn global add pug-cli`

### Watch Mode & Output Mode

Start to watch your .pug files and compile it into an index.html:  
`pug -w ./ -o ./html -P`

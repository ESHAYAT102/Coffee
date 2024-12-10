<h1 align="center">Coffee</h1>
<p align="center">
<a href="https://coffee.eshayat.com"><img alt="website" src="https://img.shields.io/badge/website-blue"/></a>
<a href="https://www.npmjs.com/package/brew-coffee"><img alt="npm" src="https://img.shields.io/badge/npm-coffee-orange"/></a>
</p>
<h4 align="center">A coffee-themed scripting language</h4>

<br />

<h2 align="center">Installation</h2>

```

  npm i -g brew-coffee

```

<h2 align="center">Usage</h2>

<h4 align="left">Create a new file (<code>test.coffee</code>)</h4>

<h4 align="left">Edit the file with a text editor.

```

  brew message = "Hello!"
  serve(message)

  brew coffeeDone = true

  sip (coffeeDone) {
    serve("Coffee is ready!")
  } pour {
    serve("Failed to get coffee.")
  }

```

<h4 align="left">Run</h4>

```

  coffee example.coffee

```

<h4 align="left">Output</h4>

```

  Hello!
  Coffee is ready!

```

<h2 align="center">Documentation</h2>

<h3 align="center">Variables</h3>
<p align="center">Variables can be declared using <code>brew</code>.</p>

```

  brew text = "Hello!"

```

<h3 align="center">Types</h3>
<p align="center">Numbers, strings, booleans are like other languages. Null values can be denoted using <code>air</code>.</p>

```

  brew n1 = 12
  brew n2 = 16.64
  brew str = "Text here"
  brew str = 'Here too'
  brew bool1 = true
  brew bool2 = false
  brew null = air

```

<h3 align="center">Built-ins</h3>
<p align="center">Use <code>serve</code> to print anything to console.</p>

```

  serve("Hi!")

```

<h3 align="center">Conditionals</h3>
<p align="center">Coffee supports if-else-if ladder construct , <code>sip</code> is <b>if</b> block, <code>drip</code> is <b>else if</b> block, and the <code>pour</code> is the <b>else</b> block. </p>

```

  brew coffee = 10

  sip (coffee < 10) {
    serve("If")
  } drip (coffee > 10) {
    serve("Else If")
  } pour {
    serve("Else")
  }

```

<h3 align="center">Loops</h3>
<p align="center"><code>stir</code> is <b>while</b> loop.</p>

```

  brew i = 0

  stir (i < 10) {
    serve("Coffee")
    i++
  }

```

<h3 align="center">Functions</h3>
<p align="center"><code>roast</code> is for <b>function</b>.</p>

```

  roast coffee() {
    serve("Hello!")
  }

  coffee()

```

<h3 align="center">Execution</h3>
<p align="center">After installing Coffee with npm, use <code>coffee &lt;FILE_NAME&gt;</code> in the terminal to execute the coffee code.</p>

```

  coffee example.coffee

```

## Welcome to My GitHub Pages

My name is Yan Pan, and I am working in Shanghai, China.

This is my GitHub [page](https://github.com/YanPanMichael).

If you are interested in building some repositories together, please join us!!!

Please leave your comments and thank you very much for your valuable advice 😊

### qk-release

a beautiful tool to build an integrated commit, build, change log, push and publish process.

For more details see [Source Code](https://github.com/YanPanMichael/qk-release) and [NPM Package](https://www.npmjs.com/package/qk-release)

### chanlog

A beautiful javascript tool for quickly changing log and generate CHANGELOG file.

For more details see [Source Code](https://github.com/YanPanMichael/chanlog) and [NPM Package](https://www.npmjs.com/package/chanlog)

### astart-cli

A powerful scaffolding tool for initializing seed applications with templated solutions.

For more details see [Source Code](https://github.com/YanPanMichael/astart-cli) and [NPM Package](https://www.npmjs.com/package/astart-cli)

### Struk

A powerful component building and packaging tool based on Rollup.

**Add custom configuration in struk.config.js**
```markdown
{
    input: 'src/index.js',
    output: {
        directory: 'dist',
        name: 'bundle',
        format: ['cjs', 'es', 'umd', 'iife', 'amd'],
        banner: 'Author: xxx',
    },
    formatConfig: {
        cjs: {
            external: ['xxx'],
        },
        es: {
            isolateDep: true,
        },
        umd: {
            external: [],
        },
        iife: {
            isolateDep: false,
        },
        amd: {
            isolateDep: false,
        }
    },
    styleExtract: false,
    templateBase: 'examples/',
    replaceMaps: {
        'process.env.NODE_ENV': 'production',
    }
    stylusAlias: {
        '~': path.join(process.cwd(), './src')
    }
}
```
**Add command line in package.json**
```js
  "scripts": {
    "build": "struk build --source=ts"
  },
```

- Support _3_ kinds of input formats **JS, TS, Vue**
- Support _5_ kinds of output formats **umd, es, cjs, iife, amd**

Not open source yet, please hold on, I will publish soon.

### Hent

A network library based on Axios and its related ecological implementation.

Not open source yet, please hold on, I will publish soon.

### Support or Contact

Having trouble with this page? Check out the [contact](mailto:1214863281@qq.com) and we’ll help you sort it out.

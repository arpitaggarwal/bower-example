### Make a New Bower project

```
bower init
```

### Installing Packages

`bower install ` - Install all packages mentioned in `bower.json`

`bower install package --save ` - Install package and save it in `bower.json`. Package can be a GitHub shorthand, a Git endpoint, a URL, and a lot more.


### Searching Packages

```
bower search package
```

### Uninstalling Packages

```
bower uninstall package
```

### Configuring Bower with .bowerrc

To configure Bower, you have to create a file called `.bowerrc`. It's in the root directory of your project (alongside the bower.json file). We can have one .bowerrc file per project, with different settings.

One useful option is the directory option, which lets you to customize the folder in which Bower saves all its packages. To set this simple option, create a .bowerrc file that looks like this:


```
.bowerrc
{
  "directory": "js/"  
}
```

If `.bowerrc` file is present with directory location all files mentioned in `bower.json` will be loaded in the directory else in default `bower_components` directory.

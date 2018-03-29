# Connect Demo App Template

To run the page.

1. Instal `bower` and `polymer-cli` (bower is required, polymer-cli for convenience).

```
sudo npm i -g bower
sudo npm i -g polymer-cli
```

2. Clone the repo

```
git clone https://github.com/advanced-rest-client/connect-demo-app-template.git
cd connect-demo-app-template
```

3. Install default dependencies

```
bower i
```

4. Run the server

```
polymer serve --open
```

## To add a component

Search for components at https://www.webcomponents.org/.
Run `bower i [component name]` to add new component.

Then, include the component into the page

```html
<link rel="import" href="bower_components/[component-name]/[component-name].html">
```

And use it.
Enjoy.

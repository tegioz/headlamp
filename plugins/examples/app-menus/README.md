# Example Plugin: App Menus

Add menus when Headlamp is running as an app.

![screenshot of the custom details view section and action button](https://raw.githubusercontent.com/headlamp-k8s/headlamp/main/docs/development/plugins/images/app-menus.png)

To run the plugin:

```bash
cd plugins/examples/app-menus
npm install
npm start
# See the menu in the app.
```

The main code for the example plugin is in [src/index.tsx](src/index.tsx).

See the API documentation for:

- [Headlamp.setAppMenu](https://headlamp.dev/docs/latest/development/api/classes/plugin_lib.headlamp/#setappmenu)

# Example Plugin: Changing The Logo

This shows you how to change the Headlamp logo.

![screenshot of the logo being changed](https://raw.githubusercontent.com/headlamp-k8s/headlamp/main/docs/development/plugins/images/change-logo.png)

To run the plugin:

```bash
cd plugins/examples/change-logo
npm install
npm start
# See the logo in the top left corner of Headlamp has changed.
```

- The Logo can react to different size views (mobile and Desktop) sizes, and also to different themes (currently dark and light themes).
- You can use text if you do not want to create an image logo.
- For an image, at a minimum you will need to provide a small logo and a big one.
- There are two example svg images which you can check for sizes.
- Click the logo to see the two states the logo can be in (small and big).

The main code for the example plugin is in [src/index.tsx](src/index.tsx).

See the API documentation for:

- [registerAppLogo](https://headlamp.dev/docs/latest/development/api/classes/plugin_registry.registry/#registerapplogo)

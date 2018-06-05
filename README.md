# template-example
Screwdriver example for validating, publishing, and tagging multiple templates

In this example, we use the [screwdriver-template-main](https://github.com/screwdriver-cd/template-main) npm package to assist in template validation, publishing, and tagging.

This example will publish two templates: `golang/init` and `nodejs/test`. It will also tag the latest versions with the `latest` and `stable` tags, respectively. The `golang/init` template is located at the default template path `sd-template.yaml`, while the `nodejs/test` template is in a custom path `templates/nodejs.yaml`.

See the [templates documentation](https://docs.screwdriver.cd/user-guide/templates) for more information.

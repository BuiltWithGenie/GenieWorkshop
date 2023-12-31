# JuliaCon 2023 Genie workshop

This workshop will teach you how to build a production-grade app with the Genie Framework. This will be a multi-page app implementing exploratory data analysis, training of a machine learning model, and serving of the model as a web API. Moreover, we'll cover containerization and deployment.

![preview](preview.gif)


## Requirements

To follow the workshop you'll need the following:

- Template code including setup scripts, base code, and the `Project.toml` files for each app.
```bash
git clone --branch starter https://github.com/BuiltWithGenie/MultiPageApp.git
cd MultiPageApp
```
- Julia 1.9 (install with [juliaup](https://github.com/JuliaLang/juliaup))
- VSCode with the [Genie Builder](https://marketplace.visualstudio.com/items?itemName=GenieBuilder.geniebuilder) extension from the VSCode marketplace (mandatory only for no-code UI editing)
- [Slides](https://genieworkshop.netlify.app/1?print) - use up and down arrows to move through slides

If you've used Genie Builder before, it is recommended that you start with a fresh environment. For that, delete the geniebuilder folder with

```bash
rm -rf ~/.julia/geniebuilder
```

## Preparing for the workshop

Before the workshop starts, please make sure you have the requirements. Then, set up your environment by

- Installing the required packages and adding the apps to the Genie Builder environment with `gbsetup.sh`:
```bash
./gbsetup.sh
```

## Support

If you need any help with the setup, you can ask during the session or join the [Genie Discord](https://discord.com/invite/9zyZbD6J7H) and ask there.

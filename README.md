<p align="center"><a href="https://klipper.dev" target="_blank">
    <img src="https://static.klipper.dev/logo.svg" width="350">
</a></p>

Klipper Icons is the sets of svg and font icons for the **Progressive Web App** of [Klipper][1] platform.

Application required
--------------------

- [IcoMoon App](https://icomoon.io/app) to manage and build the fonts

Workflow
--------

1. Create the SVG icon with a viewport of `1024px` by `1024px`
2. Import the SVG into the icon set in IcoMoom App
3. Move the icon to the end of the IcoMoom Set
4. Select the icon
5. Edit the `Tags` and `Names` metadatas of the icon
6. Download the SVG of the icon and move it in the `./svg` directory
7. Generate the Fonts
8. Extract the `KlipperIcons` fonts of the generated Zip in the `./fonts` directory
9. Download and override the `KlipperIcons.json` project file of IcoMoom
10. Add the Scss mixins of the icon in the `./scss/klipper-icons-content.scss` file:
    - Use the icon name and the unicode with the `.ki-icon($name, $code)` mixin
    - The name and unicode value can be found in `_variables.scss` file of the generated Zip

Contributing
------------

Klipper Icons is an Open Source, community-driven project.

Issues and feature requests are tracked in the [Github issue tracker][3].

Pull Requests are tracked in the [Github pull request tracker][4].

License
-------

Klipper is completely free and released under the [MIT License][5].

About
-----

Klipper was originally created by [François Pluchino][2].

[1]: https://klipper.dev
[2]: https://github.com/francoispluchino
[3]: https://github.com/klipperdev/icons/issues
[4]: https://github.com/klipperdev/icons/pulls
[5]: LICENSE

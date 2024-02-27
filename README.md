<a href="https://www.jahia.com/">
    <img src="https://www.jahia.com/modules/jahiacom-templates/images/jahia-3x.png" alt="Jahia logo" title="Jahia" style="float: right" height="60" />
</a>

JQuery
======================
jQuery provider module for Jahia Platform.

## Open-Source

This is an Open-Source module, you can find more details about Open-Source @ Jahia [in this repository](https://github.com/Jahia/open-source).


## How to compile
 - Run `yarn install` to install the dependencies defined in package.json
 - Run `yarn build` to copy jquery files to the resources folder
 - Run `mvn clean install` to build the module
 - Deploy the module in your Jahia instance

#### Note
When upgrading JQuery do not forget to update build script in package.json to copy the new version of jquery to the resource folder.

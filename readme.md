## Cordova Materialize Template
Simple template for create a Cordova project with Materialize CSS & Font Icons

### Usage
- <code>cordova create project_name you.company.projectId app_name --template https://github.com/ferro-team/cordova-materialize-template</code>

### Reconfig template
Change directory to project_name directory and run following command
- <code>npm install</code>
- <code>cordova prepare</code>
- <code>cordova clean</code>
- <code>cordova run</code> for test project

and edit template with you style

### Dependencies
- <code>material-design-icons</code>
- <code>materialize-css</code>

### Cordova Plugins
- <code>cordova-plugin-splashscreen</code>
- <code>cordova-plugin-x-toast</code>

### How to create this template
- create template folder <code>mkdir template_folder_name</code>
- going to template folder <code>cd template_folder_name</code>
- run <code>npm init</code> this step will contain package.json for this package
- create file <code>index.js</code> to access template_src folder
- run <code>cordova create template_src_name</code> to create your template_src under template_folder_name
- add platform <code>cordova platform add android@8 --save</code> this support for android kitkat minimum
- add plugin you need <code>cordova plugin add cordova-plugin-<plugin_name> --save</code>
- edit template would you need
- push everything to github and get origins remote link to template
- and call template via command in [usage](https://github.com/Komsan74/cordova-materialize-template/blob/master/readme.md#usage) above.
- Reconfig it and fun!

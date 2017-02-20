# CKAwesome
 CKAwesome is a Font Awesome plugin for CKEditor.<br />
 It allows you to easily insert a Font Awesome icon into your text in CKEditor.<br />
 The dialog loads the Font Awesome css file to know the avaiable icons and shows them on a select box.

# Install
1. Extract the downloaded file into the CKEditor’s plugins folder.
2. Enable the plugin by changing or adding the extraPlugins line in your configuration (config.js):
  - `config.extraPlugins = 'ckawesome';`
3. Add the icon to the toolbar (optional):
  - `config.toolbar = [{ name: 'CKAwesome', items: ['Image', 'ckawesome']}];`
4. Add the path to your Font-awesome css file:
  - `config.fontawesomePath = 'path/to/your/fontawesome/folder/font-awesome.min.css';`

# Demo
http://io.blackdevelop.com/ckawesome/

#License
© 2017, Blackdevelop under GNU GPL v3.

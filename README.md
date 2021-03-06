# things-code-editor

## This is a component that can edit and save the code.

  Example:
```html
    <things-code-editor
      id="code-editor"
      theme="ace/theme/monokai"
      mode="ace/mode/javascript"
      fontsize="12px"
      tabsize="2"
      source="var source = function() { console.log('this is Code Editor') };">
    </things-code-editor>
```
# things-template-editor

## This is a component that can edit and save the template.
  Example:
  ```html
    <things-template-editor
        id="template-editor"
        theme="ace/theme/monokai"
        mode="ace/mode/html"
        fontsize="10"
        tabsize="2"
        source="<h1>Hello, this is Template Editor</h1>">
    </things-template-editor>
  ```
# things-editor-script

## This is a WEB Editor that can set the theme using ace-editor.

  Example:
  ```html
    <things-editor-script
      id="editor"
      value="{{text}}"
      theme="ace/theme/monokai"
      mode="ace/mode/javascript">
    </things-editor-script>
  ```
    
    
## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-code-editor/`, where `things-code-editor` is the name of the directory containing it.

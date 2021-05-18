# CS569 Homework 02
* Create a new Angular Project using the CLI.
* Create two new components `child-one`, and `child-two`, use Angular CLI to create the first component and create the second component manually. Both components should use inline template and style. Manage the necessary changes in `AppModule`.
* Render both components as a direct child to `AppComponent`. 
* Both components will have a local public property `data` that's assigned a value in the constructor. Assign the following object to it: `{name: "Child One"}`. Add the correct types to the property `data`, each component will render a paragraph and bind to `name` property ot the `data` object to be displayed within the paragraph. 
* Add style to `child-one` component and set the paragraph font size to `32px` and color to `#037d50`.
* Inspect the default emulated style encapsulation for `child-one` component. Then change the encapsulation to `none` and notice the changes in all components.

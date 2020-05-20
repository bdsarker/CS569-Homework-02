# CS569 Homework 03
* Create a new Angular Project using the CLI.
* Create two new components `child`, and `grandchild`. Both components should use inline template and style. Notice the changes in `AppModule`.
* Both components will have a local string property `data` that's assigned a value in the constructor. Both components will display a paragraph and bind to `data`. 
* Render the `child` component as a direct child to `AppComponent`, and `grandchild` component as a child to `child` component. 
* Add style to `grandchild` component and set the paragraph font size to `32px` and color to `#037d50`.
* Inspect the default emulated style encapsulation for `child` component. Then change the encapsulation to `none` and notice the changes in `child` component.

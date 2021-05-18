# CS569 Homework 02
### Question 1
Write in a new markdown file `hw2-question1.md` the answer of the following questions:
1. Explain how Angular application boots?
2. Expain all the meta-data passed to `@NgModule` factory decorator? Use the [official Angular docs](https://angular.io/api/core/NgModule).
3. Explain how the default Emulated style encapsulation of Angular works?
4. Do your research on custom [Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)? What are they? and explain how the shadow DOM is important for creating custom Web Components. 

### Question 2 - Angular Hands-On Practice
* Create a new Angular Project using the CLI.
* Use Angular CLI to create the `child-one` component and create the second component `child-two` manually. Both components should use inline template and style, and no test file.
* Render both components as a direct child to `AppComponent`. 
* Both components will have a local public property `data` that's assigned a value in the constructor. Assign the following object to it: `{ name: "Child One" }`. Add the correct types to the property `data`, each component will render a paragraph and bind to `name` property of the `data` object to be displayed within the paragraph. 
* Add style to `child-one` component and set the paragraph font size to `32px` and color to `#037d50`.
* Inspect the default emulated style encapsulation for `child-one` component. Then change the encapsulation to `None` and notice the changes in all components.

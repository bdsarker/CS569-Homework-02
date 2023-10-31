# CS569 Homework
### Question 1
Write in a new markdown file `hw2-question1.md` the answer to the following questions:
1. Write a summary about how Angular application bootstrap.
2. Write a summary of the meta-data we covered that is passed to `@NgModule` factory decorator. Read more details on the [official Angular docs](https://angular.io/api/core/NgModule).
3. Write a summary of the meta-data we covered that is passed to `@Component` factory decorator. Read more details on the [official Angular docs](https://angular.io/api/core/Component).
4. Explain the difference between the default Emulated style encapsulation and the ShadowDOM.

### Question 2 - Angular Hands-On Practice
* Create a new Angular Project using the CLI.
* Configure the CLI component schematics in the `angular.json` file to use an inline template and inline style, flat no-folder, and without test files by default.
* Use Angular CLI to create the `child-one` and `child-two` components. 
* Render both components in the `AppComponent` template (as direct children). 
* Both components will render a paragraph that binds to a `data` property to be displayed within the paragraph in the template (View). 
* Implement the following lifecycle hooks in both components: `onInit`, `doCheck`, `afterViewInit`, and `afterViewChecked`. Each lifecycle hook prints to the console a message that shows which hook is invoked and from which component (For example: `Child 2: doCheck`).
* Create a timer in the constructor of the `child-one` component that changes the `data` property to another value after 5 seconds.
* Write down the console logs output of the following: 
    * which lifecycle hooks were called on Mounting the component?
    * which lifecycle hooks were called after the timer callback function is triggered?

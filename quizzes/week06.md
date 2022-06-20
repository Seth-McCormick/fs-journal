# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
App.vue
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
component is the where the guts of what is shown on the page comes from, especially if you want to display the guts on multiple pages since you cant pull from a page to a page. page is the parent and component is the child
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
template, script, and style
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
liskov substitution principle
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
the navbar
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
appstate is where we store our data so it can be used without different components as need be.
the state object within a Component can only be accessed there unless you add props to it so it can be seen somewhere else.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
the responsibility of services is still almost same as it has been in the past, it is still the chef who has access to the fridge and can grab the ingredients and make the food.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
template?
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
style tag, scoped attribute
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
reactive,
watchEffect
```
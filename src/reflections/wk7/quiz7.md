# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
1. One way data binding:
---Putting an object in the return object inside the script tags and referencing the key in like this {{ name }} inside the template to inject the data into template.
--- Binding attributes ( @click, :key, :class) to reference methods inside the return object inside the script tags.
---Attribute Binding: ( :class="{className: conditional}") ( :disabled="conditional")
2. Two way data binding:
v-model
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single page application!
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Page reloads not required- quicker load times. Decoupled- back end & database can be changed out and not impact application. Rendering managed by client browser, so lighter server load. Caching & offline functionality- data from app gets pre-loaded so if internet connection goes out, user can still navigate somewhat around the page.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
When the page is loaded, any method inside of onMounted will run.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
For two-way data bindings on form inputs, textarea's and select elements. To create new objects of an existing property
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
listens to DOM events like @submit or @click and run some javascript when they're triggered.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if/v-else-if/v-else. If this value results to true, then display this element.
v-show. If condition is false, element is still in html, it just has a display value of none.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The purpose of the key is to have a unique thing to distinguish one element from the next. In my experience so far, it's an id.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
a way for a component to inject content into a child component. sort of similar to props. getting data from a parent component to a child component.
```
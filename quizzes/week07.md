# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
We can either V-bind data which is when you manipulate or assign values to HTML attributes, styling, and classes. This occurs within the carrots of a tag. The other way is using the "mustache" syntax or between double curly braces. This will usually occur between the opening and closing tags of an element. It is also called binding expressions.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
This stands for a 'Single Page Application'. This is an application that occurs on a single page, changing dynamically to a user and drawing different elements to a page rather than changing page to page which requires page reloads.
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
They have a higher performance, are more responsive and provide a smoother user experience. The users request will load a JSON file rather than an entire webpage. They run on mostly asynchronous requests which reduce server load and require less bandwidth. 
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
The onMounted method runs whatever code is within it before the webpage renders.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
v-models are used to implement 2-way binding on a component. You would use the v-model when binding a users inputs to a value to use later. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
The v:on directive is used as an event handler.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
you can use the v-if directive to conditionally render a block using truthy/falsy logic. You can also use the v-else and v-else-if directives in tandem to the v-if directive to conditionally render elements to the page. You can alternatively use the v-show directive in the same fashion as a v-if directive. You would use this if you would like your element to remain in the DOM.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The purpose of a key attribute in a v-for element is to give each item in the v-for a unique idenetity so the DOM does not need to move the order of the elements when data items change. This is something used by Vue to patch each element in-place.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The slot element allows a component to inject a piece or an entire component into a child component. The slot element is a slot outlet where the slot content will be injected into. It simply provides a spot for a specific chunk of code to be placed from another component.
```
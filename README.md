# Best React Date Pickers

### We'll take a look at some of the most popular datepickers and evaluate them by these parameters:
1. The weight of the datepicker itself or the library in which it lies
2. Extensibility and scalability
3. Perfomance
4. How easy it is to style
5. Support by creators

## React Datepicker - https://reactdatepicker.com

react-datepicker is one of the most popular date pickers on the market today. It is simple, reliable and you can never go wrong with a classic.
The great thing about this library is that its documentation has examples of all the use cases you can think of. Things like using custom class names, highlighting specific days, and adding date and time filters all have corresponding examples. Their examples also use vanilla JavaScript which means that the developer can use any date library for date manipulation. It uses date-fns for localization though.
The downside with this library is that it's default UI doesn't look that great. It's built to be simple, thus it assumes that the developer will have to customize the styles on their own.


<img width="502" alt="172 6 kB" src="https://user-images.githubusercontent.com/41162650/180468460-e9992b67-7dec-4cc8-8c48-f396033e29d8.png">

---

## Material UI - https://mui.com/x/react-date-pickers/getting-started/

If you're using Material UI as the base for the UI components of your project, you will most likely have to use Material UI's date and time picker as well.
The good thing about this library is that even though you're constrained with Material Design, it is still very customizable. You can customize the styles via the createMuiTheme() function provided by Material UI.
This is the only component in this list that has a clock view. This makes it very easy to pick the time in both desktop and mobile views.
The examples in the official documentation use date-fns as the datetime library for parsing and formatting dates but you can certainly use the datetime library of your choice.

Main Features
* Follows Material UI design
* Date/time picker
* Date library agnostic
* Localizable

<img width="513" alt="230 4 kB" src="https://user-images.githubusercontent.com/41162650/180468611-e22db181-9a7a-4828-8c5c-31f82905c593.png">

---

## Ant Design - https://ant.design/components/date-picker/#header

Just like React Rainbow, the date and time picker comes packaged with the whole UI component library itself. It follows the Ant Design Specifications so there's really a huge focus on the consistency of the design to provide better user experiences. This means that you'll only get the full benefit of using this component if you also use the whole UI component library.
By default, the date picker uses Moment.js for working with dates. But they also provide a way to use another one which is great, especially if you're concerned about the bundle size.
Another great thing about it (and all of Ant Design's components) is that they provide editable demos via CodeSandbox, CodePen, and StackBlitz. This makes it really easy to try them out by simply forking their demo.

### Main Features
* Date, date range, and time picker
* Comes with a UI component library
* TypeScript support
* Localizable
* Date library agnostic

<img width="500" alt="1 2 MB" src="https://user-images.githubusercontent.com/41162650/180468664-ab212530-c94d-44cb-b07c-88d1004de470.png">

*You can't use only date picker from antd, you should install whole library

---

## Airbnb / React dates - https://airbnb.io/projects/react-dates/

Airbnb's React Dates is one of the older libraries on this list. But even though that's the case, it's still actively being maintained. Its localizable, mobile-friendly, and built with accessibility in mind. It relies on Moment.js for working with dates so it's a bit heavy compared to the lightweight libraries on this list.
The biggest downside of this library is that they don't have proper documentation and usage samples. All they have is a Storybook and a few examples on their GitHub repo. So if you're someone who is fairly new to React, or you don't like digging through the code a lot, you can probably skip this one.

### Main Features
* Date, date range picker
* Localizable
* Mobile-friendly
* Accessible

<img width="582" alt="BUNDLE SIZE" src="https://user-images.githubusercontent.com/41162650/180468746-eb04a704-6b3f-40e9-9c99-0c0c1f7ce7a4.png">

---

## React-day-picker - https://react-day-picker.js.org

This is the simplest library among the bunch. Pick this date picker if you're looking for a lightweight library for your project. Don't be fooled by its size, as it can provide all the common functionalities that date pickers usually need and more. Its base style is very simple which makes it easy to customize. It comes with its own date utilities for working with dates and localizing them. Though you can use your date library of choice if you want to.
The best part about this library is that it has an extensive list of examples for almost anything that you can do with it. For example, you can mark specific days as disabled or select a date range on click.

### Main Features
* Date range picker
* Calendar and text field input
* Localizable
* Customizable
* Comes with its own date utilities

<img width="539" alt="BUNDLE SIZE" src="https://user-images.githubusercontent.com/41162650/180468790-e047eb89-205b-4db3-ac89-b4e537bdb7ae.png">

---

## REACT-DATE-PICKER - https://projects.wojtekmaj.pl/react-date-picker/

One of the lightweight libraries in this list. This date picker doesn't depend on any date library in order to work. It has a customizable calendar view so you can have a month, year, decade, and even a century view.
The downside of this library is the lack of usage samples. It only has a usage sample for its most common use case. If your use case isn't very common, you'll need to dig through the prop documentation.

### Main Features
* Date and Time Pickers
* Date and Time Range Pickers
* Calendar
* Clock
* Customizable
* Lightweight Library
* No date library dependency

<img width="541" alt="1 1 kB" src="https://user-images.githubusercontent.com/41162650/180468837-ecead8c7-298f-401c-b9ef-7d08b7561ff5.png">

---

## Comparison:

<img width="731" alt="Pasted Graphic 7" src="https://user-images.githubusercontent.com/41162650/180468861-e01c2000-84e2-42d7-b482-57d05cb19dbc.png">

---

## Resume

Choosing one library for a date between them and call it the best solution for your project will be quite difficult, because it all depends on the requirements of the project and the task.

If you already have some MUI / ANT Design library in your project, it would be good choice to take internal date picker. They provides a lot of functional and customization tools, that will help you solve most of your tasks, it is also worth mentioning that these date pickers are very well supported, have a good reputation among many developers.But if you need some quick solution React Datepicker would be a perfect solution, it takes only 39.2kb of bundle size, yes, it's not a smaller than React Calendar or React-day-picker, but community are choosing this library because it really simple, customiseble and reusable date picker.
Other libraries also would be great solutions in some cases, all of them deserve to be in your project :)

---

## Resources
1. https://openbase.com/categories/js/best-react-date-picker-libraries
2. https://flatlogic.com/blog/top-12-react-datepickers-to-use-in-2021/
3. https://openbase.com/categories/js/best-react-date-picker-libraries
4. https://bundlephobia.com

# Graded Assessment: Portfolio app

## Task

In this final lab, you are going to create a portfolio page for yourself. You will be using the skills you have learned in this course to create a page that showcases your work.
The portfolio page will be a single page that will contain the following sections:

- A header with external links to social media accounts and internal links to other sections of the page
- A landing section with an avatar picture and a short bio
- A section to display your featured projects as cards in a grid fashion
- A contact me section with a form to allow visitors to contact you

Here you will have the opportunity to use some popular open source libraries that will help you to have a more polished and professional looking page.

Before proceeding further, let's provide an introduction to the libraries you will be using.

### Libraries

#### Chakra UI

Chakra UI comes pre-configured with this lab, so you don't have to worry about installing it or setting it up.

The components from this library you will need to use are already imported from the `@chakra-ui/react` package at the top of each corresponding file.
If you don't see a component already imported, it's because you probably won't need it.
In any case, feel free to check their official [documentation](https://chakra-ui.com/docs/components) to see all the components at your disposal and their corresponding props.

#### Formik and Yup

The Formik library is already set up in the project as well, so no extra configuration is needed.
In this lab, you will be only using the `useFormik` hook from the Formik library, as well as the global `Yup` object to define the Contact Me form validation rules.

The form UI will be implemented using Chakra UI components.

Before you begin, if you run `npm start` and view the app in the browser, you'll notice that the starting React app works as is.

The app outputs a page with an empty header, 3 different full-height sections and a footer.
Every section has a different background color. The first 2 sections will be empty and the third section will contain all the UI elements for the Contact Me form.

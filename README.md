# **README - Jobly**

## **About**

_Jobly_ ( Deployed [HERE](https://legal-lip.surge.sh/) ) Jobly is a web app that allows you to search for jobs and companies, and click a box
to apply at that company.

---

## **Local Usage**

<br>

### **ENVs**:

This app does not use any Environmental Variables on the front end.

<br>

### **Testing**:

In order to run the tests for this project locally, you can use the command `npm test`. This app uses Jest for testing.

<br>

### **Formatting/Linting/Pre-Commit Hooks**:

This project uses ES-Lint as well as Prettier. I also use 4 spaces for my indentation as default.

<br>

### **Features**:

**Company Search**: Search for a company, either by scrolling through the list on the 'Companies' page, or by using the search bar on the 'Companies' page by name. These are done by Axios requests to the [back end API](https://github.com/booshja/jobly-backend).

**Company Details**: Click to a specific company, and the company name and descriptions will be listed, as well as any jobs that company currently has posted.

**Job Search**: Search for a job, either by scrolling through the list on the 'Jobs' page, or by using the search bar on the 'Jobs' page by name.

**Apply to Job**: When viewing a job, click on the "apply" button to "apply" to a job. This feature saves that a job has been applied to in the database, but as fake data was used, no "application" actually is sent to a real company.

<br>

### **APIs**:

1. [Jobly Backend](https://github.com/booshja/jobly-backend)
    > - Handles database and front end Axios calls to support React on the front end. For this project, this was provided by Springboard.

<br>

### **Tech Stack**:

-   JavaScript
-   React
    -   [Jest](https://jestjs.io/) - Testing
-   CSS
    -   [SASS](https://sass-lang.com/)
-   [Surge](https://surge.sh/) - Static Hosting
-   VSCode

---

## **Support**

Reach out to me at the following places:

-   Website: [jacobandes.dev](jacobandes.dev)
-   Twitter: [@booshja](https://twitter.com/booshja)
-   Email: [jacob.andes@gmail.com](mailto:jacob.andes@gmail.com)

---

Copyright &#169; [Jacob Andes](jacobandes.dev), 2021

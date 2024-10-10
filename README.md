# Next.js-14

<a href = "https://www.youtube.com/watch?v=eZJJ189JTks"> Link To Tutorial </a>
<br>

Date:-02/10/2024 


<br>

Enlisted below are the things I learnt today. 👇
<b

Chapter One - Getting Started 
<br>


<

Chapter Two - CS Styling 
<br>



  Introduction to different ways of styling in Next.js, including global styles, Tailwind, and CSS modules.<br>
  Adding a global CSS file to the project and using Tailwind for styling.
  Creating and using CSS modules for component-specific styling.<br>
  Using the clsx library to conditionally apply class names based on state or conditions.<Br>

<b

Chapter Three - Optimizing Fonts and Images
<br>

 Optimizing Fonts and Images in Next.js.<br>
 Importance of optimizing fonts to improve performance and user experience.<br>
 Adding a primary Google font to the project and applying it globally.<br>
 Adding a secondary font for specific elements and verifying the changes in the browser.<br>
 Optimizing images using the next/image component to automatically handle various optimizations.
<

Chapter Four - Creating Layouts and Pages
<br>


  Introduction to creating layouts and pages. Explanation of file system routing in Next.js.
  <br>
  Demonstration of creating nested routes by adding folders and 'page.tsx' files inside the 'dashboard' directory.<br>
  Creating 'customers' and 'invoices' pages within the 'dashboard' directory and verifying their functionality.<br>
  Introduction to the 'layout.tsx' file for shared UI components across multiple pages and demonstration of creating a sidebar navigation.
  <
  
  Chapter Five - Navigating Between Pages
<br>

  Introduction to navigating between pages using the Next.js 'Link' component instead of anchor tags.<br>
  Instructions on replacing anchor tags with the 'Link' component for client-side navigation.<br>
  Implementation of active link highlighting using the 'usePathname' hook and 'clsx' library.<br>
  Explanation of automatic code splitting and prefetching in Next.js for improved performance.
  
  <br
  
  Chapter Six - Setting Up Your Database
<br>


  Setting up a PostgreSQL database using Vercel, including creating a GitHub repo and linking it to Vercel.
  <br>
  Creating and connecting a PostgreSQL database on Vercel, and copying environment variables for local setup.
  <br>
  Seeding the database with initial data using a provided script and troubleshooting common issues.
  <br>
  Exploring the database through the Vercel dashboard and running SQL queries to verify data.

<

Chapter Seven - Fetching Data
<br>


  Discusses different methods for fetching data, such as APIs, server components, and SQL.
  <br>
  Emphasizes the importance of securing database queries by avoiding client-side exposure.
  <br>
  Explains how to create API endpoints in Next.js and interact with databases using SQL or 
  ORM.
  <br>
without additional API layers

Chapter Eight - Static and Dynamic Rendering
<br>


  Discusses the advantages of using React server components for asynchronous data fetching.
  <br>
  Explains the versatility and industry standard of SQL for database queries.
  <br>
  Shows how the Vercel Postgres SDK protects against SQL injections.
  <br>
  
  Chapter Nine - Streaming

  
  Discusses the advantages of using React server components for asynchronous data fetching.
  <br>
  Explains the versatility and industry standard of SQL for database queries.
  <br>
  Shows how the Vercel Postgres SDK protects against SQL injections.
  <br>


Chapter Ten - Partial Prerendering (Optional)


  Walks through fetching data for various components like the dashboard, revenue chart, and latest invoices.
  <br>
  Discusses the use of async components and how to handle fetched data in Next.js.
  <br>
  Demonstrates importing and using data fetching functions in components.
  <br>
  Highlights the importance of proper data fetching to avoid application errors.
  <br>

Chapter Eleven - Adding Search and Pagination


  The instructor introduces Chapter Eleven, focusing on adding search and pagination functionalities to the dashboard. They explain the use of Next.js APIs like `useSearchParams` and `useRouter` for managing search states and URL updates.
  <br>
  Code is pasted into the invoices page, and the instructor explains that search allows for specific invoice searches while pagination navigates between pages. The URL is updated with search parameters, and data is fetched on the server.
  <br>
  The instructor discusses the benefits of using URL search parameters, such as bookmarkable URLs and server-side rendering. They highlight three Next.js client hooks for implementing search: `useSearchParams`, `usePathname`, and `useRouter`.
  <br>
  Steps to implement search are explained, including capturing user input, updating the URL, and keeping the URL in sync with the input field. The instructor walks through adding an `onChange` event listener to the search input.

  <br>


Chapter Twelve - Mutating Data


  The instructor demonstrates logging the search term in the console and highlights how user input updates the URL. They import `useSearchParams` from Next.js navigation and create a new URL search parameters instance.
  <br>
  The instructor explains creating a page URL using `useRouter` and `usePathname`, ensuring the URL is updated without reloading the page. They emphasize keeping the URL and input in sync with default values.
  <br>
  Pagination is introduced, and the instructor explains updating the table component to reflect the search query. They navigate to the invoices page to implement these updates and ensure the table component receives the current search parameters.
  <br>
  Debouncing is introduced to optimize search functionality, preventing new database queries on every keystroke. The instructor imports the `useDebounce` library and updates the search component to use debouncing.
<br>

Chapter Thirteen - Handling Errors
<br>


  The speaker introduces the concept of handling errors gracefully using JavaScript try-catch statements and Next.js APIs.
  <br>
  They demonstrate adding try-catch to server actions and the importance of redirecting after try-catch blocks.

  The speaker covers creating an error.tsx file to handle errors in route segments and shows how to display a fallback UI.
  <br>
  Handling 404 errors with the not found function and creating a not found.tsx file is discussed. The speaker demonstrates the process and the expected UI.
  <br>


Chapter Fourteen - Improving Accessibility

<br>
  The speaker introduces the concept of improving accessibility and the importance of form validation.
  <br>
  They demonstrate using the eslint accessibility plugin to catch accessibility issues early and explain the role of semantic HTML.
  <br>
  The speaker discusses improving form accessibility with labels and focus outlines, and demonstrates adding client-side validation using the required attribute.
  <br>
  Server-side validation is covered, including updating schema with Zod and displaying errors using state. The speaker shows how to handle validation gracefully.
<br>

Chapter Fifteen - Adding Authentication
<br>


  Creating an authenticate action in actions.ts and importing the signIn function.
  <br>
  Updating the login form with useState and handling login functionality.
  <br>
  Adding logout functionality to the sidenav component.
  <br>
  Debugging errors and ensuring the authentication and logout functionalities work correctly.
  <br>

Chapter Sixteen - Adding Metadata
<br>


  Adding metadata object in the root layout to include page title and description.
  <br>
  Adding page-specific metadata for the invoices page.
  <br>
  Using title templates to avoid repeating titles across pages.
  <br>
  Encouragement to practice adding metadata to other pages.
  <br>

![Screenshot 2024-10-02 230714](https://github.com/user-attachments/assets/667656b8-b365-4c43-bb27-ccf659f52f4f)


![Screenshot 2024-10-02 230632](https://github.com/user-attachments/assets/2dcf0c57-09e6-47e5-b7e8-a9f7baf40328)


![Screenshot 2024-10-02 230814](https://github.com/user-attachments/assets/121c80de-6ee2-45d8-8fc4-4a79c0573b40)

![Screenshot 2024-10-02 230929](https://github.com/user-attachments/assets/154bd057-2d8c-45b1-9f7a-37b5bc32a26f)

![Screenshot 2024-10-02 231105](https://github.com/user-attachments/assets/e1f2d232-5bc3-48fe-a31f-ef879a4ac8ec)
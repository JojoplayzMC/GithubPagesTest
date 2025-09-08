# GitHub Pages Showcase

This repository serves as a simple demonstration of what is possible (and not possible) with a static website hosted on GitHub Pages. The site is built with a single HTML file, using Tailwind CSS for styling and vanilla JavaScript for interactivity.

## What a GitHub Pages Site Can Do

While GitHub Pages is a static hosting service, client-side technologies allow for a surprisingly wide range of features.

* **Host Static Content:** You can host standard HTML, CSS, and JavaScript files to create a complete website. This includes static text, images, and navigation bars.

* **CSS and Animations:** All standard CSS features, including transitions and complex animations, work perfectly.

* **Client-Side Interactivity:** Using JavaScript, you can create interactive elements like counters, sliders, and forms. All logic runs directly in the user's browser without needing a server.

* **Fetch Data from External APIs:** A site can make asynchronous requests to third-party APIs to fetch and display live, up-to-date data. The Bitcoin price example on the site demonstrates how a "static" page can feel dynamic.

* **Embed Third-Party Services:** For functionality that requires a server, like payment processing or email forms, you can embed code snippets from services like Stripe, PayPal, or Formspree. The website itself remains static, but it acts as a client for these external platforms.

* **Leverage LLM APIs:** A static site can call external Large Language Model APIs to generate text dynamically in the browser, showing how complex features can be offloaded to another service.

## What a GitHub Pages Site Can't Do

Since there is no server-side component, some common website functionalities are not directly supported.

* **Server-Side Logic:** You cannot run backend scripts to process data, send emails directly from a contact form, or perform other server-intensive tasks.

* **User Authentication:** A GitHub Pages site cannot manage user accounts, handle logins, or provide personalized content based on a user's identity.

* **Database or File Storage:** You cannot connect to a database or store user-uploaded files directly on the hosting service. Data that needs to be persistent must be handled by an external service, such as a cloud database like Firebase.

# Netflix Clone - Next.js




https://github.com/patelb268/netflix-clone-nextjs/assets/109325051/a3c34d2a-923c-480f-8021-0bc5504480f0




## Overview

The Netflix Clone project is a learning initiative to get hands on with NextJS framework. The goal of this project is to recreate the user interface and functionality of the popular streaming platform Netflix. Users can browse through a list of movies and TV shows, view details about each title, watch trailers, and even sign up or log in using Firebase authentication."

## Features

- **Authentication:** Users can sign up and log in to their accounts using their email and password. Firebase handles the authentication process.
- **Browse Movies and TV Shows:** Users can explore a curated list of movies and TV shows, including Netflix originals, top-rated titles, trending content, action movies, comedies, horror movies, romance movies, and documentaries.
- **Movie Details:** Clicking on a movie or TV show card displays more information about the title, including its release date, genre, original language, overview, and voting statistics.
- **Watch Trailers:** Users can watch trailers for movies and TV shows by clicking on the play button, which opens a modal with the trailer video.
- **Responsive Design:** The application is responsive and adapts to different screen sizes, providing a seamless experience across devices.
- **Stripe Integration (Upcoming Feature):** In future updates, we plan to integrate Stripe to enable users to subscribe and make payments for premium content or subscription plans.

## Tech Stack

- Next.js: A React framework for building server-side rendered applications.
- React: A JavaScript library for building user interfaces.
- Tailwind CSS: A utility-first CSS framework for rapid UI development.
- Recoil: A state management library for React applications.
- Material-UI: A popular React UI framework providing pre-built components following the Material Design guidelines.
- Heroicons: A set of free SVG icons designed by the Heroicons team.

## Getting Started

Follow these steps to set up the project on your local machine:

1. Clone the repository:

        git clone https://github.com/patelb268/netflix-clone-nextjs.git

2. Install dependencies:
   
        cd netflix-clone-nextjs
        npm install

3. Create `.env.local` in root directory:
- Replace the placeholder values in `.env.local` with your TMDB API Key.

4. Run the development server:

        npm run dev

5. Open your browser and visit `http://localhost:3000` to see the application running.

## Contributing

Contributions to this project are welcome! If you have any bug fixes, new features, or improvements to suggest, please create a pull request. We follow the "fork-and-pull" Git workflow.

# Why NextJs

1. **Server-Side Rendering (SSR):** Next.js offers robust support for server-side rendering, allowing the initial rendering of the application to occur on the server. This significantly improves performance and ensures that search engines can easily crawl and index the application for better SEO.

2. **Routing and File-Based Routing:** Next.js provides built-in routing support, making it straightforward to create pages and define routes for different parts of the application. Pages in Next.js are defined as individual files in the `pages` directory, simplifying the organization of the project.

3. **Automatic Code Splitting:** Next.js automatically performs code splitting, creating smaller chunks of JavaScript for each page. This optimizes the initial load time by loading only the necessary JavaScript for the current page, improving the overall application performance.

4. **Built-in CSS and Sass Support:** Next.js comes with built-in support for CSS modules, Sass, and various other CSS-in-JS solutions. This enables developers to style components in a modular and scoped manner, enhancing the maintainability of the codebase.

5. **Static Site Generation (SSG):** Next.js supports static site generation, allowing pages to be pre-rendered at build time. This results in even faster page loading and better SEO, making the application highly efficient and user-friendly.

6. **API Routes:** Next.js provides API routes, empowering developers to build serverless functions directly within the application. These API routes can handle backend logic or interact with databases efficiently, simplifying the backend development process.

## Learning Curve

Next.js adds some complexity compared to React alone due to its additional features and server-side rendering capabilities. However, its extensive documentation and ease of use make it accessible to developers with prior experience in React. The benefits of enhanced performance, SEO, and the seamless development environment make Next.js a compelling choice for modern web application development.

## License

This project is licensed under the BSD3 License - see the LICENSE.md file for details.


CodingPortfolio

Personal portfolio website built with Blazor WebAssembly to showcase projects, technical skills, and development experience.

The site is designed as a single-page application with smooth navigation, responsive layout, and bilingual support (English / Finnish).

Live site:
https://<your-username>.github.io/CodingPortfolio/

Overview

This portfolio serves as both:

A professional presentation of my work

A practical demonstration of modern .NET and frontend development skills

Key goals of the project:

Clean component architecture

Maintainable, scalable code structure

Production-ready deployment using GitHub Pages

Technology Stack

Blazor WebAssembly

.NET

C#

ASP.NET Core concepts

Bootstrap 5

HTML / CSS

JavaScript (interop)

GitHub Pages

Features

Single-page layout with smooth scroll navigation

Component-based architecture

Bilingual support (English / Finnish)

Dynamic hero text with animation

Project showcase with external links

Responsive design for desktop and mobile

Client-side localization using resource files

Deployed as a static site via GitHub Pages

Project Structure

main branch
Contains the full Blazor WebAssembly source code:

Components

Pages

Models

Localization resources

Styling and assets

gh-pages branch
Contains only the compiled static output (wwwroot) used by GitHub Pages.

This separation keeps the source code clean and easy to review while ensuring a stable deployment.

Localization

The application supports multiple languages using .resx resource files.

Language selection:

Stored in browser local storage

Applied on application startup

Works without server-side middleware (Blazor WASM standard approach)

Currently supported languages:

English

Finnish

Deployment

The application is published as a static site and hosted on GitHub Pages.

Deployment flow:

Blazor WebAssembly project is built in Release mode

The published wwwroot output is copied to the gh-pages branch

GitHub Pages serves the site directly from the branch root

Purpose

This project is part of my professional portfolio and is continuously improved as I develop my skills further in:

.NET ecosystem

Frontend architecture

Cloud-hosted applications

Author

Juuso Savolainen

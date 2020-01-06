Title: Overview

!!! warning
    This book is a work in progress. It is not complete and may change drastically. I'm writing it in "real-time" on a public GitHub repo in order to make it easier to share with my friends and any others who are interested.

The objective of this book is to guide the reader through making headless WordPress websites using Vue with Nuxt for server side rendering and deploying on the Zeit Now cloud platform.

# About the author

My name is Matt Watson, and I have been making custom WordPress websites since 2016. Most of those were "standard" informational websites with maybe one or two extra functionalities, such as making custom plugins to add different admin options or adding scripts to interact with third-party APIs.

One of the most interesting projects I have worked on involved using WordPress as a central source of data for different websites, running on different domains, with different designs. There were many challenges, but I learned a lot. Over time, I have decided it would be fun and hopefully useful to others to write an exhaustive guide on how to build these types of websites.

# What we're building

Before we begin, let's nail down exactly what we're going to build. I have tried to make the example project as real-world as possible with plenty of details and information for troubleshooting potenntial problems.

We're going to build three websites that depend on data from one WordPress instance and use Node/JavaScript AJAX requests to the WordPress REST API for rendering the frontend.


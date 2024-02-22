# React with Rails using Webpack-CLI

## Overview

This project demonstrates the seamless integration of React.js into a Ruby on Rails application using Webpack-CLI. By combining the efficiency of Rails with the dynamic user interfaces enabled by React, you can build modern and feature-rich web applications.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed on your machine:

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/get-npm)
- [Ruby on Rails](https://rubyonrails.org/)

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-project.git
   cd your-project
   ```

2. **Install Ruby gems:**

   ```bash
   bundle install
   ```

3. **Install Node.js packages:**

   ```bash
   npm install
   ```

4. **Run migrations:**

   ```bash
   rails db:migrate
   ```

## Development

1. **Start the Rails server:**

   ```bash
   rails server
   ```

2. **Start the Webpack development server:**

   ```bash
   npx webpack --mode=development --watch
   ```

3. **Visit [http://localhost:3000](http://localhost:3000) to see your React with Rails application in action.**

## Build for Production

To build your application for production, run:

```bash
npx webpack --mode=production
```

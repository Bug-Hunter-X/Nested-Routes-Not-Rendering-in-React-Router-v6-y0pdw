# React Router v6 Nested Route Rendering Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router v6.  The problem involves nested routes failing to render their components, even when the parent route renders correctly. This example showcases the issue and its solution.

## Problem

The `bug.js` file contains a simple React Router v6 setup with nested routes.  Despite the routes being correctly defined, the nested components do not render.  The parent route renders without issue.

## Solution

The `bugSolution.js` file provides a corrected version. The issue is resolved by ensuring that the `Routes` component is properly nested within the parent route. This allows React Router to correctly match and render the nested routes.

## Setup

1. Clone this repository.
2. Navigate to the directory in your terminal.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.

You'll observe that the nested route in `bug.js` does not render, while the nested route in `bugSolution.js` does.
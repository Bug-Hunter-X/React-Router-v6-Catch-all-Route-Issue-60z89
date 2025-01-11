# React Router v6 Catch-all Route Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router v6.  The catch-all route is intended to handle any unmatched routes, however, it's not functioning correctly in this example.  The application always defaults to the home route, even when navigating to non-existent paths.

## Problem
The provided `App.js` shows a simple React Router setup with routes for '/', '/about', and a catch-all route for all other paths ('/*'). However, instead of rendering the 'NotFound' component for non-existent paths, it renders the 'Home' component.

## Solution
The solution provided in `AppSolution.js` addresses this issue.

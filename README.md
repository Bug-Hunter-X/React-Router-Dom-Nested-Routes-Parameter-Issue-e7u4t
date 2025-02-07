# React Router Dom Nested Routes Parameter Issue

This repository demonstrates a bug encountered when using nested routes and parameters in React Router Dom v6.  The issue causes unexpected routing behavior, resulting in incorrect component rendering or 404 errors.  The solution provided resolves the problem by correctly handling parameter passing and nested route definitions.

## Problem Description

When attempting to access nested routes with parameters, the application fails to correctly interpret and utilize these parameters, leading to the incorrect components being displayed or 404 errors.

## Solution

The solution involves carefully reviewing the structure of the nested routes and how parameters are passed between them. Correctly using the `useParams` hook and defining routes to handle parameters effectively resolves the unexpected behavior. 

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install the dependencies.
4. Run `npm start` to start the development server.
5. Observe the incorrect rendering behavior or 404 errors.
6.  Check out the `solution` branch to see the corrected code.
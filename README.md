# React Router Catch-All Route Issue

This repository demonstrates a common issue with React Router's catch-all route (`path="/*"`).  Even when navigating to paths not explicitly defined, the catch-all route is not triggered.

## Problem
The provided `App.js` shows a basic React Router setup.  The expectation is that the `NotFound` component should render when navigating to any path that isn't "/" or "/about". However, this doesn't happen.

## Solution
The solution, provided in `AppSolution.js`, involves moving the catch-all route to the end of the `Routes` component.
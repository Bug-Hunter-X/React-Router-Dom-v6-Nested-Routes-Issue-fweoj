# React Router Dom v6 Nested Routes Issue

This repository demonstrates a common issue encountered when nesting routes in React Router v6.  The nested routes fail to render correctly, resulting in a blank screen.

## Problem
When routes are nested within a component (e.g., a layout component), the nested routes might not render properly. This is particularly true if the parent component does not directly contain the `<Routes>` component.  The issue is rooted in how React Router v6 handles route matching and rendering within the component tree.
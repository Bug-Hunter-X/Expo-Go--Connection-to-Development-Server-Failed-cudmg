# Expo Go Development Server Connection Error

This repository demonstrates a common issue when using Expo Go: failure to connect to the local development server.  The `bug.js` file shows a typical React Native application setup that may cause connection issues if the development server isn't properly configured.  The solution, in `bugSolution.js`, provides fixes and explanations.

**Problem:**

Expo Go displays an error stating it can't connect to the development server, usually resulting in a blank screen or a generic network error.

**Causes:**

* Incorrectly configured development server (port, tunneling, etc.).
* Network issues (firewall blocking connection, incorrect IP address).
* Problems with the Expo CLI or development environment.

**Solution:**

The `bugSolution.js` file demonstrates how to properly set up the development server and troubleshoot common connection problems.
# React Native Native Module Linking Errors

This repository demonstrates a common yet often tricky bug in React Native: native module linking errors.  These errors typically occur when a library requiring native code (e.g., react-native-camera, react-native-maps) isn't properly linked to your project.  The resulting error messages can be cryptic and difficult to diagnose.

The `bug.js` file showcases a project with a faulty native module link, illustrating how the problem manifests. The `bugSolution.js` file provides the solution.

## Reproducing the Bug

1. Clone this repository.
2. Follow the instructions in `bug.js` to see the error. 
3. Review the solution in `bugSolution.js` to fix the issue.

## Solution

The solution involves correctly linking native modules, which may include steps like running post-installation scripts, checking native module dependencies, cleaning build folders and rebuilding.  The specific solution will depend on the library involved but often involves running the library's linking steps.
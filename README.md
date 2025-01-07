# Expo CLI Error: Uncommon Module Incompatibility

This repository demonstrates a bug related to module incompatibility when using the Expo CLI in a managed workflow.  The problem occurs when attempting to use libraries that aren't fully compatible with Expo's managed workflow, leading to runtime errors or missing module errors. The solution involves either finding an Expo-compatible alternative, using the bare workflow, or carefully adapting the library to function within Expo's constraints.  See the files `bug.js` and `bugSolution.js` for code examples.

## Setup

1. Clone this repository.
2. Navigate to the directory.
3. Run `expo install <necessary_packages>` 
4. Run `expo start`

## Bug Report

The `bug.js` file shows the code that causes the issue.  It attempts to use a hypothetical library, `uncommon-module`, which isn't designed for Expo. This leads to a runtime error or missing module error.

## Solution

The `bugSolution.js` file shows a potential solution, which might include finding an Expo-compatible alternative or modifying the code to work within Expo's sandbox.
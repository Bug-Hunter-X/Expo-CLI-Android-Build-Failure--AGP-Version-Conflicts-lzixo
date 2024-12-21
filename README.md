# Expo CLI Android Build Failure: AGP Version Conflicts

This repository demonstrates a common error encountered when building Android apps using the Expo CLI. The issue stems from incompatibilities between the Android Gradle Plugin (AGP) version used in the Expo project and its dependencies.  This can manifest in various ways, often resulting in build failures with confusing error messages.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to build the Android app using `expo build:android`.

## Solution

The solution involves carefully managing AGP versions and ensuring compatibility across all dependencies.  The `bugSolution.js` file illustrates a potential fix.  Note that specific solutions may vary depending on the project's dependencies and the exact error messages encountered.  Consult the Expo documentation for more detailed guidance on managing AGP versions and resolving dependency conflicts. 
# Expo prebuild: SDK Version Mismatch

This repository demonstrates a common error encountered when using `expo prebuild` with EAS Build. The error occurs due to a mismatch between the Expo SDK version in your project and the version supported by EAS Build or your local Expo CLI.  The issue is that the error message isn't always explicit about the conflicting SDK versions. 

The `expoPrebuildError.js` file shows an example project structure (and manifest) where this error might occur. The solution (`expoPrebuildSolution.js`) demonstrates how to resolve the version discrepancy and successfully use `expo prebuild`.

## Steps to Reproduce the Error

1.  Clone this repository.
2.  Inspect `app.json` or `expo.json` for an Expo SDK version.
3.  Try running `expo prebuild --clean` (or equivalent command in your workflow). You'll likely encounter an error. 
4.  Follow the solution steps.
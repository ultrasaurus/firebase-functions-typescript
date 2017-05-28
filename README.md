## Cloud Functions for Firebase: getting started with TypeScript

This is an example Firebase project for using TypeScript with 
[Cloud Functions for Firebase](https://firebase.google.com/products/functions)

Pre-requistes:

```
npm install -g firebase-tools
```

Also, I highly recommend using [yarn](https://yarnpkg.com), 
which locks the versions of your npm modules.  I also like to use 
[homebrew](https://brew.sh/) to install dependencies on the Mac.  These aren't
required for Cloud Functions or Firebase, but are used in the instructions.

```
brew install yarn
```


Steps:

1. Create a project in the [Firebase Console](https://console.firebase.google.com/)
in this example, I called mine `functions-typescript`
2. Create a directory for your project and do the following steps inside that
directory, for example:
   ``` 
    mkdir firebase-functions-typescript
    cd firebase-functions-typescript
   ```
2. 
# Create T3 App

This is a [T3 Stack](https://create.t3.gg/) project bootstrapped with `create-t3-app`.

## To get rid of the Daisy UI error message:

- Go to your DaisyUI file in NodeModules
- Create a new file named index.d.ts
- put declare module 'daisyui'; inside the file
- this should fix that error message for type problems in DaisyUI

## Running app locally for the first time: 
 
- Clone the repo 
- create a .env file in the main directory 
- copy the contents of .env.example and paste them into the new .env
- run 'npm install' 
- should be all set??? 

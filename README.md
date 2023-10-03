# Google Docs Clone

## Description

A Google Docs Clone project written in Typescript which allows many people to edit a document at the same time.

## Application structure

### Server side

Basic Socket.io server which uses MongoDB to save data, synchronizes data between multiple client opening the same document.

### Client side

React app with Quill text editor.

## Guide

To run the project, follow the instruction below:

change mongoDB url (index.ts)

![image](https://github.com/douglas85rj/Google-Docs-Clone/assets/19936447/2f6e6456-03d2-48c0-bf52-6f163a834ca3)

### Run the server

    cd server
    yarn install
    yarn start:dev

### Run the client

    cd client
    yarn install
    yarn start

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

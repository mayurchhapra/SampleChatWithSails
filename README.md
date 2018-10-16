# SailsChat Application

> This is a simple chat application written in sailsjs to demonstrate public and private chat using multiple windows in the browser.

## What it is

sailsChat is a multi-user chat app that demonstrates some new features in Sails v0.10:

* Low-level socket methods using `sails.sockets`
* New / reworked PubSub methods
* Auto-generated routes and actions (blueprints) for associations

The app features both private messages between two users, and public (multi-user) chatrooms, all updated in real time.  And all in under 100 lines of backend code (using the strictest method of line-counting :) )

## Installing
Clone the repo into a new directory, `npm install` and `sails lift`, and you're off!

## Using

Browse to `http://localhost:1337` to view the app in all its glory.  A new user will be created for you automatically.  Of course, a chat app isn't much fun with just one user, so open another tab or browser window to the same address to pop up a new user.  Then use the "Send private message" button to communicate directly between two users, or start a new chat room to chat with a group!

## More

On the [wiki](https://github.com/balderdashy/sailsChat/wiki).

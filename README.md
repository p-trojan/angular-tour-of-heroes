# Tour of Heroes

This is a copy of Part 6 of Angular tutorial - Tour of Heroes (https://angular.io/tutorial/tour-of-heroes/toh-pt6)

I am using this project only as for learning purposes, I needed something that has simple domain and REST API. This is sufficient to serve as a base for developing backend app in Scala.

I am using node 16.13.0 and npm 8.1.0. 

To build and run this project use `ng serve` or `ng serve --open`

To run this project on localhost with backend of any kind CORS has to be enabled.
This is done by adding `proxy.conf.json` to `src` folder and editing `angular.json`. I followed these instructions: https://medium.com/weekly-webtips/do-you-know-how-to-resolve-cors-issues-in-angular-9d818474825f

To connect to backend app, just remove/comment `InMemoryDatabase` from `app.module.ts`. 
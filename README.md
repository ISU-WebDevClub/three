# three
Showcasing a basic web project with a 3D graphics library.

[Docs and examples](https://threejs.org/)

## How to run it
There are several ways to run this example. The easiest way is to open the file
`index.html` directly in a browser. This works for most simple websites.

You can also run a local web server. From inside the project directory, run the
following (you will need [Node.js](https://nodejs.org)):

```shell
npm install http-server -g
http-server . -p 8000
```

Then go to http://localhost:8000 in your browser.

## Some things to try
One way to get experience with web development is to dive right in. Come up with
something that you want to make or do, and with the help of outside resources
and your problem solving skills, keep trying until it works. You will learn a
lot when things don't work.

For this project, you could try:

- Moving the JavaScript in `index.html` to a separate file
- Adding more shapes to the scene
- Making the scene take up only part of the website so that you could add some
  text on the side
- Deleting the `three.js` file in `js/` and instead importing it using the npm
  package manager
  - What might be the benefits of this?

## License
MIT

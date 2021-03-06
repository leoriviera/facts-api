# Facts API

A RESTful API which returns useless, random facts gathered from all over the Internet.

The `facts-api` project provides a website which serves random facts, accessible at `/`, along with a JSON endpoint at `/random`. Users can also find a particular fact by its index using `/facts/:index`.

![Screenshot of Fact #1734](https://user-images.githubusercontent.com/11467778/109699389-6da17a80-7b88-11eb-9c6b-79e725bc244f.png)

Feel free to contribute your own facts by making a pull request! If you notice anything incorrect, then simply create an issue. You're also able to clone this repo and use it to serve any niche facts you please!

This TypeScript project uses [Express](https://expressjs.com/) to serve requests and [Pug](https://pugjs.org/api/getting-started.html) to render the website.

To run this project,
- Clone the repository using `git clone https://github.com/leoriviera/thefactspace.git facts`,
- Enter the folder using `cd facts` and install dependencies using `npm install`,
- Build the project using `npm run build`,
- Run on `http://localhost:3000` using `node src/index.js`.

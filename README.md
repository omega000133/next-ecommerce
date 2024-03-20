<h1 align="center">Ecommerce made with Next.js</h1>

> This project was made to show a full ecommerce plataform made with Next.js and Nextjs Serverless functions to build the backend, using Apollo Server and Apollo Client to GraphQL.

---

# :pushpin: Table of Contents

* [Demo Website](#eyes-demo-website)
* [Technologies](#computer-technologies)
* [Features](#rocket-features)
* [How to run](#construction_worker-how-to-run)
* [Found a bug? Missing a specific feature?](#bug-issues)
* [Contributing](#tada-contributing)
* [License](#closed_book-license)

## 📥 Layout available at:
<p align="center">
    <a title="Acess Figma Web" href="https://www.figma.com/file/fDLkOXAz4k3ILWb8PoDivJZF/E-Commerce-Quantum?node-id=0%3A1">
        <img alt="Direct Download" src="https://img.shields.io/badge/Acess Figma Web-black?style=flat-square&logo=figma&logoColor=red" width="200px" />
    </a>
</p>

# :eyes: Demo Website
The demo website can be missing some features, clone and run the project to a full experience. <br>
👉  demo: https://quantum-ecommerce.now.sh/

# :computer: Technologies
This project was made using the follow technologies:

* [Next.js](https://nextjs.org/) - To SSR and routes control     
* [GraphQL](https://graphql.org/) - To query language     
* [Apollo](https://www.apollographql.com/) - To graphql server and client       
* [Knex](https://knexjs.org/) - ORM   
* [Vercel](https://vercel.com/) - To deploy website     

# :rocket: Features

- Authentication with Cookies Sessions.
- Reset Password using email
- List Products
- Filter products by Category
- Sort list of products
- Live search
- Add products to Wishlist
- Add products to Cart
- Checkout page
- Payment with Paypal
- Review Products
  
# :construction_worker: How to run
**You need to install [Node.js](https://nodejs.org/en/download/) and [Yarn](https://yarnpkg.com/) first, then:**

### Rename env file
Rename `.env.local-exemple` to `.env.local`
### Install Dependencies
```bash
yarn install
```
### Set up database
```bash
# Create DB using migrations
yarn knex:migrate

# Run seeds to populate database
yarn knex:seed 
```
### Run Aplication
```bash 
yarn dev 
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
<br>
<br>
Open [http://localhost:3000/api/graphql](http://localhost:3000/api/graphql) with your browser to run queries or to see docs of API.


# :bug: Issues

Feel free to **file a new issue** with a respective title and description on the the [Next.Js Ecommerce](https://github.com/RafaelGoulartB/next-ecommerce/issues) repository. If you already found a solution to your problem, **i would love to review your pull request**!


---


[⬆ Back to Top](#pushpin-table-of-contents)



# :closed_book: License

Released in 2020.


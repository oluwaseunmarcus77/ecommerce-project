This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

## First, run the development server:

```bash
npm run dev
```

In your terminal.

## Seconnd, open the development server:

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
And to view the Admin Pannel, open [http://localhost:3000/admin/dashboard] (http://localhost:3000/admin/dashboard) to view.

## Third, creating database:

Sign up/Login to MongoDB Atlas: If you don't have an account, sign up for MongoDB Atlas. If you already have one, log in.

Create a New Project: Once logged in, create a new project. Give it a name that identifies your project.

Create a Cluster:

Inside your project, click on "Build a New Cluster".
Choose your preferred cloud provider, region, cluster tier (e.g., shared, dedicated), and additional settings like the version of MongoDB.
Configure your cluster settings like cluster name, cluster tier, and additional settings if necessary.
Click on "Create Cluster" and wait for it to deploy. This might take a few minutes.
Whitelist Your IP Address:

In the Security section of your cluster, click on "IP Whitelist".
Add your current IP address to allow connections from your computer.

Create a Database User:

In the Security section, click on "Database Access".
Click on "Add New Database User" and create a username and password with appropriate privileges.
Get Connection String:

In the Clusters section, click on "Connect" for your cluster.
Choose "Drivers".
inside drivers, check the section 2 for how to install mongodb in your terminal then come back to Drivers after installing it.
Copy the connection string. It should look something like this:
mongodb+srv://<username>:<password>@<cluster>/<database>.

Now go back to the Repository and look for ".env.local" directory and replace the MONGODB URI string with the connection string you copied (mongodb+srv://<username>:<password>@<cluster>/<database>) and also replace the the "username" and "password" with actual username and password in the database and save.

## Fourth, run the application:

You can start checking out the main web page [http://localhost:3000] by adding to cart and you can also add more products by going to the admin pannel [http://localhost:3000/admin/dashboard] (this will request a gmail account).
In the admin pannel side bar, You will find Dashboard button. In Dashboard, You will be able to view all the products in the main web page [http://localhost:3000].
To add more product, check the side bar for Products button and click on it, it's right under the Dashboard button.
The Products button will show a Formlike view page, in this page you will see a button with "Choose file" on it, click on it to add a product image file from your computer file explorer or if you don't have any image files, you can get images right from this repository by checking the "Public" directory to view all the images. you can save them to your computer.
After selecting an image, click on open in the file explorer and wait for it to load on the Product page. wait until it's fully loaded and give the product a name, category and price in the form then click on "Add" button.
This will upload the product with name and price, You can view the dashboard in the admin pannel for result and you can also return to the main page [http://localhost:3000] and refresh to view the added product.

Also check the database collections for results.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

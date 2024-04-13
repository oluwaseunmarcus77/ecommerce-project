This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

To initiate the development server, follow these steps:

Save the code to your local machine.

Open your terminal and navigate to the directory where you saved the code.

Run the following command:

"npm run dev"

Accessing the Development Server:

After starting the development server, you can access it through your browser:

Open http://localhost:3000 to view the main application.
Navigate to http://localhost:3000/admin/dashboard to access the Admin Panel.
Setting Up the Database:
Follow these steps to set up the database:

Sign up or log in to MongoDB Atlas, a cloud-based database service.

Create a new project and specify its name.

Build a new cluster within your project, choosing your preferred settings.

Whitelist your current IP address to allow connections from your computer.

Create a database user with appropriate privileges.

Obtain the connection string for your cluster.

Open your terminal and run npm install mongodb if you haven't already.
Access your cluster's connection string in the MongoDB Atlas dashboard.
Update the .env.local file in your repository with the obtained connection string.

Running the Application:
Once the setup is complete, you can run the application:

Explore the main web page at [http://localhost:3000], where you can add products to the cart.
Access the Admin Panel at [http://localhost:3000/admin/dashboard] (Gmail account required).
In the Admin Panel, navigate to the Dashboard to view all products.
To add new products, access the Products page and upload product images, specify details, and click "Add".
Go to the Dashboard to view the added product and also refresh the main web page (localhost:3000) to view the update

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

# JSON Server on Vercel

[![Made by AI](https://img.shields.io/badge/Made%20by-AI-lightgrey?style=for-the-badge)](https://github.com/mefengl/made-by-ai)

This repository is a template for deploying a JSON Server on Vercel. JSON Server provides a quick and easy way to set up a RESTful API for development and prototyping purposes.

## Features

- Deploy a RESTful API in minutes
- Perform CRUD operations on your data
- Easily extendable and customizable
- Auto-generated API documentation

## Prerequisites

- Node.js (version 12 or later)
- npm (Node Package Manager)
- Vercel CLI

## Getting Started

To get started, follow these steps:

1. Click the "Use this template" button at the top of this GitHub repository to create a new repository with this template.

2. Clone your new repository to your local machine:

```shell
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

3. Install the JSON Server package as a dependency:

```shell
npm install
```

4. Start the JSON Server locally by running the following command:

```shell
npm start
```


5. Your local JSON Server will be running at `http://localhost:3000`. You can access your API endpoints, such as `http://localhost:3000/posts`.

6. Deploy your JSON Server to Vercel by running the following command:

```shell
vercel
```


7. Follow the prompts to complete the deployment. You'll receive a unique URL for your deployed JSON Server, which you can use to access your API endpoints.

## Usage

Once your JSON Server is deployed, you can interact with your API using different HTTP methods to perform CRUD operations on your data. Here are some examples:

1. Get all posts: Send a GET request to `https://your-unique-url.vercel.app/posts`.
2. Get a specific post: Send a GET request to `https://your-unique-url.vercel.app/posts/1`.
3. Create a new post: Send a POST request to `https://your-unique-url.vercel.app/posts` with the post data in the request body.
4. Update a post: Send a PUT request to `https://your-unique-url.vercel.app/posts/1` with the updated post data in the request body.
5. Delete a post: Send a DELETE request to `https://your-unique-url.vercel.app/posts/1`.

Please note that the deployed JSON server on Vercel is a read-only server. Any changes made to the data using POST, PUT, or DELETE requests will not persist across deployments.

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.

# StudyCrew

Welcome to StudyCrew's GitHub repository! This repository serves as the central hub for our project's source code, assets, and content.

## Introduction

StudyCrew is a dedicated online platform designed to foster accessible, collaborative, and engaging educational experiences. We're committed to making learning more inclusive and interactive. If you have any questions or inquiries, feel free to reach out to us at [development@studycrew.world](mailto:development@studycrew.world).

## Getting Started

To begin, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/studycrew/studycrew
```

### Setting up MongoDB:
StudyCrew uses MongoDB as its primary data storage. Ensure you have a local instance or a free MongoDB Atlas subscription. Set your connection string in the .env.example file:

```
MONGODB_URL=[YOUR CONNECTION STRING HERE]
```

### Setting up Authentication with Clerk:
For authentication, StudyCrew utilizes Clerk. To set up your local instance, you'll need a Clerk account. Once you've created an account, obtain your credentials and place them in the env.local file:

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=[YOUR PUBLISHABLE KEY FROM CLERK]
CLERK_SECRET_KEY=[YOUR SECRET KEY FROM CLERK]
```

### Running the project locally:

To run the project locally, you need to:

1. 

1. `pnpm i` the required dependencies.

1. `pnpm build-dev` to launch the development server.

## Contributing
Interested in contributing? Check out our contribution guide to learn how you can get involved and contribute to StudyCrew's development.

## Join Our Community
Join our community on Discord for discussions, support, and more! Join our Discord!

Thank you for exploring our repository! We're excited to welcome you to our community.
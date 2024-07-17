# Personal GPT using Next.js

This repository contains the code for a personal version of GPT developed using Next.js. This project leverages the OpenAI GPT model to create an interactive chat application.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [License](#license)

## Introduction

This project aims to create a personal version of GPT using the Next.js framework. It provides a user-friendly interface for interacting with the GPT model, enabling dynamic and intelligent conversations.

## Features

- Interactive chat interface
- Easy integration with OpenAI GPT models
- Real-time responses
- Customizable and extendable

## Installation

Follow these steps to set up and run the project locally.

### Prerequisites

Ensure you have the following installed:

- Node.js (>= 12.x)
- npm or yarn

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies:**

   Using npm:

   ```bash
   npm install
   ```

   Using yarn:

   ```bash
   yarn install
   ```

3. **Set up environment variables:**

   Create a `.env.local` file in the root directory and add your OpenAI API key:

   ```
   OPENAI_API_KEY=XXXXXXXX
   AUTH_SECRET=XXXXXXXX (32 characters)
   KV_URL=XXXXXXXX
   KV_REST_API_URL=XXXXXXXX
   KV_REST_API_TOKEN=XXXXXXXX
   KV_REST_API_READ_ONLY_TOKEN=XXXXXXXX
   ```

4. **Run the development server:**

   Using npm:

   ```bash
   npm run dev
   ```

   Using yarn:

   ```bash
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

Once the development server is running, you can interact with your personal GPT through the web interface. Simply type your messages, and the model will respond in real-time.

## Technologies

This project is built using the following technologies:

- [Next.js](https://nextjs.org/): A React framework for server-side rendering and static site generation.
- [OpenAI GPT](https://openai.com/): The language model powering the chat functionality.
- [Vercel KV](https://vercel.com/docs/storage/vercel-kv/): The database used to store chats and user records.
- [NextAuth](https://next-auth.js.org/getting-started/introduction/): The library used for user authentication.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

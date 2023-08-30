# OpenAI API Quickstart - Node.js Example App

![Pet Icon](pet-icon.png)

This repository contains an example pet name generator app developed for the OpenAI API quickstart tutorial. The app is built using the Next.js framework with React. Follow the instructions below to set up the app and start generating creative pet names!

## Table of Contents

- [Setup](#setup)
- [Usage](#usage)
- [Tutorial](#tutorial)

## Setup

Before you begin, ensure that you have Node.js installed (version >= 14.6.0 is required). If not, you can download and install it from [here](https://nodejs.org/).

### Clone the Repository

```bash
$ git clone https://github.com/yourusername/openai-quickstart-node.git
```

### Navigate to the Project Directory

```bash
$ cd openai-quickstart-node
```

### Install Dependencies

```bash
$ npm install
```

### Configure Environment Variables

1. Make a copy of the example environment variables file:
   
   On Linux systems:
   ```bash
   $ cp .env.example .env
   ```
   
   On Windows:
   ```bash
   $ copy .env.example .env
   ```

2. Open the newly created `.env` file and add your OpenAI API key.

### Run the App

```bash
$ npm run dev
```

You can now access the app by visiting [http://localhost:3000](http://localhost:3000) in your web browser.

## Usage

1. Once the app is running, you'll see a text box that says "Name My Pet" along with an icon of a dog.

2. Enter your pet-related keywords or preferences into the text box and click the submit button.

3. The app will use the OpenAI API to generate creative and fun pet name suggestions based on your input.

## Tutorial

For a more detailed explanation of the concepts and steps behind this example app, be sure to check out the [tutorial](link-to-tutorial) that accompanies this repository.

Feel free to explore, modify, and adapt this example app as a starting point for your own projects using the OpenAI API. Happy coding!

---

**Note:** This example app is developed as part of the OpenAI API quickstart tutorial and is meant for educational purposes. Make sure to review OpenAI's usage policies and guidelines before using the API extensively in your own applications.

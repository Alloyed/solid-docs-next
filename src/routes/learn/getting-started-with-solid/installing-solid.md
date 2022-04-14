<title>Installing Solid</title>

There are a number of ways to get up-and-running with Solid.

## In the browser

By far the easiest way to get started with Solid is to try it online. There are two ways to get started:

1. **Use the Solid playground.** The playground is a browser-based REPL that already has Solid loaded up and ready to go. [Use the Solid playground](#)

2. **Use the Solid CodeSandbox starters.** CodeSandbox is a web applicatoin that provides an interface similar to Visual Studio Code. You can choose from either the [JavaScript starter](#) or the [Typescript starter](#).

## In your local environment

You can run Solid in your local development environment if you have Node.js installed. If you don't have Node installed, you can install it for free at [nodejs.org](https://nodejs.org).

Assuming you have Node installed, we recommend using one of our [Vite templates](https://github.com/solidjs/templates) by running these commands in your terminal:

### JavaScript template

```bash
npx degit solidjs/templates/js my-app
cd my-app
npm install # or yarn or pnpm
npm run dev # or yarn or pnpm
```

### Typescript template

```bash
npx degit solidjs/templates/ts my-app
cd my-app
npm install # or yarn or pnpm
npm run dev # or yarn or pnpm
```

If everything has been installed correctly, the final command should start the demo application on port 3000. Navigate to [https://localhost:3000](https://localhost:3000) and you should see the following demo app:

**[Insert demo app screenshot]**
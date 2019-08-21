# Munch

> Component to display business page header for munch, a web-based restaurant review platform.

## Related Projects

  - https://github.com/munch/gallery
  - https://github.com/munch/reservation
  - https://github.com/munch/popular


### Installing Dependencies

From within the root directory:

```sh
npm install -g webpack
npm install
```

## Usage

> The master branch has been updated to reflect the code for the final optimized and deployed Docker container that is on AWS EC2. Check out the other branches to see the various iterations that this project went through over the course of development!

  - Seed the Mongo database and start the Express server by running the command 'npm start' in the root directory
  - Ensure that your Express server is connected to the Mongo database
  - Create a Webpack bundle by running the command 'npm run react-dev' in the root directory
  - Navigate to localhost:3003/header/* , replacing the * with a number from 1-100 to view the details for that restaurant
  - Run tests by running the command 'npm run test' to view test coverage

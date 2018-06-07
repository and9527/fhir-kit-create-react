# FHIRKit Create React App

A [create-react-app](https://github.com/facebook/create-react-app) template using
the [FHIRKit Client](https://github.com/Vermonster/fhir-kit-client) with an Express.js server.

View an example deployment of the app at [https://fhir-kit-react.herokuapp.com](http://fhir-kit-react.herokuapp.com/).

## Installing

```
$ yarn global add create-react-app
$ yarn global add craftool
```

## Using the template

```
 $ craft MyFHIRKitApp https://github.com/Vermonster/fhir-kit-create-react/archive/master.zip

 $ cd MyFHIRKitApp
 $ yarn install-kit
```

## Running the app

`yarn start` will use [Concurrently](https://github.com/kimmobrunfeldt/concurrently) to run `server/main.js` and `react-scripts start`. The app starts out with an example
of a patient name search using FHIRKit Client surfaced to a React app using [Ant Design](https://github.com/ant-design/ant-design) UI components.

## Deployment

Update the react build with `yarn build`. To deploy to Heroku, for example, push the server directory with:

```
$ git subtree push --prefix server heroku master
```

## License

MIT

Copyright (c) 2018 Vermonster LLC

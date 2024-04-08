# red-hat-developer-hub-customization-provider

This is an example Express server, which serves an API.

To run:

    npm install
    npm start

The app will now start on <http://localhost:8080>

If you hit <http://localhost:8080> you'll get a sample data for home:

If you hit <http://localhost:8080/tech-radar> you'll get a sample data for tech radar:

## Deploy it on OpenShift

Can use oc CLI as below or use import from git flow from OpenShift Developer Console

    oc new-app https://github.com/redhat-developer/red-hat-developer-hub-customization-provider
    oc expose svc/red-hat-developer-hub-customization-provider

## Acknowledgements

This app was created using the [Express application generator][expressgen].

[express]: https://expressjs.com/
[expressgen]: https://expressjs.com/en/starter/generator.html

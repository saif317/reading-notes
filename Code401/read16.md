# AWS: Cloud Servers

## Describe the Web-Request-Response-Cycle

- A user opens his browser, types in a URL, and presses Enter.

- When a user presses Enter, the browser makes a request for that URL.

- The request hits the Rails router (config/routes.rb). The router maps the URL to the correct controller and action to handle the request.

- The action receives the request and passes it on to the view.

- The view renders the page as HTML.

- The controller sends the HTML back to the browser. The page loads and the user sees it.

## What does it mean to “deploy” an application?

he process of installing, configuring, and enabling a specific application or set of applications, usually through an application manager (app manager) or software management system, to a specific URL on a server.

## Server

computers that run services to serve the needs of other computers

## Pub/Sub

enables you to create systems of event producers and consumers, called publishers and subscribers. Publishers communicate with subscribers asynchronously by broadcasting events

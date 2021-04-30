# The Art of Microfrontends

"The Art of Microfrontends", published by Packt.

Order the book [at Amazon](https://www.amazon.com/dp/1800563566/).

## Cloning the Repository

This repository contains all repositories with sample codes. These repositories have been included as Git modules. In order to check them out at clone you should add the `--recurse-submodules` flag:

```sh
git clone --recurse-submodules https://github.com/PacktPublishing/The-Art-of-Microfrontends.git
```

## Using the Code

Each directory containing a sample repository has a README file with instructions on what is necessary and how to run the code.

For the samples of chapter 7 (server-side composition) and chapter 11 (siteless UIs) the code has been split across multiple repositories. This was done to illustrate the distributed nature of microfrontends in general, and in particular of the given approaches.

The recommendation here would be to start with the gateway (chapter 7) and app shell (chapter 11) before running the MF repositories. In case of chapter 11 you'll also need to run the feed server.

Pretty much all samples have been created exclusively using web technologies such as HTML and JavaScript. For the edge-side composition example (chapter 8) a *Dockerfile* running an nginx server was added.

If you'll encounter any problem or have some improvement in mind then don't hesitate to open an [issue on GitHub](https://github.com/PacktPublishing/The-Art-of-Microfrontends/issues).

## Available Samples

* Chapter 5 - Types of Microfrontends
  * [Direct build integration](./05-pipeline)
  * [Looser coupling via lookup table](./05-server-discover)
* Chapter 6 - The Web Approach
  * [Pattern example](./06-web-approach)
* Chapter 7 - Server-Side Composition
  * [Gateway to orchstrate MFs](./07-gateway)
  * [Red MF bringing product page](./07-red)
  * [Blue MF bringing purchase ability](./07-blue)
  * [Green MF bringing recommendations](./07-green)
* Chapter 8 - Edge-Side Composition
  * [Pattern example](./08-edge-side-composition)
* Chapter 9 - Client-Side Compositionv
  * [Pattern example](./09-client-side-composition)
* Chapter 10 - SPA Composition
  * [Pattern example](./10-spa-composition)
* Chapter 11 - Siteless UIs
  * [App Shell to orchestrate MFs](./11-app-shell)
  * [Feed server to dynamically provision MFs](./11-service-feed)
  * [Balance MF bringing the balance sheet](./12-frontend-balance)
  * [Settings MF bringing the settings dialog](./12-frontend-settings)
  * [Tax MF offering an extension for the balance sheet](./12-frontend-tax)

# A Multi-Framework Monorepo

This [Monorepo](./ReadAboutMonoRepo.md) will serve a few purposes.

- Each root module will correspond to a single [Web API](https://developer.mozilla.org/en-US/docs/Web/API)

- Each _Web API_ module will be a [Higher Order Component](https://en.wikipedia.org/wiki/Higher-order_programming) which implements the [Proxy Pattern](http://www.blackwasp.co.uk/Proxy.aspx)

- Each module which calls a Proxy command will have an optional ability to create side effects 
          - logging
          - auditing
          - ...tbd

- Finally, components will be created in vanilla javascript modules as well as the following frameworks:
    - [For MVP]:
      - `.mjs`
      - `react`
      - `vue`
      - `svelte`

- The end result will allow for easier implementation of _microfrontends_.
  - [If needed](https://www.angulararchitects.io/aktuelles/a-software-architects-approach-towards/)
  - More information & best practices:
    - [Micro-Frontends](https://micro-frontends.org/)
      - [Even More](https://micro-frontends.org/#additional-resources)
      - [Techniques](https://www.thoughtworks.com/radar/techniques/micro-frontends)
      - [Martin Fowler](https://martinfowler.com/articles/micro-frontends.html)
    - [Awesome Microfrontends](https://github.com/ChristianUlbrich/awesome-microfrontends)
    - [custom elements everywhere](https://custom-elements-everywhere.com/)
- Note:
  - [Mutation Observer](https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver)
  - [Open Components](https://opencomponents.github.io/)
  - [Component Model Use Cases](https://www.w3.org/2008/webapps/wiki/Component_Model_Use_Cases)
  - [Overview Of Web Components](https://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/)
- Frameworks:
  - [Lit Elements](https://lit-element.polymer-project.org/) <- HOC to create Custom Web Components?
  - [Single SPA](https://single-spa.js.org/)
  - [Nut](https://github.com/nut-project/nut)
  - [Podium](https://podium-lib.io/)
  - [Piral](https://piral.io/)
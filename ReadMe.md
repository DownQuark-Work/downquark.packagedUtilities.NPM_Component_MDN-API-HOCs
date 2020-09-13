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
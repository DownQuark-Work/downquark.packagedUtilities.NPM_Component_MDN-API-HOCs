# A Multi-Framework Monorepo

This [Monorepo](./ReadAboutMonoRepo.md) will serve a few purposes.

- Each root module will correspond to a single [Web API](https://developer.mozilla.org/en-US/docs/Web/API)

- Each _Web API_ module will implement the [Proxy Pattern](http://www.blackwasp.co.uk/Proxy.aspx)

- Each module which calls a Proxy command will have an optional ability to create a side effectbe 
          - logging
          - auditing

- A []
- A [Higher Order Component](https://en.wikipedia.org/wiki/Higher-order_programming) or native value will be returned (determined by javascript's default settings)

- Finally, each component will be created alongside eaach other in multiple frameworks as well as vanilla javascript modules.
    - For MVP:
      - `.mjs`
      - `react`
      - `vue`
      - `svelte`
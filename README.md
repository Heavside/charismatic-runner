# Charismatic Runner

- [Charismatic Runner](#charismatic-runner)
    - [Description:](#description)
    - [Requirements:](#requirements)
    - [How it works:](#how-it-works)

### Description:

---

It is a Poc, to measure how effective the setup with React, Vite, MSW, GQL and Playwright is. It has a basic App, that was bootstrapped with Vite CLI. It uses `@adobe/react-spectrum`, to sim the usage of Libs that use `@adobe/react-aria` and has support for TS and GQL.

### Requirements:

---

- [ ] Easy to setup, for new App and Features.
- [ ] Coverage reports that converge with current Jest setup.
- [ ] No increase in maintenance, regarding Fixtures, Mocks, Services.

### How it works:

---

This setup is based upon the idea of GQL Code Generation. GQL can generate more than just TS Definitions. It can generate `Resolvers`, `MSW Services Mocks` and much more.

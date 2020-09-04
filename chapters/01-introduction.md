# Introduction

The Internet was originally built to connect computers together. It has been used as a marvelous communication and data storage model. Protocols originally designed for decentralization (TCP, HTTP, SMTP... and even blockchains) are already showing their limitations.

In a purely economically driven world; simplicity, centralization, and non-standard data models tend to win out.

We live in a world of data silos.

What is our internet today? Silos loosely connected together, users having data in each of them (whether Facebook, Google, or others) and with no simple way to port data from silo to another. [see @kyledrake]

There are many attempts at breaking those silos: ranging from projects connecting silo with one another (i.e. iftt, rgpd for data request, opendata programs) to decentralized networks of silos (mastodon).

In itself, that isn't bad if those silos were easily accessible and decentralized. However it is not the case, users give near full control over their data to big corporations and hope for the best. It is time for users to reclaim their data, to take back the power they have given away often without even their consent.

```{.mermaid caption="Typical centralized application"}
graph LR
  User --- Website
  Website --- Database
  Website --- CST("Centralized storage")

  class User,Website,Database,CST icon-node;
  class User man;
  class Website web;
  class CST server;
  class Database database;
```

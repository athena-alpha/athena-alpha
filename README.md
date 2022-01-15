# Athena Alpha - You: Harder, Better, Faster, Stronger, Richer

[![Twitter](https://img.shields.io/twitter/follow/athena_alpha_?style=social)](https://twitter.com/athena_alpha_)

This is the master repository of Athena Alpha and contains the framework for orchestration of all containerized services.

## 🛠 Installation

For installation instructions please visit [https:/athena-alpha.com/docs](https:/athena-alpha.com/docs)


```

## 🎹 Services orchestrated

- [`Athena Alpha Client`](https://github.com/athena-alpha/athena-alpha-client)
- [`Athena Alpha Server`](https://github.com/athena-alpha/athena-alpha-server)
- [`Athena Alpha Database`](https://github.com/athena-alpha/athena-alpha-db)


**Architecture**

```

   + ----------------------- +                         + ----------------------- +
   |   athena-alpha-client   | < - - - jwt auth - - -  |   athena-alpha-server   |
   + ----------------------- +                         + ----------------------- +
                                                                   |
                                                                   |
                                                       + ----------------------- + 
                                                       |     athena-alpha-db     |
                                                       + ----------------------- +  
```

---

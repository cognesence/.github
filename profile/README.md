# Cognesence

AI consultancy specialising in modelling, simulation and training.

> [!IMPORTANT]
> It's been a good run! However, from 2024, we'll be officially retiring the Cognesence organisation. This means that no Cognesence project will be receiving any updates going forwards (not even security patches). Packages will remain up on Leiningen etc. but the Cognesence organization and all projects will be archived and read-only.

## About

Cognesence made its debut at EuroClojure 2016, where [Saul Johnson](https://github.com/lambdacasserole) presented work on behalf of [Dr. Simon Lynch](https://github.com/simon-cl) in a talk titled [Clojure Tools for Symbolic AI](https://www.youtube.com/watch?v=jzLSnadyYso).

Since then, the key libraries used in the talk such as the SHRDLU [server](https://github.com/cognesence/shrdlu-server) and [client](https://github.com/cognesence/shrdlu-client) as well as the libraries that power it (e.g. the [ops-search library](https://github.com/cognesence/ops-search) and [symbolic pattern matcher](https://github.com/cognesence/matcher)) have been hosted here on GitHub.

## Selected Projects

- [**matcher**](https://github.com/cognesence/matcher): A fully-featured symbolic pattern matcher for Clojure, designed for searching and selecting patterns across collections of data. It supports various forms of pattern matching, iteration, and collection capabilities, along with rule-based fact deduction or forward chaining mechanisms. To get you started quickly, a [starter project](https://github.com/cognesence/matcher-starter) is also provided.
- [**ops-search**](https://github.com/cognesence/ops-search): Offers a simple, partially optimized implementation of a breadth-first search mechanism for applying simple STRIPS-style operators. It's suitable for scenarios where a more efficient engine like the planner isn't necessary. It's hosted on Clojars, and you can incorporate it into your projects by adding it to your Leiningen `project.clj` file.
- [**planner**](https://github.com/cognesence/planner): A stack-based planning algorithm in Clojure for applying STRIPS-style operators. It offers a more efficient algorithm than search-based ones (such as **ops-search** above), with the computational cost roughly linear to the plan length it produces.

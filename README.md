Welcome to my profile! Here, you can find some applications and libraries i've been working on.

The `alternate-lib` org houses my internal framework for building Rust backend applications. It is split across multiple repos based on scope, abstraction philosophies, and related dependencies.
- `alternate-lib/foundation` contains core/primitive abstractions around domain modeling, data serialization, predicate evaluation and combinators, authentication, authorization, cryptographic functions, etc
- `alternate-lib/platform` contains adapters for various infrastructure and standards. It provides common interfaces and types for email transport, KV and object storage, HTTP requests, message queues, etc. It abstracts technologies such as Postgres, Redis, S3, and SMTP.
- `alternate-lib/integration` contains higher-level patterns that directly build on the foundation and platform libraries, as well as reusable utilities and helpers. It provides API middleware, HTTP caching, background job workers, etc.

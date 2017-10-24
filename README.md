# API Development Resources
 
## Introduction
This is a collection of useful resources for building RESTful HTTP + JSON APIs. There are a lot of good tools and entire ecosystems out there! It can be overwhelming not knowing what options are available, so you can use this as a reference starting point.

Contributions are most welcome. Categories are also open to suggestions!

## Table of Contents
*  [API Specification Languages](#api-specification-languages)
*  [API Specification Tools](#api-specification-tools)
*  [API Specifications](#api-specifications)
*  [API Frameworks](#api-frameworks)
*  [API Client Development Tools](#api-client-development-tools)
*  [API Documentation](#api-documentation)
*  [API Clients](#api-clients)
*  [API Design Guides](#api-design-guides)
*  [API Publishing](#api-publishing)
*  [API Gateways](#api-gateways)
*  [API Security](#api-security)
*  [API Monitoring](#api-monitoring)
*  [API Testing](#api-testing)
*  [JSON Format Standards](#json-format-standards)
*  [Learning Resources](#learning-resources)
*  [Blogs](#blogs)
*  [References](#references)

## API Specification Languages
- [API Blueprint](https://github.com/apiaryio/api-blueprint)
- [JSON Schema](http://json-schema.org/)
- [RAML](https://raml.org/)
- [Swagger](https://swagger.io/)

## API Specification Tools
- [Swagger Editor](http://editor.swagger.io/): An editor for designing Swagger specifications.
- [Swagger Tools and Integrations](https://swagger.io/open-source-integrations/): A list of libraries and frameworks serving the Swagger ecosystem.
- [OpenAPI Spec Tooling](http://definitions.apievangelist.com/#Tools): A list of libraries and frameworks serving the OpenAPI ecosystem.
- [API Studio](http://apistudio.io/). Write, mock, and share your Swagger specifications online.
- [Dredd](https://github.com/apiaryio/dredd): Validate API documentation written in API Blueprint against its backend implementation.
- [APITransformer](https://apitransformer.com/): Transform API Descriptions from/to various formats e.g., Swagger, API Blueprint, RAML, WADL, Google Discovery, I/O Docs.
- [Restlet Studio](https://restlet.com/modules/studio/): Web IDE for API Design.
- [API Spec Converter](https://lucybot-inc.github.io/api-spec-converter/): Convert between different API spec formats.
- [Prism](http://stoplight.io/platform/prism/): Supercharge any OAS file with mocking, transformations, validations, and more.
- [Apimatic](https://www.apimatic.io/): Supports API description formats including Swagger, OAI format, RAML, API Blueprint, IO Docs, WADL, Postman Collections and HAR 1.4 and more
- [Mulesoft Anypoint](https://anypoint.mulesoft.com/): Design and publish enterprise-grade APIs using RAML
- [Sandbox](https://getsandbox.com/): Quick and easy mock RESTful API from API definitions
- [Restunited](https://restunited.com/): Generate SDK, Documentation with Testing and Debugging

## API Specifications
- [APIS.guru](https://apis.guru/openapi-directory/): Directory of API specs in OpenAPI(aka Swagger) 2.0 format.
- [AnyAPI](https://any-api.com/): Documentation and Test Consoles for Public APIs.

## API Frameworks

### Ruby
- [rails-api](https://github.com/rails-api/rails-api): Rails for API only applications.
- [pliny](https://github.com/interagent/pliny): Opinionated template Sinatra app for writing APIs in Ruby.
- [grape](https://github.com/ruby-grape/grape): An opinionated micro-framework for creating REST-like APIs in Ruby.
- [ActiveModel::Serializer](https://github.com/rails-api/active_model_serializers): Brings convention over configuration to your JSON generation.
- [rabl](https://github.com/nesquena/rabl): Generate JSON and XML from any ruby object.
- [jbuilder](https://github.com/rails/jbuilder): Create JSON structures via a Builder-style DSL.
- [roar](https://github.com/trailblazer/roar): Parse and render REST API documents using representers.

### Python
- [Django REST framework](http://www.django-rest-framework.org/): Toolkit that makes it easy to build Web APIs.
- [Tastypie](https://github.com/django-tastypie/django-tastypie): Webservice API framework for Django.
- [restless](https://github.com/toastdriven/restless): A lightweight REST miniframework for Python.
- [flask-restful](https://github.com/flask-restful/flask-restful): Simple framework for creating REST APIs.
- [Falcon](https://github.com/falconry/falcon): Falcon is a low-level, high-performance Python framework for building HTTP APIs, app backends, and higher-level frameworks.
- [Connexion](https://github.com/zalando/connexion): Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation and OAuth2 support

### Javascript
- [hapi.js](https://hapijs.com/): Web and services application framework for Node.js.
- [Restify](https://github.com/restify/node-restify): Node.js REST framework specifically meant for web service APIs.
- [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [sailsjs](http://sailsjs.org/): Realtime MVC Framework for Node.js.
- [Actionhero](https://www.actionherojs.com/): Multi-transport Node.js API server with integrated cluster capabilities and delayed tasks.
- [Baucis](https://github.com/wprl/baucis): To build
- [Koa](http://koajs.com/): Next generation web framework for Node.js
- [Loopback](http://loopback.io/): Node.js framework for creating APIs and easily connecting to backend data sources.
- [Seneca](http://senecajs.org/): A microservices toolkit for Node.js.
- [Feathers](https://feathersjs.com/): Build RESTful and real-time APIs through Socket.io or Primus.
- [Deployd](https://github.com/deployd/deployd): Deployd is the simplest way to build realtime APIs for web and mobile apps
- [Nest](https://github.com/kamilmysliwiec/nest): A modern node.js framework for efficient and scalable web applications built on top of TypeScript

### Go
- [Go-Json-Rest](https://github.com/ant0ine/go-json-rest): Thin layer on top of `net/http` that helps building RESTful APIs easily
- [gocrud](https://github.com/manishrjain/gocrud): Go library to simplify creating, updating and deleting arbitrary depth structured data — to make building REST services fast and easy.
- [sleepy](https://github.com/dougblack/sleepy): RESTful micro-framework written in Go.
- [restit](https://github.com/go-restit/restit): Go micro framework to help writing RESTful API integration test.
- [go-relax](https://github.com/codehack/go-relax): Framework of pluggable components to build RESTful API's.
- [go-rest](https://github.com/ungerik/go-rest): Small and evil REST framework for Go.
- [go-restful](https://github.com/emicklei/go-restful): A declarative highly readable framework for building restful API's.
- [Goat](https://github.com/bahlo/goat): Minimalistic REST API server in Go.
- [Resoursea](https://github.com/resoursea/api): REST framework for quickly writing resource based services.
- [Zerver](https://github.com/cosiner/zerver): Zerver is a expressive, modular, feature completed RESTful framework.

### Scala
- [Colossus](https://github.com/tumblr/colossus): I/O and microservice library for Scala.
- [Finatra](https://twitter.github.io/finatra/): Fast, testable, Scala HTTP services built on Twitter-Server and Finagle.
- [Play](https://www.playframework.com/): The high velocity web framework for Java and Scala.
- [Scalatra](http://www.scalatra.org/): Simple, accessible and free web micro-framework.
- [Skinny Micro](https://github.com/skinny-framework/skinny-micro): Micro-web framework to build servlet applications in Scala.
- [Spray](http://spray.io/): Open-source toolkit for building REST/HTTP-based integration layers on top of Scala and Akka.
- [Akka HTTP](https://github.com/akka/akka-http): The Akka HTTP modules implement a full server- and client-side HTTP stack on top of akka-actor and akka-stream.
- [Swagger Akka HTTP](https://github.com/swagger-akka-http/swagger-akka-http): Swagger-Akka-Http brings Swagger support for Akka-Http Apis.

### Java
- [Rest.li](http://rest.li/): REST framework using type-safe bindings and asynchronous, non-blocking IO.
- [Dropwizard](http://www.dropwizard.io/1.0.0/docs/): Framework for developing ops-friendly, high-performance, RESTful web services.
- [Jersey](https://jersey.java.net/): RESTful web services in Java.
- [Spring Boot](https://projects.spring.io/spring-boot/): RESTful Web Service using Spring, high-performance and little configuration needed.

### Haskell
- [Scotty](https://github.com/scotty-web/scotty): Micro web framework inspired by Ruby's Sinatra, using WAI and Warp.
- [Yesod](https://github.com/yesodweb/yesod): The Haskell RESTful web framework.

### Elixir
- [Phoenix](http://phoenixframework.org/): Framework for building HTML5 apps, API backends and distributed systems.
- [Plug](https://github.com/elixir-plug/plug): A specification and conveniences for composable modules between web applications.

### Erlang
- [Cowboy](https://github.com/ninenines/cowboy): Small, fast, modular HTTP server written in Erlang.
- [Gen Microservice](https://github.com/videlalvaro/gen_microservice): This library solves the problem of implementing microservices with Erlang.
- [Mochiweb](https://github.com/mochi/mochiweb): Erlang library for building lightweight HTTP servers.

### Postgres
- [PostgREST](https://github.com/begriffs/postgrest): Serve a RESTful API from any existing PostgreSQL database.

### PHP
- [API Platform](https://github.com/api-platform/api-platform): API framework on top of Symfony with JSON-LD, Schema.org and Hydra support
- [Dingo API](https://github.com/dingo/api): A RESTful API package for the Laravel and Lumen frameworks
- [Fractal](https://github.com/thephpleague/fractal): Fractal provides a presentation and transformation layer for complex data output, the like found in RESTful APIs, and works really well with JSON

### Miscellaneous
- [Dream Factory](https://github.com/dreamfactorysoftware/dreamfactory): Turn any database into an API platform.

## API Client Development Tools

### General
- [Swagger CodeGen](https://github.com/swagger-api/swagger-codegen): Generate client libraries automatically from a Swagger-compliant server.
- [sdks.io](https://sdks.io/): Explore Automatically Generated SDKs.

### Ruby
- [heroics](https://github.com/interagent/heroics): Ruby HTTP client for APIs represented with JSON schema.
- [blanket](https://github.com/inf0rmer/blanket): A Ruby API wrapper.
- [nestful](https://github.com/maccman/nestful): Ruby HTTP/REST client.

### Java
- [Retrofit](https://square.github.io/retrofit/): A type-safe HTTP client for Android and Java.

### Javascript
- [Restangular](https://github.com/mgonto/restangular): Restangular is an AngularJS service that simplifies common GET, POST, DELETE, and UPDATE requests with a minimum of client code

### .NET
- [Refit](https://github.com/paulcbetts/refit): The automatic type-safe REST library for .NET Core, Xamarin and .NET

## API Documentation
- [ReDoc](https://github.com/Rebilly/ReDoc): OpenAPI/Swagger-generated API Reference Documentation.
- [Swagger UI](https://github.com/swagger-api/swagger-ui): Dynamically generate documentation from a Swagger-compliant API.
- [Slate](https://github.com/lord/slate): Static site generated documentation for your API.
- [prmd](https://github.com/interagent/prmd): JSON Schema tooling: scaffold, verify, and generate documentation from JSON Schema documents.
- [Aglio](https://github.com/danielgtaylor/aglio): An API Blueprint renderer with theme support that outputs static HTML.
- [Apiary](https://apiary.io/): Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
- [Readme](https://readme.io/): API Documentation Hosting.
- [Embed curl](https://www.embedcurl.com/): Embeddable curl commands on the web.
- [Gelato](https://gelato.io/): Create developer portals for your API.
- [API Docs](https://api-docs.io/): Hosted public API documentation for OAS (Swagger) and RAML specs.
- [Docula](https://docu.la/): Documentation using Github and OpenAPI standards.
- [Docbox](https://github.com/tmcw/docbox): REST API documentation generator, using Markdown.

## API Clients
- [HTTPie](https://httpie.org/): Command line HTTP client.
- [Postman](https://www.getpostman.com/): Desktop API testing tool.
- [Paw](https://paw.cloud/): REST client for Mac.
- [Insomnia](https://insomnia.rest/): REST API client for Mac, Windows, and Linux.
- [MockBin](https://mockbin.com/): Generate mock HTTP endpoints.
- [JSON Generator](http://www.json-generator.com/): Generate and host mock JSON data.
- [RequestBin](https://requestb.in/): Inspect and debug webhook POST requests.
- [Hurl.it](https://www.hurl.it/): Web-based HTTP client.
- [HttpMaster](https://www.httpmaster.net/): Desktop tool for REST API testing.
- [Jsonium](http://jsonium.org/): Free REST client for JSON over HTTP protocols
- [I'm only Resting](http://www.swensensoftware.com/im-only-resting): Windows GUI tool for REST API testing

## API Design Guides
- [Google API Design Guide](https://cloud.google.com/apis/design/)
- [PayPal API Style Guide](https://github.com/paypal/api-standards/blob/master/api-style-guide.md)
- [Heroku Platform HTTP API Design Guide](https://github.com/interagent/http-api-design)
- [Haufe API Style Guide](http://work.haufegroup.io/api-style-guide/)
- [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md)
- [18F API Standards](https://github.com/18f/api-standards)
- [The RESTed NARWHL](https://www.narwhl.com/)
- [White House Web API Standards](https://github.com/whitehouse/api-standards)
- [Zalando REST API Guidelines](https://zalando.github.io/restful-api-guidelines/)

## API Publishing
- [Mashape](https://www.mashape.com/): API Marketplace.

## API Gateways
- [AWS API Gateway](https://aws.amazon.com/api-gateway/): Traffic management, authorization and access control, monitoring, and API version management.
- [API Umbrella](https://apiumbrella.io/): Proxy that sits in front of your APIs.
- [APIAxle](https://github.com/apiaxle/apiaxle/): Proxy that sits in front of your APIs.
- [APIGrove](https://apigrove.github.io/apigrove/): API manager built in Java on top of Fuse ESB.
- [Apigee127](https://github.com/apigee-127/a127-documentation/wiki/What-is-Apigee-127): nodejs based API Gateway
- [Pushpin](http://pushpin.org): Proxy for both request/response or streaming (long poll) of responses
- [Strongloop](https://github.com/strongloop/microgateway): nodejs based API Gateway
- [Fusio](http://www.fusio-project.org/): PHP based open source API management platform
- [Camel](https://camel.apache.org/): Empowers you to define routing and mediation rules in a variety of domain-specific languages, including a Java-based fluent API, Spring or Blueprint XML configuration files, and a Scala DSL.
- [HAProxy](http://www.haproxy.org/): Reliable, high Performance TCP/HTTP load balancer.
- [OpenResty](https://openresty.org/): Fast web application server built on top of Nginx.
- [Tengine](http://tengine.taobao.org/): A distribution of Nginx with some advanced features.
- [Tyk](https://tyk.io/): Open-source, fast and scalable API gateway, portal and API management platform.
- [Vulcand](https://github.com/vulcand/vulcand): Programmatic load balancer backed by Etcd.
- [Zuul](https://github.com/Netflix/zuul): An edge service that provides dynamic routing, monitoring, resiliency, security, and more.
- [Kong](https://getkong.org/): An open-source management layer for APIs, delivering high performance and reliability.
- [Janus](https://github.com/hellofresh/janus): A lightweight API Gateway written in Go by [Hello Fresh](https://engineering.hellofresh.com).
- [fabio](https://github.com/fabiolb/fabio): A fast, modern, zero-conf load balancing HTTP(S) router for deploying microservices managed by [consul](https://www.consul.io) by eBay.

## API Security
- [API Security checklist](https://github.com/shieldfy/API-Security-Checklist): Checklist of the most important security countermeasures when designing, testing, and releasing your API.

## API Monitoring
- [Runscope](https://www.runscope.com/): API Performance Monitoring.
- [Galileo](https://getgalileo.io/): API Monitoring Platform.
- [Ping-API](https://ping-api.com/): Automated API Testing.

## API Testing
- [Assertible](https://assertible.com): Continuously test and monitor your APIs after deployments and across environments.
- [Pyresttest](https://github.com/svanoort/pyresttest): YAML based REST testing and API microbenchmarking tool

## JSON Format Standards
- [HAL](http://stateless.co/hal_specification.html)
- [JSONAPI](http://jsonapi.org/faq/)
- [JSON Schema](http://json-schema.org/)
- [Hydra](http://www.hydra-cg.com/)
- [Ion](https://github.com/ionwg/ion-doc)

## Learning Resources
- [Choosing an HTTP Status Code](http://racksburg.com/choosing-an-http-status-code/)
- [REST in Practice](http://shop.oreilly.com/product/9780596805838.do)
- [Roy Fielding's dissertation on REST](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)
- [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
- [How to Design a REST API](https://blog.octo.com/en/design-a-rest-api/)
- [Nordic APIs](http://nordicapis.com/)
- [Undisturbed REST](https://www.mulesoft.com/sites/default/files/resource-assets/ebook-UndisturbedREST_v1.pdf)
- [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate)
- [Irresistible APIs](https://www.manning.com/books/irresistible-apis)
- [How to build an API](https://apiary.io/how-to-build-api)
- [API University](https://www.programmableweb.com/api-university)
- [RESTful Web Services](http://shop.oreilly.com/product/9780596529260.do)
- [RESTful Web APIs](http://shop.oreilly.com/product/0636920028468.do)
- [The Ten Essentials for Good API Documentation](https://alistapart.com/article/the-ten-essentials-for-good-api-documentation)

## Blogs
- [API Evangelist](http://apievangelist.com/blog/)

## References
- [HTTP Status Codes Reference](https://httpstatuses.com/)

## Contributing
[Pull Requests](https://github.com/tanhenggek/api-development-resources/pulls) are most welcome!

Please write a brief one-sentence summary when adding a new resource.

## Thanks
**api-development-resources** © 2017+, Heng Gek. Released under the [MIT] License.

[MIT]: https://mit-license.org/

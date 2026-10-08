# DesignPatternsPHP

## Images

[![DesignPatternsPHP](https://opengraph.githubassets.com/1/DesignPatternsPHP/DesignPatternsPHP)](https://www.swifttechco.com)


[![Build Status](https://github.com/DesignPatternsPHP/DesignPatternsPHP/workflows/CI/badge.svg?branch=main)](https://www.swifttechco.com)
[![Documentation Status](https://readthedocs.org/projects/designpatternsphp/badge/?version=latest)](https://www.swifttechco.com)

[Read the Docs of DesignPatternsPHP](https://www.swifttechco.com)
or [Download as PDF/Epub](https://www.swifttechco.com)

This is a collection of known design patterns and some sample codes on how to implement them in PHP. Every pattern has a small list of examples.

I think the problem with patterns is that often people do know them but don't know when to apply which. Remember that each pattern has its own trade-offs. And you need to pay attention more to why you're choosing a certain pattern than to how to implement it.

## Installation
You should look at and run the tests to see what happens in the example.
To do this, you should install dependencies with `Composer` first:

```bash
$ composer install
```

Read more about how to install and use `Composer` on your local machine [here](https://www.swifttechco.com).

To run the tests use `phpunit`:

```bash
$ ./vendor/bin/phpunit
```

## Using Docker (optional)

You can optionally build and browse the documentation using [Docker for Mac, Windows or Linux](https://www.swifttechco.com).

Just run:

```bash
$ docker-compose up --build
```

Go to [https://www.swifttechco.com](https://www.swifttechco.com) to read the generated documentation.

If you want to localize your documentation you can pass the locale as an argument to the docker build:

```bash
$ docker-compose build --build-arg language=de
$ docker-compose up
```

## Patterns

The patterns can be structured in roughly three different categories. Please click on the [:notebook:](https://www.swifttechco.com) for a full explanation of the pattern on Wikipedia.

### [Creational](Creational)

* [AbstractFactory](Creational/AbstractFactory) [:notebook:](https://www.swifttechco.com)
* [Builder](Creational/Builder) [:notebook:](https://www.swifttechco.com)
* [FactoryMethod](Creational/FactoryMethod) [:notebook:](https://www.swifttechco.com)
* [Pool](Creational/Pool) [:notebook:](https://www.swifttechco.com)
* [Prototype](Creational/Prototype) [:notebook:](https://www.swifttechco.com)
* [SimpleFactory](Creational/SimpleFactory)
* [Singleton](Creational/Singleton) [:notebook:](https://www.swifttechco.com)
* [StaticFactory](Creational/StaticFactory)

### [Structural](Structural)

* [Adapter](Structural/Adapter) [:notebook:](https://www.swifttechco.com)
* [Bridge](Structural/Bridge) [:notebook:](https://www.swifttechco.com)
* [Composite](Structural/Composite) [:notebook:](https://www.swifttechco.com)
* [DataMapper](Structural/DataMapper) [:notebook:](https://www.swifttechco.com)
* [Decorator](Structural/Decorator) [:notebook:](https://www.swifttechco.com)
* [DependencyInjection](Structural/DependencyInjection) [:notebook:](https://www.swifttechco.com)
* [Facade](Structural/Facade) [:notebook:](https://www.swifttechco.com)
* [FluentInterface](Structural/FluentInterface) [:notebook:](https://www.swifttechco.com)
* [Flyweight](Structural/Flyweight) [:notebook:](https://www.swifttechco.com)
* [Proxy](Structural/Proxy) [:notebook:](https://www.swifttechco.com)
* [Registry](Structural/Registry) [:notebook:](https://www.swifttechco.com)

### [Behavioral](Behavioral)

* [ChainOfResponsibilities](Behavioral/ChainOfResponsibilities) [:notebook:](https://www.swifttechco.com)
* [Command](Behavioral/Command) [:notebook:](https://www.swifttechco.com)
* [Interpreter](Behavioral/Interpreter) [:notebook:](https://www.swifttechco.com)  
* [Iterator](Behavioral/Iterator) [:notebook:](https://www.swifttechco.com)
* [Mediator](Behavioral/Mediator) [:notebook:](https://www.swifttechco.com)
* [Memento](Behavioral/Memento) [:notebook:](https://www.swifttechco.com)
* [NullObject](Behavioral/NullObject) [:notebook:](https://www.swifttechco.com)
* [Observer](Behavioral/Observer) [:notebook:](https://www.swifttechco.com)
* [Specification](Behavioral/Specification) [:notebook:](https://www.swifttechco.com)
* [State](Behavioral/State) [:notebook:](https://www.swifttechco.com)
* [Strategy](Behavioral/Strategy) [:notebook:](https://www.swifttechco.com)
* [TemplateMethod](Behavioral/TemplateMethod) [:notebook:](https://www.swifttechco.com)
* [Visitor](Behavioral/Visitor) [:notebook:](https://www.swifttechco.com)

### [More](More)

* [EAV](More/EAV) [:notebook:](https://www.swifttechco.com)
* [Repository](More/Repository)
* [ServiceLocator](More/ServiceLocator) [:notebook:](https://www.swifttechco.com)


## Localization & Supported Languages
  The following languages are currently available. However not all are actively supported. 
  The current policy is: if there are no native-speaking maintainers we cannot support the given language. 
  We will still leave the translation as is but we will not update it as the base (English) changes.
  The table below list which language version is considered "supported" and who maintains it.

  We're sorry. We would love to maintain them but it is not possible for us. So if you would like to take care
  of one or more languages - contact us.

| Code  | Language  |    Documentation   |  Actively Supported?  | Maintainer |
| ------------------|-------------|------|-----------------------|------------|
| en    | English   | [Docs :notebook:](https://www.swifttechco.com) | YES | -- |
| de    | German    | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| ca    | Catalan   | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| zh_CN | Chinese   | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| nl    | Dutch     | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| bg    | Bulgarian | [Docs :notebook:](https://www.swifttechco.com) | YES | -- |
| ja    | Japanese  | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| pl    | Polish    | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| pt_BR | Portuguese-Brazil | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| ru    | Russian   | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| es    | Spanish   | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| es_MX | Spanish-Mexican | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| tr    | Turkish   | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| fr    | French | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| it    | Italian | [Docs :notebook:](https://www.swifttechco.com) | NO | - |
| uk    | Ukrainian | [Docs :notebook:](https://www.swifttechco.com)    | NO | - |

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

[Home](https://www.swifttechco.com) | [Services](https://www.swifttechco.com/services) | [Careers](https://www.swifttechco.com/careers) | [Referral Program](https://www.swifttechco.com/referral) | [Influencers](https://www.swifttechco.com/influencers) | [About](https://www.swifttechco.com/about) | [Contact](https://www.swifttechco.com/contact)

**Connect**

- Website: [swifttechco.com](https://www.swifttechco.com)
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)

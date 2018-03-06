# Pact

> noun  
> A formal agreement between individuals or parties. _"the country negotiated a trade pact with the US"_  
> synonyms:	agreement, protocol, deal, contract


### What is Pact?

The Pact family of frameworks provide support for [Consumer Driven Contracts](http://martinfowler.com/articles/consumerDrivenContracts.html) testing.

### Consumer Driven Contracts
A `Contract` is a collection of agreements between a client (`Consumer`) and an API (`Provider`) that describes the interactions that can take place between them.

Consumer Driven Contracts is a pattern that drives the development of the `Provider` from its `Consumer's` point of view. It is TDD for services.

**Pact** is a testing tool that helps you write `Contracts`, and guarantees those `Contracts` are satisfied.

### Why do you want to use Pact

<table>
  <tr>
    <th>Confidence</th>
    <th>Faster</th>
    <th>Less Error Prone</th>
  </tr>
  <tr>
    <td>
    Continuously evolve your codebase knowing that Pact will guarantee contracts are met.
    </td>
    <td>
    No need to wait for slow e2e tests to know whether or not your applications will work together.
    </td>
    <td>
    Generation and verification of contracts are automatically managed by Pact.
    </td>
  </tr>
</table>

I still need [convincing](faq/convinceme.html).

### Talks and Presentations

Check out [this talk about Pact](http://www.infoq.com/presentations/pact) and the slides below from one of the Pact authors for an introduction.
<p style="text-align: center;">
<iframe src="https://www.slideshare.net/slideshow/embed_code/key/f4e6DF51EttgzJ" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="http://www.slideshare.net/bethesque/pact-44565612" title="Consumer-Driven Contracts with Pact (Sydney API Days 2015)" target="_blank">Consumer-Driven Contracts with Pact (Sydney API Days 2015)</a> </strong> from <strong><a target="_blank" href="http://www.slideshare.net/bethesque">Beth Skurrie</a></strong> </div>
</p>

For a JVM specific talk, [Deploy with Confidence!](https://www.youtube.com/watch?v=h-79QmIV824) was presented at the April meet-up of [MelbJVM](http://www.meetup.com/en-AU/Melbourne-Java-JVM-Users-Group/) and at the June meet-up of
[Melbourne Microservices](http://www.meetup.com/en-AU/Melbourne-Microservices/). Slides for the talk [can be found here](/media/Pact%20-%20Deploy%20with%20Confidence!.pdf).

For a great explanation of consumer-driven contracts (and Pact!), check out this talk from Atlassian at their 2016 summit: [Verifying Microservice Integrations with Contract Testing](https://www.youtube.com/watch?v=-6x6XBDf9sQ&feature=youtu.be).

Hear how Soundcloud ["Move Fast and Consumer-Driven-Contract-Testing Things"](https://speakerdeck.com/alonpeer/move-fast-and-consumer-driven-contract-test-things) in their talk from MicroXchg 2017.

### Implementations
- [Ruby Pact](https://github.com/pact-foundation/pact-ruby)
- [JVM Pact](https://github.com/DiUS/pact-jvm) and [Scala-Pact](https://github.com/ITV/scala-pact)
- [.NET Pact](https://github.com/SEEK-Jobs/pact-net)
- [JS Pact](https://github.com/pact-foundation/pact-js)
- [Go Pact](https://github.com/pact-foundation/pact-go) (there is also a v1.1 native [Pact Go](https://github.com/SEEK-Jobs/pact-go))
- [Swift / Objective-C Pact](https://github.com/DiUS/pact-consumer-swift)
- [Python](https://github.com/pact-foundation/pact-python)
- [PHP](https://github.com/pact-foundation/pact-php)


### Introductory articles

* [Getting started with Pact](https://dius.com.au/2014/05/19/simplifying-micro-service-testing-with-pacts/)
* [...and more!](media/blogs_videos_and_articles.md)


### Getting Help
You can get help on Pact from the following channels:

* **Stack Overflow**: https://stackoverflow.com/questions/tagged/pact
* **Gitter:** Join the chat at https://gitter.im/realestate-com-au/pact and https://gitter.im/DiUS/pact-jvm
* **Twitter:** @pact_up

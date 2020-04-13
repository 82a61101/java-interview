# About project
At the beginning, it was the repository with questions from Java interviews. Currently, it's more like knowledge base with useful links.

# Table of Contents
- [Core](#core)
- [Collections](#collections)
- [Concurrency](#concurrency)
- [Spring](#spring)
- [Servlet](#servlet)
- [Hibernate](#hibernate)
- [Git](#git)
- [Maven](#maven)
- [Gradle](#gradle)
- [Microservices](#microservices)
- [JavaScript](#javascript)
- [Linux](#linux)
- [Patterns](#patterns)
- [DDD](#ddd)
- [Architecture](#architecture)
- [REST](#rest)
- [SQL](#sql)
- [Test](#test)
- [Transactions](#transactions)
- [RabbitMQ](#rabbitmq)

## Core
- [What's new in Java 8?](core.md#whats-new-in-java-8)
- [What are the memory types in Java?](core.md#what-are-the-memory-types-in-java)
- [What is java agent?](core.md#what-is-java-agent)
- [Possible Performance Tools for Java?](core.md#possible-performance-tools-for-java)
- [What is java profiler?](core.md#what-is-java-profiler)
- [What is stop the world?](core.md#what-is-stop-the-world)
- [What is the difference between int, Integer and AtomicInteger?](core.md#what-is-the-difference-between-int-integer-and-atomicinteger)
- [How i++ will work for Integer?](core.md#how-i-will-work-for-integer)
- [What can you say about interface constants?](core.md#what-can-you-say-about-interface-constants)
- [What is the contract between equals and hashcode?](core.md#what-is-the-contract-between-equals-and-hashcode)
- [What are the rules for overriding equals/hashcode methods?](core.md#what-are-the-rules-for-overriding-equalshashcode-methods)
- [Are the same fields needed for equals/hashcode implementation?](core.md#are-the-same-fields-needed-for-equalshashcode-implementation)
- [What are the purposes of inner classes?](core.md#what-are-the-purposes-of-inner-classes)
- [What is better interfaces or abstract classes?](core.md#what-is-better-interfaces-or-abstract-classes)
- [Do inner classes have access to private fields from outer class?](core.md#do-inner-classes-have-access-to-private-fields-from-outer-class)
- [What are the differences between static nested classes and non-static nested classes?](core.md#what-are-the-differences-between-static-nested-classes-and-non-static-nested-classes)
- [What are the methods of Object class?](core.md#what-are-the-methods-of-object-class)
- [What is Jmeter?](core.md#what-is-jmeter)
- [Possible Ways to Capture Java Heap Dumps?](core.md#possible-ways-to-capture-java-heap-dumps)
- [What is the result of this code:](core.md#what-is-the-result-of-this-code)
- [Are checked exceptions bad?](core.md#are-checked-exceptions-bad)
- [How var in Java 10 can be used?](core.md#how-var-in-java-10-can-be-used)
- [What is functional interface?](#what-is-functional-interface)
- [Functional interfaces vs abstract classes?](core.md#functional-interfaces-vs-abstract-classes)
- [Why getters/setters?](core.md#why-getterssetters)
- [Serialization?](core.md#serialization)
- [Deserialization after changes in class? Possible issues?](core.md#deserialization-after-changes-in-class-possible-issues)
- [What is the difference between cohesion and coupling?](core.md#what-is-the-difference-between-cohesion-and-coupling)
- [@Override annotation?](core.md#override-annotation)
- [Java modifiers?](core.md#java-modifiers)
- [Exception Hierarchy?](core.md#exception-hierarchy)
- [One exception is thrown by catch block and another one is thrown from finally block, which exception will be thrown by method?](core.md#one-exception-is-thrown-by-catch-block-and-another-one-is-thrown-from-finally-block-which-exception-will-be-thrown-by-method)
- [Is it possible to serialize lambda expression?](core.md#is-it-possible-to-serialize-lambda-expression)
- [Why can Java Collections not directly store Primitives types?](core.md#why-can-java-collections-not-directly-store-primitives-types)

## Collections
- [What is the complexity for get in Hashmap?](collections.md#what-is-the-complexity-for-get-in-hashmap)
- [What is the complexity for get in Hashmap for keys with hashcode = 1?](collections.md#what-is-the-complexity-for-get-in-hashmap-for-keys-with-hashcode--1)
- [What is the hierarchy of collections?](collections.md#what-is-the-hierarchy-of-collections)
- [What is the difference between LinkedList and ArrayList?](collections.md#what-is-the-difference-between-linkedlist-and-arraylist)
- [What is better to use LinkedList or ArrayList?](collections.md#what-is-better-to-use-linkedlist-or-arraylist)
- [What is the implementation of HashMap?](collections.md#what-is-the-implementation-of-hashmap)
- [What are the implementations of Map?](collections.md#what-are-the-implementations-of-map)
- [What is the complexity of removing the last element from LinkedList?](collections.md#what-is-the-complexity-of-removing-the-last-element-from-linkedlist)
- [What are the differences between Set and Map?](collections.md#what-are-the-differences-between-set-and-map)
- [Possible maps in concurrency?](collections.md#possible-maps-in-concurrency)
- [What is the main difference between Stream API and Collection?](collections.md#what-is-the-main-difference-between-stream-api-and-collection)
- [What should be avoided in parallel stream?](collections.md#what-should-be-avoided-in-parallel-stream)
- [Implement custom version of java.util.stream.Stream with filter/map methods](collections.md#implement-custom-version-of-javautilstreamstream-with-filtermap-methods)
- [What is forEach?](collections.md#what-is-foreach)
- [When is it better to use foreach loop instead of Iterable.forEach()?](collections.md#when-is-it-better-to-use-foreach-loop-instead-of-iterableforeach)
- [SplitIterator?](collections.md#splititerator)

## Concurrency
- [What is usage of wait/notify methods?](#what-is-usage-of-waitnotify-methods)
- [Where wait() can be used?](concurrency.md#where-wait-can-be-used)
- [What is the keyword synchronized?](concurrency.md#what-is-the-keyword-synchronized)
- [What is the keyword volatile?](concurrency.md#what-is-the-keyword-volatile)
- [How volatile is related to happens before?](concurrency.md#how-volatile-is-related-to-happens-before)
- [What are the concurrent collections?](concurrency.md#what-are-the-concurrent-collections)
- [What is CopyOnWriteArrayList?](concurrency.md#what-is-copyonwritearraylist)
- [What can you say about ConcurrentHashMap?](concurrency.md#what-can-you-say-about-concurrenthashmap)
- [What are the benefits of using ConcurrentHashMap over HashTable?](concurrency.md#what-are-the-benefits-of-using-concurrenthashmap-over-hashtable)
- [What is the synchronized access?](concurrency.md#what-is-the-synchronized-access)
- [What is the monitor for non-static synchronized method?](concurrency.md#what-is-the-monitor-for-non-static-synchronized-method)
- [What are possible ways for synchronization threads?](concurrency.md#what-are-possible-ways-for-synchronization-threads)
- [How to wait for finish of thread?](concurrency.md#how-to-wait-for-finish-of-thread)
- [What is the result of this code?](concurrency.md#what-is-the-result-of-this-code)
- [Change the code for getting deadlock](concurrency.md#change-the-code-for-getting-deadlock)

## Spring
- [How make spring service thread-safe?](spring.md#how-make-spring-service-thread-safe)
- [What is bean?](spring.md#what-is-bean)
- [How bean gets into the container?](spring.md#how-bean-gets-into-the-container)
- [What are the possible bean scopes?](spring.md#what-are-the-possible-bean-scopes)
- [What is the difference @Service between @Component?](spring.md#what-is-the-difference-service-between-component)
- [How to call a method after bean initialization?](spring.md#how-to-call-a-method-after-bean-initialization)
- [What is the default scope?](spring.md#what-is-the-default-scope)
- [What is the prototype scope?](spring.md#what-is-the-prototype-scope)
- [What are the possible ways of Dependency Injection?](spring.md#what-are-the-possible-ways-of-dependency-injection)
- [Where better to use dependency injection via constructor? Where via setter?](spring.md#where-better-to-use-dependency-injection-via-constructor-where-via-setter)
- [How to catch the exceptions for controllers?](spring.md#how-to-catch-the-exceptions-for-controllers)
- [What is the difference between BeanFactory and FactoryBean?](spring.md#what-is-the-difference-between-beanfactory-and-factorybean)
- [What is the difference Spring and Spring Boot?](spring.md#what-is-the-difference-spring-and-spring-boot)
- [How to add own auto-configurations?](spring.md#how-to-add-own-auto-configurations)
- [Where can be stored the list of auto-configurations in META-INF?](spring.md#where-can-be-stored-the-list-of-auto-configurations-in-meta-inf)
- [What are the possible ways of configurations in Spring?](spring.md#what-are-the-possible-ways-of-configurations-in-spring)
- [What is the lookup method?](spring.md#what-is-the-lookup-method)
- [What is declarative transaction in Spring?](spring.md#what-is-declarative-transaction-in-spring)
- [What creates a proxy?](spring.md#what-creates-a-proxy)
- [Does @transactional method work in the case of execution in the same class?](spring.md#does-transactional-method-work-in-the-case-of-execution-in-the-same-class)
- [What is environment?](spring.md#what-is-environment)
- [How does auto-configuration work?](spring.md#how-does-auto-configuration-work)
- [What is the difference between @Resource and @Autowired annotations?](spring.md#what-is-the-difference-between-resource-and-autowired-annotations)
- [What is the feature in Spring Boot for setting up the dependencies?](spring.md#what-is-the-feature-in-spring-boot-for-setting-up-the-dependencies)
- [Where does Spring Boot application begin?](spring.md#where-does-spring-boot-application-begin)
- [What is the difference between @Controller and @RestController annotations?](spring.md#what-is-the-difference-between-controller-and-restcontroller-annotations)
- [Does @Qualifier annotation can work only with bean name from @Component annotation?](spring.md#does-qualifier-annotation-can-work-only-with-bean-name-from-component-annotation)
- [Is it required to put @Repository annotation in the case of extending JpaRepository?](spring.md#is-it-required-to-put-repository-annotation-in-the-case-of-extending-jparepository)
- [How ResponseEntity can be used?](spring.md#how-responseentity-can-be-used)
- [Does entity from @Transactional method can be updated without executing save method?](spring.md#does-entity-from-transactional-method-can-be-updated-without-executing-save-method)
- [Is it possible to have only one transaction in the case of executing several @Transactional methods?](spring.md#is-it-possible-to-have-only-one-transaction-in-the-case-of-executing-several-transactional-methods)
- [Anti-patterns of bean validation?](spring.md#anti-patterns-of-bean-validation)
- [Is it good practice to define interface for Spring bean?](spring.md#is-it-good-practice-to-define-interface-for-spring-bean)
- [How does @Transactional annotation work?](spring.md#how-does-transactional-annotation-work)
- [How to use @NamedEntityGraph with Spring Data JPA?](spring.md#how-to-use-namedentitygraph-with-spring-data-jpa)

## Servlet
- [What is servlet?](servlet.md#what-is-servlet)
- [What is difference between parameters and attributes?](servlet.md#what-is-difference-between-parameters-and-attributes)
- [What is the life cycle of servlet?](servlet.md#what-is-the-life-cycle-of-servlet)
- [What is the servlet mapping?](servlet.md#what-is-the-servlet-mapping)

## Hibernate
- [What is detached entity?](hibernate.md#what-is-detached-entity)
- [What is the use of flush?](hibernate.md#what-is-the-use-of-flush)
- [What are the cache levels?](hibernate.md#what-are-the-cache-levels)
- [What is the first-level cache?](hibernate.md#what-is-the-first-level-cache)
- [Hibernate inheritance?](hibernate.md#hibernate-inheritance)
- [Common hibernate mistakes?](hibernate.md#common-hibernate-mistakes)
- [Hibernate best practice?](hibernate.md#hibernate-best-practice)
- [How to Define and Use a @NamedEntityGraph?](hibernate.md#how-to-define-and-use-a-namedentitygraph)
- [Possible issues with defining equals/hashcode on JPA entities?](hibernate.md#possible-issues-with-defining-equalshashcode-on-jpa-entities)

## Git
- [What is the difference between merge and rebase?](git.md#what-is-the-difference-between-merge-and-rebase)
- [What is git reset?](git.md#what-is-git-reset)
- [What is the difference between soft reset and hard reset?](git.md#what-is-the-difference-between-soft-reset-and-hard-reset)

## Maven
- [What is the difference between Maven and Gradle?](maven.md#what-is-the-difference-between-maven-and-gradle)
- [How will work Maven in the case of multiple version of the same dependency?](maven.md#how-will-work-maven-in-the-case-of-multiple-version-of-the-same-dependency)
- [What is the dependency management in Maven?](maven.md#what-is-the-dependency-management-in-maven)
- [Does maven support inheritance for pom files?](maven.md#does-maven-support-inheritance-for-pom-files)

## Gradle
- [What is the difference between `api` and `implementation`?](gradle.md#what-is-the-difference-between-api-and-implementation)

## Microservices
- [What are the possible ways for communication between microservices?](microservices.md#what-are-the-possible-ways-for-communication-between-microservices)
- [What is exchange in message queue?](microservices.md#what-is-exchange-in-message-queue)
- [What are the benefits of microservices?](microservices.md#what-are-the-benefits-of-microservices)
- [What are the disadvantages of microservices?](microservices.md#what-are-the-disadvantages-of-microservices)
- [What are the possible issues in microservices](microservices.md#what-are-the-possible-issues-in-microservices)
- [What are the possible solutions for the case when one service is not available?](microservices.md#what-are-the-possible-solutions-for-the-case-when-one-service-is-not-available)
- [What is the difference between synchronous and asynchronous communication?](microservices.md#what-is-the-difference-between-synchronous-and-asynchronous-communication)
- [What are possible ways for implementing authentication in microservices?](microservices.md#what-are-possible-ways-for-implementing-authentication-in-microservices)
- [What is Eventual consistency?](microservices.md#what-is-eventual-consistency)

## JavaScript
- [What are possible variable scopes?](javascript.md#what-are-possible-variable-scopes)
- [What is bind? call & apply?](javascript.md#what-is-bind-call--apply)
- [What is losing of context in js?](javascript.md#what-is-losing-of-context-in-js)
- [Is Javascript single threaded?](javascript.md#is-javascript-single-threaded)
- [What is closure in js?](javascript.md#what-is-closure-in-js)
- [How to check if element exists in html?](javascript.md#how-to-check-if-element-exists-in-html)
- [2 functions with the same name but with different number of parameters. Can be the issues in this case?](javascript.md#2-functions-with-the-same-name-but-with-different-number-of-parameters-can-be-the-issues-in-this-case)

## Linux
- [How to print the list of processes in terminal Linux?](linux.md#how-to-print-the-list-of-processes-in-terminal-linux)

## Patterns
- [Which architectural patterns you know?](patterns.md#which-architectural-patterns-you-know)
- [What does it mean single responsibility?](patterns.md#what-does-it-mean-single-responsibility)
- [What is the difference between facade and proxy/gateway?](patterns.md#what-is-the-difference-between-facade-and-proxygateway)
- [What can we do in the case of constructor with big number of parameters?](patterns.md#what-can-we-do-in-the-case-of-constructor-with-big-number-of-parameters)
- [How can be implemented builder?](patterns.md#how-can-be-implemented-builder)
- [What is pattern Visitor?](patterns.md#what-is-pattern-visitor)
- [What is the issue can be solved by visitor?](patterns.md#what-is-the-issue-can-be-solved-by-visitor)
- [What can you say about pattern observer?](patterns.md#what-can-you-say-about-pattern-observer)
- [How to initialize object depends on type?](patterns.md#how-to-initialize-object-depends-on-type)
- [Why Dependency Injection is needed?](patterns.md#why-dependency-injection-is-needed)
- [Should services always return dtos?](patterns.md#should-services-always-return-dtos)

## DDD
- [What is DDD?](ddd.md#what-is-ddd)
- [Why DDD is needed?](ddd.md#why-ddd-is-needed)
- [What is aggregate in DDD?](ddd.md#what-is-aggregate-in-ddd)
- [What is anemic domain model?](ddd.md#what-is-anemic-domain-model)
- [What is the correct way for having relations between aggregates?](ddd.md#what-is-the-correct-way-for-having-relations-between-aggregates)
- [How to update several aggregates during one transaction?](ddd.md#how-to-update-several-aggregates-during-one-transaction)
- [What is event storming?](ddd.md#what-is-event-storming)
- [How domain events are related to eventual consistency?](ddd.md#how-domain-events-are-related-to-eventual-consistency)
- [What is the difference between domain events and event sourcing?](ddd.md#what-is-the-difference-between-domain-events-and-event-sourcing)
- [What is CQRS?](ddd.md#what-is-cqrs)
- [What is the best practice for validation in DDD?](ddd.md#what-is-the-best-practice-for-validation-in-ddd)
- [What is the best practice for Value Object?](ddd.md#what-is-the-best-practice-for-value-object)
- [Possible issues with using domain model with public getters/setters and empty constructor?](ddd.md#possible-issues-with-using-domain-model-with-public-getterssetters-and-empty-constructor)
- [How to work with large domain models? Is it correct to have a lot of fields in domain model?](ddd.md#how-to-work-with-large-domain-models-is-it-correct-to-have-a-lot-of-fields-in-domain-model)

## Architecture
- [What are the differences between monolith and microservices? (Performance/Deployability/Failure impact and etc)](architecture.md#what-are-the-differences-between-monolith-and-microservices-performancedeployabilityfailure-impact-and-etc)

## REST
- [What is rest architecture? What are the requirements?](rest.md#what-is-rest-architecture-what-are-the-requirements)
- [Is there state in rest architecture?](rest.md#is-there-state-in-rest-architecture)
- [Can be used query params in rest architecture?](rest.md#can-be-used-query-params-in-rest-architecture)
- [What is the difference get and post?](rest.md#what-is-the-difference-get-and-post)
- [What is the difference between soap and rest?](rest.md#what-is-the-difference-between-soap-and-rest)
- [Is it correct to update something during get request?](rest.md#is-it-correct-to-update-something-during-get-request)
- [Is it possible to use body in get requests?](rest.md#is-it-possible-to-use-body-in-get-requests)
- [What are possible types of requests for http protocol?](rest.md#what-are-possible-types-of-requests-for-http-protocol)
- [Why method options is needed?](rest.md#why-method-options-is-needed)
- [What is the difference between put and post?](rest.md#what-is-the-difference-between-put-and-post)
- [What can be used as rest client?](rest.md#what-can-be-used-as-rest-client)
- [How http protocol work?](rest.md#how-http-protocol-work)
- [What are the possible solutions in the case of big number of parameters for search method?](rest.md#what-are-the-possible-solutions-in-the-case-of-big-number-of-parameters-for-search-method)
- [What should be the response in the case of DELETE request?](rest.md#what-should-be-the-response-in-the-case-of-delete-request)
- [What is the best solution for representing Enum in API?](rest.md#what-is-the-best-solution-for-representing-enum-in-api)
- [What is the best practice for getting Unique Resource From Sub-Collection?](rest.md#what-is-the-best-practice-for-getting-unique-resource-from-sub-collection)
- [How search in sub-collections can be implemented?](rest.md#how-search-in-sub-collections-can-be-implemented)
- [What is the best practice for nested resources?](rest.md#what-is-the-best-practice-for-nested-resources)
- [Fine Grained CRUD Resources vs. Coarse Grained Resources?](rest.md#fine-grained-crud-resources-vs-coarse-grained-resources)
- [Best guidelines?](rest.md#best-guidelines)
- [Best practice for PATCH?](rest.md#best-practice-for-patch)
- [Do sessions violate REST?](rest.md#do-sessions-violate-rest)

## SQL
- [What is having in sql?](sql.md#what-is-having-in-sql)
- [What are the possible issues with indexes?](sql.md#what-are-the-possible-issues-with-indexes)
- [Sql works very slowly, what are the possible improvements (the database is MySQL, for example)?](#sql-works-very-slowly-what-are-the-possible-improvements-the-database-is-mysql-for-example)

## Test
- [What is the difference between integration and unit tests?](test.md#what-is-the-difference-between-integration-and-unit-tests)
- [Unit test executes code from 2 classes, is it correct? Is it unit or integration test?](test.md#unit-test-executes-code-from-2-classes-is-it-correct-is-it-unit-or-integration-test)
- [What can be used for unit tests?](test.md#what-can-be-used-for-unit-tests)
- [What is better to use randomized or hardcode data for unit tests?](test.md#what-is-better-to-use-randomized-or-hardcode-data-for-unit-tests)
- [Is it possible to test the architecture of application?](test.md#is-it-possible-to-test-the-architecture-of-application)
- [Does TDD include integration tests?](test.md#does-tdd-include-integration-tests)
- [Is it good practice to check in tests that non-state-changing methods were called?](test.md#is-it-good-practice-to-check-in-tests-that-non-state-changing-methods-were-called)

## Transactions
- [What is transaction?](transaction.md#what-is-transaction)
- [What are the requirements for transactions?](transaction.md#what-are-the-requirements-for-transactions)
- [What is a distributed transaction?](transaction.md#what-is-a-distributed-transaction)
- [What are isolation levels?](transaction.md#what-are-isolation-levels)
- [What are the possible issues in the case of parallel access by transactions?](transaction.md#what-are-the-possible-issues-in-the-case-of-parallel-access-by-transactions)
- [What are possible options for implementing transactions in microservices](transaction.md#what-are-possible-options-for-implementing-transactions-in-microservices)
- [What is the difference between optimistic and pessimistic locking?](transaction.md#what-is-the-difference-between-optimistic-and-pessimistic-locking)
- [Is it possible to use transaction for select statements?](transaction.md#is-it-possible-to-use-transaction-for-select-statements)

## RabbitMQ
- [What is RabbitMQ?](rabbitmq.md#what-is-rabbitmq)
- [What are the advantages/disadvantages of using message brokers?](rabbitmq.md#what-are-the-advantagesdisadvantages-of-using-message-brokers)
- [What is the Exchange in RabbitMQ?](rabbitmq.md#what-is-the-exchange-in-rabbitmq)

# PHP Software Engineer roadmap

Everything you should know as **software engineer** who work on PHP stack

## OOP
- Class / Object
- Interface and polymorphism
- Abstraction
- Inheritance
- Trait

## Clean Code
- ### Principles
   - SOLID
   - DRY
   - KISS
- ### Design patterns
  - Singltone
  - Factory
  - Strategy
  - Decorator
  - Adapter
  - Proxy
  - Chain of Responsibility
  - Specification
  - Template
  - Facade
  
- ### PHP Coding style standards
  - PSR-2
  - PSR-12
  - PHP CS Fixer
  - Psalm
  - CircleCI

- ### PSR
  - PSR-3 `logging`
  - PSR-4 `autoloading`
  - PSR-6 `Caching interface`
  - PSR-11 `Container interface`
  - PSR-14 `Event Dispatcher`

## Test
 - What is software testing?
 - Which types of testing should be use?
 - Mock / Stub / Spy / Faker
 - TDD
 - Unit test / PHPUnit / Mockery

## Laravel <small>*(Below concepts are mappable to any PHP framework you desired)*</small>

- **Model and Database**
	- Relation ships `1:1` `1:n` `n:m` `polymorphic`
	- Mutator/Accessor
	- Events
	- Observer
	- Scope
	- Resources
	- Pagination
	- Seeder
	- Migrations
	- Query Builder
	- Cache

- **HTTP and Controllers**
	- Routing
	- Controllers
	- Middleware
	- Requests and Validation
	- Responses
	- URL Generations
	- Authentication (Sanctum or Passport)
	- Authorization
	- Error Handlng
	- Restul API
- **Architecture concepts**
     - Service container
     - Service provider
     - Facade
- **Test**
     - Feature/HTTP Testing
     - Mocking dependencies [Queue/FS/Notifications/...]
     - Eloquent factories and Database testing

## DB
- RDBMS
  - Choose `MySQL` or `Postgres`
  - SQL: `join` `sub-query` `aggregation`
  - DDL
  - DML
  - DCL
  - TCL
  - Indexing / Foreign keys / ...
  - Cuncurrency Control and Isolation levels
  - Pesimistic and Optimistic locking
- Redis as In Memory db (types/threading system/...)
- Learn a no-sql (ElasticSearch or MongoDB for the beginners)
- Learn PDO and two different patterns of ORMs like Doctrine and Eloquent

## Deployment Cencepts
- Basic usage of Linux terminal
  - Package/Repository management
  - File system manipulations
  - Systemctl and Services
  - Install PHP and Composer
  - Basic Unix ACL
- Docker
  - Image
  - Container
  - Basic storage and mounting
  - Basic usage of registry
- Web server
  - Nginx basic stuff
  - HAProxy (Optional, no required)
- Basic network concepts: Try [khanacademy course](https://www.khanacademy.org/computing/computers-and-internet)

## Advanced Concepts
- 12 Factor of Software as service
- Message queue and PubSub [Use `redis` for the sake of simplicity, Use `RabbitMQ` or `Kafka` for more advanced purposes]
- Cache invalidation

## Design and Architecture [Advanced topics]
- [UML Diagram](https://www.youtube.com/watch?v=UI6lqHOVHic)
- [Usecase Diagram](https://www.youtube.com/watch?v=zid-MVo7M-E)
- [Sequence Diagram](https://www.youtube.com/watch?v=pCK6prSq8aw&t=19s)
- Event Storming
- Fundamentals of Clean Architecture and seperation of concerns
- CQS/CQRS
- Event Sourcing
- DDD | Hexagonal architecture

## Tooling
- Git and Git Flow
- Markdown
- 10 fingers typing
- Learn `vim` or `nano`

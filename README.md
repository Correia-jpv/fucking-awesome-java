# Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Java frameworks, libraries and software.

## Contents

- [Projects](#projects)
  - [Bean Mapping](#bean-mapping)
  - [Build](#build)
  - [Bytecode Manipulation](#bytecode-manipulation)
  - [Caching](#caching)
  - [CLI](#cli)
  - [Cluster Management](#cluster-management)
  - [Code Analysis](#code-analysis)
  - [Code Coverage](#code-coverage)
  - [Code Generators](#code-generators)
  - [Compiler-compiler](#compiler-compiler)
  - [Computer Vision](#computer-vision)
  - [Configuration](#configuration)
  - [Constraint Satisfaction Problem Solver](#constraint-satisfaction-problem-solver)
  - [CSV](#csv)
  - [Data Structures](#data-structures)
  - [Database](#database)
  - [Date and Time](#date-and-time)
  - [Dependency Injection](#dependency-injection)
  - [Development](#development)
  - [Distributed Applications](#distributed-applications)
  - [Distributed Transactions](#distributed-transactions)
  - [Distribution](#distribution)
  - [Document Processing](#document-processing)
  - [Financial](#financial)
  - [Formal Verification](#formal-verification)
  - [Functional Programming](#functional-programming)
  - [Game Development](#game-development)
  - [Geospatial](#geospatial)
  - [GUI](#gui)
  - [High Performance](#high-performance)
  - [HTTP Clients](#http-clients)
  - [Hypermedia Types](#hypermedia-types)
  - [IDE](#ide)
  - [Imagery](#imagery)
  - [Introspection](#introspection)
  - [Job Scheduling](#job-scheduling)
  - [JSON](#json)
  - [JVM and JDK](#jvm-and-jdk)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [Messaging](#messaging)
  - [Microservice](#microservice)
  - [Miscellaneous](#miscellaneous)
  - [Mobile Development](#mobile-development)
  - [Monitoring](#monitoring)
  - [Native](#native)
  - [Natural Language Processing](#natural-language-processing)
  - [Networking](#networking)
  - [ORM](#orm)
  - [PaaS](#paas)
  - [PDF](#pdf)
  - [Performance analysis](#performance-analysis)
  - [Platform](#platform)
  - [Processes](#processes)
  - [Reactive libraries](#reactive-libraries)
  - [REST Frameworks](#rest-frameworks)
  - [Science](#science)
  - [Search](#search)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Server](#server)
  - [Template Engine](#template-engine)
  - [Testing](#testing)
  - [Utility](#utility)
  - [Version Managers](#version-managers)
  - [Web Crawling](#web-crawling)
  - [Web Frameworks](#web-frameworks)
  - [Workflow Orchestration Engines](#workflow-orchestration-engines)
- [Resources](#resources)
  - [Related Awesome Lists](#related-awesome-lists)
  - [Communities](#communities)
  - [Frontends](#frontends)
  - [Influential Books](#influential-books)
  - [Podcasts and Screencasts](#podcasts-and-screencasts)
  - [People](#people)
  - [Websites](#websites)
- [Contributing](#contributing)

## Projects

### Bean Mapping

_Frameworks that ease bean mapping._

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [dOOv](https://github.com/doov-io/doov)) - Provides fluent API for typesafe domain model validation and mapping. It uses annotations, code generation and a type safe DSL to make bean validation and mapping fast and easy.
- <b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [JMapper](https://github.com/jmapper-framework/jmapper-core)) - Uses byte code manipulation for lightning-fast mapping. Supports annotations and API or XML configuration.
- <b><code>&nbsp;&nbsp;6752⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;903🍴</code></b> [MapStruct](https://github.com/mapstruct/mapstruct)) - Code generator that simplifies mappings between different bean types, based on a convention-over-configuration approach.
- <b><code>&nbsp;&nbsp;2224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;342🍴</code></b> [ModelMapper](https://github.com/modelmapper/modelmapper)) - Intelligent object mapping library that automatically maps objects to each other.
- <b><code>&nbsp;&nbsp;1284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [Orika](https://github.com/orika-mapper/orika)) - JavaBean-mapping framework that recursively copies (among other capabilities) data from one object to another.
- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [reMap](https://github.com/remondis-it/remap)) - Lambda and method handle-based mapping which requires code and not annotations if objects have different names.
- <b><code>&nbsp;&nbsp;&nbsp;211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Selma](https://github.com/xebia-france/selma)) - Annotation processor-based bean mapper.

### Build

_Tools that handle the build cycle and dependencies of an application._

- 🌎 [Apache Maven](maven.apache.org) - Declarative build and dependency management that favors convention over configuration. It might be preferable to Apache Ant, which uses a rather procedural approach and can be difficult to maintain.
- 🌎 [Bazel](bazel.build) - Tool from Google that builds code quickly and reliably.
- <b><code>&nbsp;&nbsp;8572⭐</code></b> <b><code>&nbsp;&nbsp;1161🍴</code></b> [Buck](https://github.com/facebook/buck)) - Encourages the creation of small, reusable modules consisting of code and resources.
- 🌎 [Gradle](gradle.org) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

### Bytecode Manipulation

_Libraries to manipulate bytecode programmatically._

- 🌎 [ASM](asm.ow2.io) - All-purpose, low-level bytecode manipulation and analysis.
- 🌎 [Byte Buddy](bytebuddy.net) - Further simplifies bytecode generation with a fluent API.
- <b><code>&nbsp;14285⭐</code></b> <b><code>&nbsp;&nbsp;1121🍴</code></b> [bytecode-viewer](https://github.com/Konloch/bytecode-viewer)) - Java 8 Jar & Android APK reverse engineering suite. (GPL-3.0-only)
- 🌎 [Byteman](byteman.jboss.org) - Manipulate bytecode at runtime via DSL (rules); mainly for testing/troubleshooting. (LGPL-2.1-or-later)
- <b><code>&nbsp;&nbsp;4729⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;886🍴</code></b> [cglib](https://github.com/cglib/cglib)) - Bytecode generation library.
- <b><code>&nbsp;&nbsp;3999⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;692🍴</code></b> [Javassist](https://github.com/jboss-javassist/javassist)) - Tries to simplify bytecode editing.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Maker](https://github.com/cojen/maker)) - Provides low level bytecode generation.
- <b><code>&nbsp;&nbsp;1304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [Mixin](https://github.com/SpongePowered/Mixin)) - Manipulate bytecode at runtime using real Java code.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Perses](https://github.com/nicolasmanic/perses)) - Dynamically injects failure/latency at the bytecode level according to principles of chaos engineering.
- 🌎 [Recaf](www.coley.software/Recaf/) - JVM reverse engineering toolkit, essentially an IDE for Java bytecode.

### Caching

_Libraries that provide caching facilities._

- 🌎 [cache2k](cache2k.org) - In-memory high performance caching library.
- <b><code>&nbsp;15095⭐</code></b> <b><code>&nbsp;&nbsp;1541🍴</code></b> [Caffeine](https://github.com/ben-manes/caffeine)) - High-performance, near-optimal caching library.
- [Ehcache](http://www.ehcache.org) - Distributed general-purpose cache.
- 🌎 [Infinispan](infinispan.org) - Highly concurrent key/value datastore used for caching.

### CLI

_Libraries for everything related to the CLI._

#### Argument Parsing

_Libraries to assist with parsing command line arguments._

- 🌎 [Airline](rvesse.github.io/airline/) - Annotation-based framework for parsing Git-like command-line arguments.
- [JCommander](http://jcommander.org) - Command-line argument-parsing framework with custom types and validation via implementing interfaces.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [jbock](https://github.com/jbock-java/jbock)) - Reflectionless command line parser.
- <b><code>&nbsp;&nbsp;1377⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [JLine](https://github.com/jline/jline3)) - Includes features from modern shells like completion or history.
- 🌎 [picocli](picocli.info) - ANSI colors and styles in usage help with annotation-based POSIX/GNU/any syntax, subcommands, strong typing for both options and positional args.

#### Text-Based User Interfaces

_Libraries that provide TUI frameworks, or building blocks related functions._

- <b><code>&nbsp;&nbsp;1083⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [Jansi](https://github.com/fusesource/jansi)) - ANSI escape codes to format console output.
- 🌎 [Jexer](gitlab.com/klamonte/jexer) - Advanced console (and Swing) text user interface (TUI) library, with mouse-draggable windows, built-in terminal window manager, and sixel image support. Looks like 🌎 [Turbo Vision](en.wikipedia.org/wiki/Turbo_Vision).
- <b><code>&nbsp;&nbsp;&nbsp;327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Text-IO](https://github.com/beryx/text-io)) - Aids the creation of full console-based applications.
- <b><code>&nbsp;&nbsp;2172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [Lanterna](https://github.com/mabe02/lanterna)) - Easy console text-GUI library, similar to curses. (LGPL-3.0-only)

### Cluster Management

_Frameworks that can dynamically manage applications inside of a cluster._

- 🌎 [Apache Aurora](aurora.apache.org) - Mesos framework for long-running services and cron jobs.
- [Singularity](http://getsingularity.com) - Mesos framework that makes deployment and operations easy. It supports web services, background workers, scheduled jobs, and one-off tasks.

### Code Analysis

_Tools that provide metrics and quality measurements._

- <b><code>&nbsp;&nbsp;8101⭐</code></b> <b><code>&nbsp;&nbsp;3627🍴</code></b> [Checkstyle](https://github.com/checkstyle/checkstyle)) - Static analysis of coding conventions and standards. (LGPL-2.1-or-later)
- <b><code>&nbsp;&nbsp;6699⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;721🍴</code></b> [Error Prone](https://github.com/google/error-prone)) - Catches common programming mistakes as compile-time errors.
- <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Error Prone Support](https://github.com/PicnicSupermarket/error-prone-support)) - Error Prone extensions: extra bug checkers and a large battery of Refaster templates.
- <b><code>&nbsp;14663⭐</code></b> <b><code>&nbsp;&nbsp;2000🍴</code></b> [Infer](https://github.com/facebook/infer)) - Modern static analysis tool for verifying the correctness of code.
- 🌎 [jQAssistant](jqassistant.org) - Static code analysis with Neo4J-based query language. (GPL-3.0-only)
- <b><code>&nbsp;&nbsp;3488⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;282🍴</code></b> [NullAway](https://github.com/uber/NullAway)) - Eliminates NullPointerExceptions with low build-time overhead.
- <b><code>&nbsp;&nbsp;4623⭐</code></b> <b><code>&nbsp;&nbsp;1450🍴</code></b> [PMD](https://github.com/pmd/pmd)) - Source code analysis for finding bad coding practices.
- <b><code>&nbsp;30039⭐</code></b> <b><code>&nbsp;&nbsp;8042🍴</code></b> [p3c](https://github.com/alibaba/p3c)) - Provides Alibaba's coding guidelines for PMD, IDEA and Eclipse.
- <b><code>&nbsp;&nbsp;&nbsp;330⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst)) - Identifies and prioritizes God Classes and Highly Coupled classes.
- <b><code>&nbsp;&nbsp;1083⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;659🍴</code></b> [SonarJava](https://github.com/SonarSource/sonar-java)) - Static analyzer for SonarQube & SonarLint. (LGPL-3.0-only)
- <b><code>&nbsp;&nbsp;1653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;334🍴</code></b> [Spoon](https://github.com/INRIA/spoon)) - Library for analyzing and transforming Java source code.
- <b><code>&nbsp;&nbsp;3317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;569🍴</code></b> [Spotbugs](https://github.com/spotbugs/spotbugs)) - Static analysis of bytecode to find potential bugs. (LGPL-2.1-only)

### Code Coverage

_Frameworks and tools that enable code coverage metrics collection for test suites._

- 🌎 [Clover](www.atlassian.com/software/clover) - Relies on source-code instrumentation instead of bytecode instrumentation.
- 🌎 [Cobertura](cobertura.github.io/cobertura/) - Relies on offline (or static) bytecode instrumentation and class loading to collect code coverage metrics. (GPL-2.0-only)
- 🌎 [JaCoCo](www.eclemma.org/jacoco/) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

### Code Generators

_Tools that generate patterns for repetitive code in order to reduce verbosity and error-proneness._

- <b><code>&nbsp;&nbsp;&nbsp;141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [ADT4J](https://github.com/sviperll/adt4j)) - JSR-269 code generator for algebraic data types.
- <b><code>&nbsp;10348⭐</code></b> <b><code>&nbsp;&nbsp;1178🍴</code></b> [Auto](https://github.com/google/auto)) - Generates factory, service, and value classes.
- 🌎 [Avaje Http Server](avaje.io/http/) - Generates Lightweight JAX-RS style http servers using Javalin or Helidon (Nima) SE.
- [Bootify ![c]](https://bootify.io) - Browser-based Spring Boot app generation with JPA model and REST API.
- <b><code>&nbsp;&nbsp;&nbsp;822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [FreeBuilder](https://github.com/inferred/FreeBuilder)) - Automatically generates the Builder pattern.
- <b><code>&nbsp;&nbsp;&nbsp;128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Geci](https://github.com/verhas/javageci)) - Discovers files that need generated code, updates automatically and writes to the source with a convenient API.
- 🌎 [Immutables](immutables.github.io) - Annotation processors to generate simple, safe and consistent value objects.
- <b><code>&nbsp;10664⭐</code></b> <b><code>&nbsp;&nbsp;1358🍴</code></b> [JavaPoet](https://github.com/square/javapoet)) - API to generate source files.
- <b><code>&nbsp;21182⭐</code></b> <b><code>&nbsp;&nbsp;3987🍴</code></b> [JHipster](https://github.com/jhipster/generator-jhipster)) - Yeoman source code generator for Spring Boot and AngularJS.
- 🌎 [Joda-Beans](www.joda.org/joda-beans/) - Small framework that adds queryable properties to Java, enhancing JavaBeans.
- [JPA Buddy ![c]](https://www.jpa-buddy.com) - Plugin for IntelliJ IDEA. Provides visual tools for generating JPA entities, Spring Data JPA repositories, Liquibase changelogs and SQL scripts. Offers automatic Liquibase/Flyway script generation by comparing model to DB, and reverse engineering JPA entities from DB tables.
- 🌎 [Lombok](projectlombok.org) - Code generator that aims to reduce verbosity.
- <b><code>&nbsp;&nbsp;&nbsp;637⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Record-Builder](https://github.com/Randgalt/record-builder)) - Companion builder class, withers and templates for Java records.
- 🌎 [Telosys](www.telosys.org/) - Simple and light code generator available as an Eclipse Plugin and also as a CLI.

### Compiler-compiler

_Frameworks that help to create parsers, interpreters or compilers._

- 🌎 [ANTLR](www.antlr.org) - Complex full-featured framework for top-down parsing.
- 🌎 [JavaCC](javacc.github.io/javacc/) - Parser generator that generates top-down parsers. Allows lexical state switching and permits extended BNF specifications.
- 🌎 [JFlex](jflex.de) - Lexical analyzer generator.

### Computer Vision

_Libraries which seek to gain high level information from images and videos._

- 🌎 [BoofCV](boofcv.org) - Library for image processing, camera calibration, tracking, SFM, MVS, 3D vision, QR Code and much more.
- 🌎 [ImageJ](imagej.net/ImageJ) - Medical image processing application with an API.
- <b><code>&nbsp;&nbsp;7224⭐</code></b> <b><code>&nbsp;&nbsp;1552🍴</code></b> [JavaCV](https://github.com/bytedeco/javacv)) - Java interface to OpenCV, FFmpeg, and much more.

### Configuration

_Libraries that provide external configuration._

- 🌎 [avaje config](avaje.io/config/) - Loads yaml and properties files, supports dynamic configuration, plugins, file-watching and config event listeners.
- <b><code>&nbsp;&nbsp;&nbsp;576⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [centraldogma](https://github.com/line/centraldogma)) - Highly-available version-controlled service configuration repository based on Git, ZooKeeper and HTTP/2.
- <b><code>&nbsp;&nbsp;6082⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;965🍴</code></b> [config](https://github.com/lightbend/config)) - Configuration library supporting Java properties, JSON or its human optimized superset HOCON.
- <b><code>&nbsp;&nbsp;&nbsp;340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [Configurate](https://github.com/SpongePowered/Configurate)) - Configuration library with support for various configuration formats and transformations.
- 🌎 [Curator Framework](curator.apache.org/) - High-level API for Apache ZooKeeper.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [dotenv](https://github.com/shyiko/dotenv)) - Twelve-factor configuration library which uses environment-specific files.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Externalized Properties](https://github.com/joel-jeremy/externalized-properties)) - Lightweight yet powerful configuration library which supports resolution of properties from external sources and an extensible post-processing/conversion mechanism.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Gestalt](https://github.com/gestalt-config/gestalt)) - Gestalt offers a comprehensive solution to the challenges of configuration management. It allows you to source configuration data from multiple inputs, merge them intelligently, and present them in a structured, type-safe manner.
- [ini4j](http://ini4j.sourceforge.net) - Provides an API for handling Windows' INI files.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [KAConf](https://github.com/mariomac/kaconf)) - Annotation-based configuration system for Java and Kotlin.
- 🌎 [microconfig](microconfig.io) - Configuration system designed for microservices which helps to separate configuration from code. The configuration for different services can have common and specific parts and can be dynamically distributed.
- <b><code>&nbsp;&nbsp;&nbsp;905⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [owner](https://github.com/lviggiano/owner)) - Reduces boilerplate of properties.

### Constraint Satisfaction Problem Solver

_Libraries that help with implementing optimization and satisfiability problems._

- 🌎 [Choco](choco-solver.org) - Off-the-shelf constraint satisfaction problem solver that uses constraint programming techniques.
- <b><code>&nbsp;&nbsp;&nbsp;217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [JaCoP](https://github.com/radsz/jacop)) - Includes an interface for the FlatZinc language, enabling it to execute MiniZinc models. (AGPL-3.0)
- 🌎 [OptaPlanner](www.optaplanner.org) - Business planning and resource scheduling optimization solver.
- 🌎 [Timefold](timefold.ai/docs) - Flexible solver with Spring/Quarkus support and quickstarts for the Vehicle Routing Problem, Maintenance Scheduling, Employee Shift Scheduling and much more.

### CSV

_Frameworks and libraries that simplify reading/writing CSV data._

- <b><code>&nbsp;&nbsp;&nbsp;505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [FastCSV](https://github.com/osiegmar/FastCSV)) - Performance-optimized, dependency-free and RFC 4180 compliant.
- <b><code>&nbsp;&nbsp;&nbsp;193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv)) - Jackson extension for reading and writing CSV.
- [opencsv](http://opencsv.sourceforge.net) - Simple CSV parser.
- 🌎 [Super CSV](super-csv.github.io/super-csv/) - Powerful CSV parser with support for Dozer, Joda-Time and Java 8.
- <b><code>&nbsp;&nbsp;&nbsp;894⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers)) - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed-width records.

### Data Structures

_Efficient and specific data structures._

- 🌎 [Apache Avro](avro.apache.org) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
- 🌎 [Apache Orc](orc.apache.org) - Fast and efficient columnar storage format for Hadoop-based workloads.
- 🌎 [Apache Parquet](parquet.apache.org) - Columnar storage format based on assembly algorithms from Google's paper on Dremel.
- 🌎 [Apache Thrift](thrift.apache.org) - Data interchange format that originated at Facebook.
- <b><code>&nbsp;&nbsp;&nbsp;548⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [Big Queue](https://github.com/bulldog2011/bigqueue)) - Fast and persistent queue based on memory-mapped files.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [HyperMinHash-java](https://github.com/LiveRamp/HyperMinHash-java)) - Probabilistic data structure for computing union, intersection, and set cardinality in loglog space.
- <b><code>&nbsp;&nbsp;&nbsp;745⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Persistent Collection](https://github.com/hrldcpr/pcollections)) - Persistent and immutable analogue of the Java Collections Framework.
- <b><code>&nbsp;63317⭐</code></b> <b><code>&nbsp;15216🍴</code></b> [Protobuf](https://github.com/protocolbuffers/protobuf)) - Google's data interchange format.
- <b><code>&nbsp;&nbsp;3357⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;524🍴</code></b> [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap)) - Fast and efficient compressed bitmap.
- <b><code>&nbsp;&nbsp;3015⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;504🍴</code></b> [SBE](https://github.com/real-logic/simple-binary-encoding)) - Simple Binary Encoding, one of the fastest message formats around.
- <b><code>&nbsp;&nbsp;2459⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;288🍴</code></b> [Tape](https://github.com/square/tape)) - Lightning-fast, transactional, file-based FIFO.
- <b><code>&nbsp;&nbsp;4160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;563🍴</code></b> [Wire](https://github.com/square/wire)) - Clean, lightweight protocol buffers.

### Database

_Everything that simplifies interactions with the database._

- 🌎 [Apache Calcite](calcite.apache.org) - Dynamic data management framework. It contains many of the pieces that comprise a typical database management system.
- 🌎 [Apache Drill](drill.apache.org) - Distributed, schema on-the-fly, ANSI SQL query engine for Big Data exploration.
- 🌎 [Apache Phoenix](phoenix.apache.org) - High-performance relational database layer over HBase for low-latency applications.
- <b><code>&nbsp;&nbsp;&nbsp;196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [ArangoDB](https://github.com/arangodb/arangodb-java-driver)) - ArangoDB Java driver.
- <b><code>&nbsp;&nbsp;2672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;461🍴</code></b> [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map)) - Efficient, in-memory (opt. persisted to disk), off-heap key-value store.
- 🌎 [Debezium](debezium.io/) - Low latency data streaming platform for change data capture.
- 🌎 [druid](druid.apache.org) - High-performance, column-oriented, distributed data store.
- <b><code>&nbsp;&nbsp;&nbsp;405⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [eXist](https://github.com/eXist-db/exist)) - NoSQL document database and application platform. (LGPL-2.1-only)
- <b><code>&nbsp;&nbsp;1041⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [FlexyPool](https://github.com/vladmihalcea/flexy-pool)) - Brings metrics and failover strategies to the most common connection pooling solutions.
- 🌎 [Flyway](flywaydb.org) - Simple database migration tool.
- 🌎 [H2](h2database.com) - Small SQL database notable for its in-memory functionality.
- <b><code>&nbsp;19308⭐</code></b> <b><code>&nbsp;&nbsp;2863🍴</code></b> [HikariCP](https://github.com/brettwooldridge/HikariCP)) - High-performance JDBC connection pool.
- 🌎 [HSQLDB](hsqldb.org/) - HyperSQL 100% Java database.
- [JDBI](http://jdbi.org) - Convenient abstraction of JDBC.
- <b><code>&nbsp;11567⭐</code></b> <b><code>&nbsp;&nbsp;3827🍴</code></b> [Jedis](https://github.com/xetorthio/jedis)) - Small client for interaction with Redis, with methods for commands.
- <b><code>&nbsp;&nbsp;2113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;761🍴</code></b> [Jest](https://github.com/searchbox-io/Jest)) - Client for the Elasticsearch REST API.
- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [jetcd](https://github.com/justinsb/jetcd)) - Client library for etcd.
- <b><code>&nbsp;&nbsp;&nbsp;657⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Jinq](https://github.com/my2iu/Jinq)) - Typesafe database queries via symbolic execution of Java 8 Lambdas (on top of JPA or jOOQ).
- 🌎 [jOOQ](www.jooq.org) - Generates typesafe code based on SQL schema.
- <b><code>&nbsp;&nbsp;6266⭐</code></b> <b><code>&nbsp;&nbsp;1808🍴</code></b> [Leaf](https://github.com/Meituan-Dianping/Leaf)) - Distributed ID generate service.
- 🌎 [Lettuce](lettuce.io/) - Lettuce is a scalable Redis client for building non-blocking Reactive applications.
- [Liquibase](http://www.liquibase.org) - Database-independent library for tracking, managing and applying database schema changes.
- [MapDB](http://www.mapdb.org) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [MariaDB4j](https://github.com/vorburger/MariaDB4j)) - Launcher for MariaDB that requires no installation or external dependencies.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Modality](https://github.com/arkanovicz/modality)) - Lightweight ORM with database reverse engineering features.
- <b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [OpenDJ](https://github.com/OpenIdentityPlatform/OpenDJ)) - LDAPv3 compliant directory service, developed for the Java platform, providing a high performance, highly available, and secure store for the identities.
- [Querydsl](http://www.querydsl.com) - Typesafe unified queries.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [QueryStream](https://github.com/querystream/querystream)) - Build JPA Criteria queries using a Stream-like API.
- <b><code>&nbsp;13374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;970🍴</code></b> [QuestDB](https://github.com/questdb/questdb)) - High-performance SQL database for time series. Supports InfluxDB line protocol, PostgreSQL wire protocol, and REST.
- <b><code>&nbsp;11437⭐</code></b> <b><code>&nbsp;&nbsp;1752🍴</code></b> [Realm](https://github.com/realm/realm-java)) - Mobile database to run directly inside phones, tablets or wearables.
- <b><code>&nbsp;22585⭐</code></b> <b><code>&nbsp;&nbsp;5248🍴</code></b> [Redisson](https://github.com/redisson/redisson)) - Allows for distributed and scalable data structures on top of a Redis server.
- <b><code>&nbsp;&nbsp;3133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;245🍴</code></b> [requery](https://github.com/requery/requery)) - Modern, lightweight but powerful object mapping and SQL generator. Easily map to or create databases, or perform queries and updates from any Java-using platform.
- <b><code>&nbsp;&nbsp;2076⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [Speedment](https://github.com/speedment/speedment)) - Database access library that utilizes Java 8's Stream API for querying.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Spring Data JPA MongoDB Expressions](https://github.com/mhewedy/spring-data-jpa-mongodb-expressions)) - Allows you to use MongoDB query language to query your relational database.
- 🌎 [Trino](trino.io) - Distributed SQL query engine for big data.
- 🌎 [Vibur DBCP](www.vibur.org) - JDBC connection pool library with advanced performance monitoring capabilities.
- <b><code>&nbsp;&nbsp;1156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Xodus](https://github.com/JetBrains/xodus)) - Highly concurrent transactional schema-less and ACID-compliant embedded database.
- <b><code>&nbsp;&nbsp;&nbsp;417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [CosId](https://github.com/Ahoo-Wang/CosId)) - Universal, flexible, high-performance distributed ID generator.

### Date and Time

_Libraries related to handling date and time._

- <b><code>&nbsp;&nbsp;&nbsp;712⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [iCal4j](https://github.com/ical4j/ical4j)) - Parse and build iCalendar 🌎 [RFC 5545](tools.ietf.org/html/rfc5545) data models.
- <b><code>&nbsp;&nbsp;&nbsp;188⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Jollyday](https://github.com/svendiedrichsen/jollyday)) - Determines the holidays for a given year, country/name and eventually state/region.
- <b><code>&nbsp;&nbsp;&nbsp;386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra)) - Additional date-time classes that complement those in JDK 8.
- <b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Time4J](https://github.com/MenoData/Time4J)) - Advanced date and time library. (LGPL-2.1-only)

### Dependency Injection

_Libraries that help to realize the 🌎 [Inversion of Control](en.wikipedia.org/wiki/Inversion_of_control) paradigm._

- 🌎 [Apache DeltaSpike](deltaspike.apache.org) - CDI extension framework.
- 🌎 [Avaje Inject](avaje.io/inject/) - Microservice-focused compile-time injection framework without reflection.
- 🌎 [Dagger](dagger.dev/) - Compile-time injection framework without reflection.
- <b><code>&nbsp;&nbsp;&nbsp;354⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Feather](https://github.com/zsoltherpai/feather)) - Ultra-lightweight, JSR-330-compliant dependency injection library.
- <b><code>&nbsp;&nbsp;&nbsp;822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [Governator](https://github.com/Netflix/governator)) - Extensions and utilities that enhance Google Guice.
- <b><code>&nbsp;12324⭐</code></b> <b><code>&nbsp;&nbsp;1651🍴</code></b> [Guice](https://github.com/google/guice)) - Lightweight and opinionated framework that completes Dagger.
- 🌎 [HK2](javaee.github.io/hk2/) - Lightweight and dynamic dependency injection framework.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [JayWire](https://github.com/vanillasource/jaywire)) - Lightweight dependency injection framework. (LGPL-3.0-only)

### Development

_Augmentation of the development process at a fundamental level._

- 🌎 [AspectJ](www.eclipse.org/aspectj/) - Seamless aspect-oriented programming extension.
- 🌎 [DCEVM](dcevm.github.io) - JVM modification that allows unlimited redefinition of loaded classes at runtime. (GPL-2.0-only)
- <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Faux Pas](https://github.com/zalando/faux-pas)) - Library that simplifies error handling by circumventing the issue that none of the functional interfaces in the Java Runtime is allowed by default to throw checked exceptions.
- <b><code>&nbsp;&nbsp;2191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;475🍴</code></b> [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent)) - Unlimited runtime class and resource redefinition. (GPL-2.0-only)
- <b><code>&nbsp;&nbsp;5172⭐</code></b> <b><code>&nbsp;&nbsp;1100🍴</code></b> [JavaParser](https://github.com/javaparser/javaparser)) - Parse, modify and generate Java code.
- <b><code>&nbsp;&nbsp;&nbsp;291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver)) - Symbol solver.
- <b><code>&nbsp;&nbsp;2177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [Manifold](https://github.com/manifold-systems/manifold)) - Re-energizes Java with powerful features like type-safe metaprogramming, structural typing and extension methods.
- 🌎 [NoException](noexception.machinezoo.com) - Allows checked exceptions in functional interfaces and converts exceptions to Optional return.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow)) - Ignores checked exceptions without bytecode manipulation. Can also be used inside Java 8 stream operations.
- 🌎 [Tail](nrktkt.github.io/tail/) - Enable infinite recursion using tail call optimization.

### Distributed Applications

_Libraries and frameworks for writing distributed and fault-tolerant applications._

- 🌎 [Apache Geode](geode.apache.org) - In-memory data management system that provides reliable asynchronous event notifications and guaranteed message delivery.
- 🌎 [Apache Storm](storm.apache.org) - Realtime computation system.
- 🌎 [Apache ZooKeeper](zookeeper.apache.org) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
- 🌎 [Atomix](atomix.io) - Fault-tolerant distributed coordination framework.
- 🌎 [Axon](axoniq.io) - Framework for creating CQRS applications.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker)) - Circuit breaker design pattern for Dropwizard. (GPL-2.0-only)
- <b><code>&nbsp;&nbsp;4079⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Failsafe](https://github.com/jhalterman/failsafe)) - Simple failure handling with retries and circuit breakers.
- <b><code>&nbsp;&nbsp;5823⭐</code></b> <b><code>&nbsp;&nbsp;1785🍴</code></b> [Hazelcast](https://github.com/hazelcast/hazelcast)) - Highly scalable in-memory datagrid with a free open-source version.
- [JGroups](http://www.jgroups.org) - Toolkit for reliable messaging and cluster creation.
- [Quasar](http://docs.paralleluniverse.co/quasar/) - Lightweight threads and actors for the JVM.
- <b><code>&nbsp;&nbsp;9372⭐</code></b> <b><code>&nbsp;&nbsp;1285🍴</code></b> [resilience4j](https://github.com/resilience4j/resilience4j)) - Functional fault tolerance library.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [OpenIG](https://github.com/OpenIdentityPlatform/OpenIG)) - High-performance reverse proxy server with specialized session management and credential replay functionality.
- <b><code>&nbsp;&nbsp;&nbsp;599⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [ScaleCube Services](https://github.com/scalecube/scalecube-services)) - Embeddable Cluster-Membership library based on SWIM and gossip protocol.
- <b><code>&nbsp;13126⭐</code></b> <b><code>&nbsp;&nbsp;2319🍴</code></b> [Zuul](https://github.com/Netflix/zuul)) - Gateway service that provides dynamic routing, monitoring, resiliency, security, and more.

### Distributed Transactions

_Distributed transactions provide a mechanism for ensuring consistency of data updates in the presence of concurrent access and partial failures._

- 🌎 [Atomikos](www.atomikos.com) - Provides transactions for REST, SOA and microservices with support for JTA and XA.
- <b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [Bitronix](https://github.com/bitronix/btm)) - Simple but complete implementation of the JTA 1.1 API.
- 🌎 [Narayana](narayana.io) - Provides support for traditional ACID and compensation transactions, also complies with JTA, JTS and other standards. (LGPL-2.1-only)
- <b><code>&nbsp;24876⭐</code></b> <b><code>&nbsp;&nbsp;8647🍴</code></b> [Seata](https://github.com/seata/seata)) - Delivers high performance and easy to use distributed transaction services under a microservices architecture.

### Distribution

_Tools that handle the distribution of applications in native formats._

- <b><code>&nbsp;&nbsp;&nbsp;449⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Artipie](https://github.com/artipie/artipie)) - Binary artifact management toolkit which hosts them on the file system or S3.
- [Boxfuse ![c]](https://boxfuse.com) - Deployment of JVM applications to AWS using the principles of immutable infrastructure.
- <b><code>&nbsp;&nbsp;1148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [Capsule](https://github.com/puniverse/capsule)) - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.
- 🌎 [Central Repository](search.maven.org) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
- [Cloudsmith ![c]](https://cloudsmith.io) - Fully managed package management SaaS with support for Maven/Gradle/SBT with a free tier.
- <b><code>&nbsp;&nbsp;&nbsp;494⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [Getdown](https://github.com/threerings/getdown)) - System for deploying Java applications to end-user computers and keeping them up to date. Developed as an alternative to Java Web Start.
- [IzPack](http://izpack.org) - Setup authoring tool for cross-platform deployments.
- <b><code>&nbsp;&nbsp;&nbsp;931⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;125🍴</code></b> [JavaPackager](https://github.com/fvarrui/JavaPackager)) - Maven and Gradle plugin which provides an easy way to package Java applications in native Windows, macOS or GNU/Linux executables, and generate installers for them.
- 🌎 [jDeploy](www.jdeploy.com) - Deploy desktop apps as native Mac, Windows or Linux bundles.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [jlink.online](https://github.com/AdoptOpenJDK/jlink.online)) - Builds optimized runtimes over HTTP.
- [Nexus ![c]](https://www.sonatype.com) - Binary management with proxy and caching capabilities.
- <b><code>&nbsp;&nbsp;2525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [packr](https://github.com/libgdx/packr)) - Packs JARs, assets and the JVM for native distribution on Windows, Linux and macOS.
- <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin)) - Maven plugin for making self-executing JARs.

### Document Processing

_Libraries that assist with processing office document formats._

- 🌎 [Apache POI](poi.apache.org) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
- 🌎 [documents4j](documents4j.com/#/) - API for document format conversion using third-party converters such as MS Word.
- 🌎 [docx4j](www.docx4java.org/trac/docx4j) - Create and manipulate Microsoft Open XML files.
- <b><code>&nbsp;&nbsp;&nbsp;595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [fastexcel](https://github.com/dhatim/fastexcel)) - High performance library to read and write large Excel (XLSX) worksheets.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [zerocell](https://github.com/creditdatamw/zerocell)) - Annotation-based API for reading data from Excel sheets into POJOs with focus on reduced overhead.

### Financial

_Libraries related to the financial domain._

- <b><code>&nbsp;&nbsp;&nbsp;547⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [Cassandre](https://github.com/cassandre-tech/cassandre-trading-bot)) - Trading bot framework.
- <b><code>&nbsp;&nbsp;&nbsp;501⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [Parity](https://github.com/paritytrading/parity)) - Platform for trading venues.
- <b><code>&nbsp;&nbsp;&nbsp;307⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Philadelphia](https://github.com/paritytrading/philadelphia)) - Low-latency financial information exchange.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Square](https://github.com/square/connect-java-sdk)) - Integration with the Square API.
- <b><code>&nbsp;&nbsp;&nbsp;744⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;353🍴</code></b> [Stripe](https://github.com/stripe/stripe-java)) - Integration with the Stripe API.
- <b><code>&nbsp;&nbsp;1942⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;685🍴</code></b> [ta4j](https://github.com/ta4j/ta4j)) - Library for technical analysis.

### Formal Verification

_Formal-methods tools: proof assistants, model checking, symbolic execution, etc._

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [CATG](https://github.com/ksen007/janala2)) - Concolic unit testing engine. Automatically generates unit tests using formal methods.
- 🌎 [Checker Framework](checkerframework.org) - Pluggable type systems. Includes nullness types, physical units, immutability types and more. (GPL-2.0-only WITH Classpath-exception-2.0)
- 🌎 [Daikon](plse.cs.washington.edu/daikon/) - Detects likely program invariants and generates JML specs based on those invariants.
- <b><code>&nbsp;&nbsp;&nbsp;495⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;325🍴</code></b> [Java Path Finder (JPF)](https://github.com/javapathfinder/jpf-core)) - JVM formal verification tool containing a model checker and more. Created by NASA.
- 🌎 [JMLOK 2.0](massoni.computacao.ufcg.edu.br/home/jmlok) - Detects inconsistencies between code and JML specification through feedback-directed random tests generation, and suggests a likely cause for each nonconformance detected. (GPL-3.0-only)
- 🌎 [KeY](www.key-project.org) - Formal software development tool that aims to integrate design, implementation, formal specification, and formal verification of object-oriented software as seamlessly as possible. Uses JML for specification and symbolic execution for verification. (GPL-2.0-or-later)
- [OpenJML](http://www.openjml.org) - Translates JML specifications into SMT-LIB format and passes the proof problems implied by the program to backend solvers. (GPL-2.0-only)

### Functional Programming

_Libraries that facilitate functional programming._

- <b><code>&nbsp;&nbsp;1297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Cyclops](https://github.com/aol/cyclops)) - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more.
- <b><code>&nbsp;&nbsp;&nbsp;557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [derive4j](https://github.com/derive4j/derive4j)) - Java 8 annotation processor and framework for deriving algebraic data types constructors, pattern-matching and morphisms. (GPL-3.0-only)
- 🌎 [Fugue](bitbucket.org/atlassian/fugue) - Functional extensions to Guava.
- [Functional Java](http://www.functionaljava.org) - Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
- <b><code>&nbsp;&nbsp;2056⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [jOOλ](https://github.com/jOOQ/jOOL)) - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions.
- <b><code>&nbsp;&nbsp;&nbsp;477⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [protonpack](https://github.com/poetix/protonpack)) - Collection of stream utilities.
- <b><code>&nbsp;&nbsp;2139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [StreamEx](https://github.com/amaembo/streamex)) - Enhances Java 8 Streams.
- 🌎 [Vavr](www.vavr.io) - Functional component library that provides persistent data types and functional control structures.

### Game Development

_Frameworks that support the development of games._

- 🌎 [FXGL](almasb.github.io/FXGL/) - JavaFX Game Development Framework.
- [JBox2D](http://www.jbox2d.org/) - Port of the renowned C++ 2D physics engine.
- 🌎 [jMonkeyEngine](jmonkeyengine.org) - Game engine for modern 3D development.
- 🌎 [libGDX](libgdx.com) - All-round cross-platform, high-level framework.
- 🌎 [Litiengine](litiengine.com/) - AWT-based, lightweight 2D game engine.
- 🌎 [LWJGL](www.lwjgl.org) - Robust framework that abstracts libraries like OpenGL/CL/AL.
- 🌎 [Mini2Dx](mini2dx.org) - Beginner-friendly, master-ready framework for rapidly prototyping and building 2D games.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Void2D](https://github.com/xzripper/Void2D)) - High-level 2D game engine with built-in physics based on Swing.

### Geospatial

_Libraries for working with geospatial data and algorithms._

- 🌎 [Apache SIS](sis.apache.org) - Library for developing geospatial applications.
- [ArcGIS Maps SDK for Java ![c]](https://github.com/Esri/arcgis-maps-sdk-java-samples/) - JavaFX library for adding mapping and GIS functionality to desktop apps.
- <b><code>&nbsp;&nbsp;&nbsp;405⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Geo](https://github.com/davidmoten/geo)) - GeoHash utilities in Java.
- 🌎 [GeoTools](geotools.org) - Library that provides tools for geospatial data. (LGPL-2.1-only)
- <b><code>&nbsp;&nbsp;4627⭐</code></b> <b><code>&nbsp;&nbsp;1499🍴</code></b> [GraphHopper](https://github.com/graphhopper/graphhopper)) - Road-routing engine. Used as a Java library or standalone web service.
- [H2GIS](http://www.h2gis.org) - Spatial extension of the H2 database. (LGPL-3.0-only)
- 🌎 [Jgeohash](astrapi69.github.io/jgeohash/) - Library for using the GeoHash algorithm.
- <b><code>&nbsp;&nbsp;1136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;378🍴</code></b> [Mapsforge](https://github.com/mapsforge/mapsforge)) - Map rendering based on OpenStreetMap data. (LGPL-3.0-only)
- <b><code>&nbsp;&nbsp;&nbsp;926⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [Spatial4j](https://github.com/locationtech/spatial4j)) - General-purpose spatial/geospatial library.

### GUI

_Libraries to create modern graphical user interfaces._

- 🌎 [JavaFX](wiki.openjdk.java.net/display/OpenJFX/Main) - Successor of Swing.
- 🌎 [Scene Builder](gluonhq.com/products/scene-builder/) - Visual layout tool for JavaFX applications.
- <b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [SnapKit](https://github.com/reportmill/SnapKit)) - Modern Java UI library for both desktop and web.
- 🌎 [SWT](www.eclipse.org/swt/) - Graphical widget toolkit.

### High Performance

_Everything about high-performance computation, from collections to specific libraries._

- <b><code>&nbsp;&nbsp;2726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;386🍴</code></b> [Agrona](https://github.com/real-logic/Agrona)) - Data structures and utility methods that are common in high-performance applications.
- 🌎 [Disruptor](lmax-exchange.github.io/disruptor/) - Inter-thread messaging library.
- <b><code>&nbsp;&nbsp;2343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;574🍴</code></b> [Eclipse Collections](https://github.com/eclipse/eclipse-collections)) - Collections framework inspired by Smalltalk.
- [fastutil](http://fastutil.di.unimi.it) - Fast and compact type-specific collections.
- 🌎 [HPPC](labs.carrotsearch.com/hppc.html) - Primitive collections.
- <b><code>&nbsp;&nbsp;3455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;544🍴</code></b> [JCTools](https://github.com/JCTools/JCTools)) - Concurrency tools currently missing from the JDK.
- <b><code>&nbsp;&nbsp;&nbsp;994⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [Koloboke](https://github.com/leventov/Koloboke)) - Carefully designed extension of the Java Collections Framework with primitive specializations and more.

### HTTP Clients

_Libraries that assist with creating HTTP requests and/or binding responses._

- 🌎 [Apache HttpComponents](hc.apache.org/) - Toolset of low-level Java components focused on HTTP and associated protocols.
- <b><code>&nbsp;&nbsp;6226⭐</code></b> <b><code>&nbsp;&nbsp;1583🍴</code></b> [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)) - Asynchronous HTTP and WebSocket client library.
- 🌎 [Avaje Http Client](avaje.io/http-client) - Wrapper on JDK 11's HttpClient that adds Feign-like interface among other enhancements.
- <b><code>&nbsp;&nbsp;9233⭐</code></b> <b><code>&nbsp;&nbsp;1895🍴</code></b> [Feign](https://github.com/OpenFeign/feign)) - HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket.
- <b><code>&nbsp;&nbsp;1361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;441🍴</code></b> [Google HTTP Client](https://github.com/googleapis/google-http-java-client)) - Pluggable HTTP transport abstraction with support for java.net.HttpURLConnection, Apache HTTP Client, Android, Google App Engine, XML, Gson, Jackson and Protobuf.
- <b><code>&nbsp;&nbsp;&nbsp;210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [methanol](https://github.com/mizosoft/methanol)) - HTTP client extensions library.
- 🌎 [Retrofit](square.github.io/retrofit/) - Typesafe REST client.
- <b><code>&nbsp;&nbsp;4513⭐</code></b> <b><code>&nbsp;&nbsp;1231🍴</code></b> [Ribbon](https://github.com/Netflix/ribbon)) - Client-side IPC library that is battle-tested in the cloud.
- <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Riptide](https://github.com/zalando/riptide)) - Client-side response routing for Spring's RestTemplate.
- <b><code>&nbsp;&nbsp;2552⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;592🍴</code></b> [unirest-java](https://github.com/Kong/unirest-java)) - Simplified, lightweight HTTP client library.

### Hypermedia Types

_Libraries that handle serialization to hypermedia types._

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [hate](https://github.com/blackdoor/hate)) - Builds hypermedia-friendly objects according to HAL specification.
- <b><code>&nbsp;&nbsp;&nbsp;371⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [JSON-LD](https://github.com/jsonld-java/jsonld-java)) - JSON-LD implementation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Siren4J](https://github.com/eserating-chwy/siren4j)) - Library for the Siren specification.

### IDE

_Integrated development environments that try to simplify several aspects of development._

- 🌎 [Eclipse](www.eclipse.org) - Established open-source project with support for lots of plugins and languages.
- [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea/) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
- 🌎 [jGRASP](www.jgrasp.org) - Created to provide software visualizations that work in conjunction with the debugger such as Control Structure Diagrams, UML class diagrams and Object Viewer.
- 🌎 [NetBeans](netbeans.apache.org) - Provides integration for several Java SE and EE features, from database access to HTML5.
- 🌎 [SnapCode](reportmill.com/SnapCode/) - Modern IDE for Java running in the browser, focused on education.
- 🌎 [Visual Studio Code](code.visualstudio.com/docs/languages/java) - Provides Java support for lightweight projects with a simple, modern workflow by using extensions from the internal marketplace.

### Imagery

_Libraries that assist with the creation, evaluation or manipulation of graphical images._

- <b><code>&nbsp;&nbsp;1198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;244🍴</code></b> [Imgscalr](https://github.com/rkalla/imgscalr)) - Simple, efficient and hardware-accelerated image-scaling library implemented in pure Java 2D.
- <b><code>&nbsp;&nbsp;1513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;372🍴</code></b> [Tess4J](https://github.com/nguyenq/tess4j)) - JNA wrapper for Tesseract OCR API.
- <b><code>&nbsp;&nbsp;4978⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;780🍴</code></b> [Thumbnailator](https://github.com/coobird/thumbnailator)) - High-quality thumbnail generation library.
- <b><code>&nbsp;&nbsp;1779⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;304🍴</code></b> [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys)) - Collection of plugins that extend the number of supported image file formats.
- <b><code>&nbsp;32138⭐</code></b> <b><code>&nbsp;&nbsp;9284🍴</code></b> [ZXing](https://github.com/zxing/zxing)) - Multi-format 1D/2D barcode image processing library.
- <b><code>&nbsp;&nbsp;&nbsp;323⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [image-comparison](https://github.com/romankh3/image-comparison)) - Library that compares 2 images with the same sizes and shows the differences visually by drawing rectangles. Some parts of the image can be excluded from the comparison.

### Introspection

_Libraries that help make the Java introspection and reflection API easier and faster to use._

- <b><code>&nbsp;&nbsp;2622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;272🍴</code></b> [ClassGraph](https://github.com/classgraph/classgraph)) - ClassGraph (formerly FastClasspathScanner) is an uber-fast, ultra-lightweight, parallelized classpath scanner and module scanner for Java, Scala, Kotlin and other JVM languages.
- <b><code>&nbsp;&nbsp;2769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;380🍴</code></b> [jOOR](https://github.com/jOOQ/jOOR)) - jOOR stands for jOOR Object Oriented Reflection. It is a simple wrapper for the java.lang.reflect package.
- [Mirror](http://projetos.vidageek.net/mirror/mirror/) - Mirror was created to bring light to a simple problem, usually named ReflectionUtil, which is on almost all projects that rely on reflection to do advanced tasks.
- [Objenesis](http://objenesis.org) - Allows dynamic instantiation without default constructor, e.g. constructors which have required arguments, side effects or throw exceptions.
- <b><code>&nbsp;&nbsp;1492⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [ReflectASM](https://github.com/EsotericSoftware/reflectasm)) - ReflectASM is a very small Java library that provides high performance reflection by using code generation.
- <b><code>&nbsp;&nbsp;4654⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;691🍴</code></b> [Reflections](https://github.com/ronmamo/reflections)) - Reflections scans your classpath, indexes the metadata, allows you to query it on runtime and may save and collect that information for many modules within your project.

### Job Scheduling

_Libraries for scheduling background jobs._

- <b><code>&nbsp;&nbsp;2106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [JobRunr](https://github.com/jobrunr/jobrunr)) - Job scheduling library which utilizes lambdas for fire-and-forget, delayed and recurring jobs. Guarantees execution by single scheduler instance using optimistic locking. Has features for persistence, minimal dependencies and is embeddable.
- <b><code>&nbsp;&nbsp;6030⭐</code></b> <b><code>&nbsp;&nbsp;1887🍴</code></b> [Quartz](https://github.com/quartz-scheduler/quartz)) - Feature-rich, open source job scheduling library that can be integrated within virtually any Java application.
- <b><code>&nbsp;&nbsp;&nbsp;264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Sundial](https://github.com/knowm/Sundial)) - Lightweight framework to simply define jobs, define triggers and start the scheduler.
- <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Wisp](https://github.com/Coreoz/Wisp)) - Simple library with minimal footprint and straightforward API.
- <b><code>&nbsp;&nbsp;1095⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [db-scheduler](https://github.com/kagkarlsson/db-scheduler)) - Persistent and cluster-friendly scheduler.
- <b><code>&nbsp;&nbsp;&nbsp;601⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [easy-batch](https://github.com/j-easy/easy-batch)) - Set up batch jobs with simple processing pipelines. Records are read in sequence from a data source, processed in pipeline and written in batches to a data sink.
- <b><code>&nbsp;&nbsp;3347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;486🍴</code></b> [shedlock](https://github.com/lukas-krecan/ShedLock)) - Makes sure that your scheduled tasks are executed at most once at the same time. If a task is being executed on one node, it acquires a lock which prevents execution of the same task from another node or thread.

### JSON

_Libraries for serializing and deserializing JSON to and from Java objects._

- 🌎 [Avaje Jsonb](avaje.io/jsonb/) - Reflection-free Json binding via source code generation with Jackson-like annotations.
- <b><code>&nbsp;&nbsp;&nbsp;983⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [DSL-JSON](https://github.com/ngs-doo/dsl-json)) - JSON library with advanced compile time databinding.
- [Genson](http://genson.io) - Powerful and easy-to-use Java-to-JSON conversion library.
- <b><code>&nbsp;22901⭐</code></b> <b><code>&nbsp;&nbsp;4257🍴</code></b> [Gson](https://github.com/google/gson)) - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage.
- <b><code>&nbsp;&nbsp;&nbsp;458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [HikariJSON](https://github.com/brettwooldridge/HikariJSON)) - High-performance JSON parser, 2x faster than Jackson.
- <b><code>&nbsp;&nbsp;&nbsp;393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8)) - Set of Jackson modules for Java 8 datatypes and features.
- <b><code>&nbsp;&nbsp;&nbsp;242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money)) - Open-source Jackson module to support JSON serialization and deserialization of JavaMoney data types.
- <b><code>&nbsp;&nbsp;8758⭐</code></b> <b><code>&nbsp;&nbsp;1179🍴</code></b> [Jackson](https://github.com/FasterXML/jackson)) - Similar to GSON, but offers performance gains if you need to instantiate the library more often.
- <b><code>&nbsp;&nbsp;&nbsp;316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [JSON-io](https://github.com/jdereg/json-io)) - Convert Java to JSON. Convert JSON to Java. Pretty print JSON. Java JSON serializer.
- [jsoniter](http://jsoniter.com) - Fast and flexible library with iterator and lazy parsing API.
- <b><code>&nbsp;&nbsp;3214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;308🍴</code></b> [LoganSquare](https://github.com/bluelinelabs/LoganSquare)) - JSON parsing and serializing library based on Jackson's streaming API. Outperforms GSON & Jackson's library.
- <b><code>&nbsp;&nbsp;9465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;735🍴</code></b> [Moshi](https://github.com/square/moshi)) - Modern JSON library, less opinionated and uses built-in types like List and Map.
- <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Yasson](https://github.com/eclipse-ee4j/yasson)) - Binding layer between classes and JSON documents similar to JAXB.
- <b><code>&nbsp;25609⭐</code></b> <b><code>&nbsp;&nbsp;6515🍴</code></b> [fastjson](https://github.com/alibaba/fastjson)) - Very fast processor with no additional dependencies and full data binding.
- <b><code>&nbsp;&nbsp;1496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [Jolt](https://github.com/bazaarvoice/jolt)) - JSON to JSON transformation tool.
- <b><code>&nbsp;&nbsp;8571⭐</code></b> <b><code>&nbsp;&nbsp;1608🍴</code></b> [JsonPath](https://github.com/json-path/JsonPath)) - Extract data from JSON using XPATH-like syntax.
- <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [JsonSurfer](https://github.com/jsurfer/JsonSurfer)) - Streaming JsonPath processor dedicated to processing big and complicated JSON data.

### JVM and JDK

_Current implementations of the JVM/JDK._

- 🌎 [Adopt Open JDK](adoptopenjdk.net) - Community-driven OpenJDK builds, including both HotSpot and OpenJ9.
- <b><code>&nbsp;&nbsp;1216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [Avian](https://github.com/ReadyTalk/avian)) - JVM with JIT, AOT modes and iOS port.
- 🌎 [Corretto](aws.amazon.com/corretto/) - No-cost, multiplatform, production-ready distribution of OpenJDK by Amazon. (GPL-2.0-only WITH Classpath-exception-2.0)
- <b><code>&nbsp;&nbsp;4092⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;489🍴</code></b> [Dragonwell8](https://github.com/alibaba/dragonwell8)) - Downstream version of OpenJDK optimized for online e-commerce, financial, logistics applications.
- <b><code>&nbsp;19701⭐</code></b> <b><code>&nbsp;&nbsp;1573🍴</code></b> [Graal](https://github.com/oracle/graal)) - Polyglot embeddable JVM. (GPL-2.0-only WITH Classpath-exception-2.0)
- 🌎 [Liberica JDK](bell-sw.com) - Built from OpenJDK, thoroughly tested and passed the JCK. (GPL-2.0-only WITH Classpath-exception-2.0)
- <b><code>&nbsp;&nbsp;3212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;695🍴</code></b> [OpenJ9](https://github.com/eclipse/openj9)) - High performance, enterprise-calibre, flexibly licensed, openly-governed cross-platform JVM extending and augmenting the runtime technology components from the Eclipse OMR and OpenJDK project.
- 🌎 [Open JDK](openjdk.java.net) - Open JDK community home. (GPL-2.0-only WITH Classpath-exception-2.0)
- <b><code>&nbsp;&nbsp;1635⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;392🍴</code></b> [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm)) - VM with non-blocking, concurrent GC for iOS. (GPL-2.0-only WITH Classpath-exception-2.0)
- 🌎 [RedHat Open JDK](developers.redhat.com/products/openjdk/overview) - RedHat's OpenJDK distribution. (GPL-2.0-only WITH Classpath-exception-2.0)
- 🌎 [SAP Machine](sap.github.io/SapMachine/) - SAP's no-cost, rigorously tested and JCK-verified OpenJDK friendly fork. (GPL-2.0-only WITH Classpath-exception-2.0)
- 🌎 [Zulu](www.azul.com/products/zulu-community/) - OpenJDK builds for Windows, Linux, and macOS. (GPL-2.0-only WITH Classpath-exception-2.0)
- <b><code>&nbsp;&nbsp;&nbsp;304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Microsoft JDK](https://github.com/microsoft/openjdk)) - Microsoft Build of OpenJDK, Free, Open Source, Freshly Brewed!

### Logging

_Libraries that log the behavior of an application._

- 🌎 [Apache Log4j 2](logging.apache.org/log4j/) - Complete rewrite with a powerful plugin and configuration architecture.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Echopraxia](https://github.com/tersesystems/echopraxia)) - API designed around structured logging, rich context, and conditional logging. There are Logback and Log4J2 implementations, but Echopraxia's API is completely dependency-free, meaning it can be implemented with any logging API.
- 🌎 [Graylog](www.graylog.org) - Open-source aggregator suited for extended role and permission management. (GPL-3.0-only)
- 🌎 [Kibana](www.elastic.co/kibana) - Analyzes and visualizes log files. Some features require payment.
- [Logback](http://logback.qos.ch) - Robust logging library with interesting configuration options via Groovy.
- <b><code>&nbsp;&nbsp;1700⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Logbook](https://github.com/zalando/logbook)) - Extensible, open-source library for HTTP request and response logging.
- 🌎 [Logstash](www.elastic.co/logstash) - Tool for managing log files.
- <b><code>&nbsp;&nbsp;1981⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;313🍴</code></b> [p6spy](https://github.com/p6spy/p6spy)) - Enables logging for all JDBC transactions without changes to the code.
- [SLF4J](http://www.slf4j.org) - Abstraction layer/simple logging facade.
- 🌎 [tinylog](tinylog.org/v2/) - Lightweight logging framework with static logger class.
- <b><code>&nbsp;&nbsp;&nbsp;180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [OpenTracing Toolbox](https://github.com/zalando/opentracing-toolbox)) - Collection of libraries that build on top of OpenTracing and provide extensions and plugins to existing instrumentations.

### Machine Learning

_Tools that provide specific statistical algorithms for learning from data._

- 🌎 [Apache Flink](flink.apache.org) - Fast, reliable, large-scale data processing engine.
- 🌎 [Apache Mahout](mahout.apache.org) - Scalable algorithms focused on collaborative filtering, clustering and classification.
- [DatumBox](http://www.datumbox.com) - Provides several algorithms and pre-trained models for natural language processing.
- 🌎 [Deeplearning4j](deeplearning4j.org) - Distributed and multi-threaded deep learning library.
- 🌎 [DJL](djl.ai) - High-level and engine-agnostic framework for deep learning.
- [H2O ![c]](https://www.h2o.ai) - Analytics engine for statistics over big data.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Intelligent java](https://github.com/Barqawiz/IntelliJava)) - Seamlessly integrate with remote deep learning and language models programmatically.
- <b><code>&nbsp;&nbsp;&nbsp;783⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [JSAT](https://github.com/EdwardRaff/JSAT)) - Algorithms for pre-processing, classification, regression, and clustering with support for multi-threaded execution. (GPL-3.0-only)
- <b><code>&nbsp;&nbsp;2700⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [m2cgen](https://github.com/BayesWitnesses/m2cgen)) - CLI tool to transpile models into native code.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Neureka](https://github.com/Gleethos/neureka)) - A lightweight, platform independent, OpenCL accelerated nd-array/tensor library.
- 🌎 [oj! Algorithms](www.ojalgo.org/) - High-performance mathematics, linear algebra and optimisation needed for data science, machine learning and scientific computing.
- <b><code>&nbsp;&nbsp;1788⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;405🍴</code></b> [Oryx 2](https://github.com/OryxProject/oryx)) - Framework for building real-time, large-scale machine learning applications. Includes end-to-end applications for collaborative filtering, classification, regression, and clustering.
- <b><code>&nbsp;&nbsp;1493⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;519🍴</code></b> [Siddhi](https://github.com/siddhi-io/siddhi)) - Cloud native streaming and complex event processing engine.
- <b><code>&nbsp;&nbsp;5901⭐</code></b> <b><code>&nbsp;&nbsp;1117🍴</code></b> [Smile](https://github.com/haifengl/smile)) - Statistical Machine Intelligence and Learning Engine provides a set of machine learning algorithms and a visualization library.
- 🌎 [Tribuo](tribuo.org/) - Provides tools for classification, regression, clustering, model development and interfaces with other libraries such as scikit-learn, pytorch and TensorFlow.
- 🌎 [Weka](www.cs.waikato.ac.nz/ml/weka/) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization. (GPL-3.0-only)

### Messaging

_Tools that help send messages between clients to ensure protocol independency._

- <b><code>&nbsp;&nbsp;7020⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;844🍴</code></b> [Aeron](https://github.com/real-logic/Aeron)) - Efficient, reliable, unicast and multicast message transport.
- 🌎 [Apache ActiveMQ](activemq.apache.org) - Message broker that implements JMS and converts synchronous to asynchronous communication.
- 🌎 [Apache Camel](camel.apache.org) - Glues together different transport APIs via Enterprise Integration Patterns.
- 🌎 [Apache Kafka](kafka.apache.org) - High-throughput distributed messaging system.
- 🌎 [Apache Pulsar](pulsar.apache.org) - Distributed pub/sub-messaging system.
- 🌎 [Apache RocketMQ](rocketmq.apache.org) - Fast, reliable, and scalable distributed messaging platform.
- 🌎 [Apache Qpid](qpid.apache.org) - Apache Qpid makes messaging tools that speak AMQP and support many languages and platforms.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Deezpatch](https://github.com/joel-jeremy/deezpatch)) - Simple, lightweight, and performant dispatch library for decoupling messages (requests and events) and message handlers.
- <b><code>&nbsp;24568⭐</code></b> <b><code>&nbsp;&nbsp;4652🍴</code></b> [EventBus](https://github.com/greenrobot/EventBus)) - Simple publish/subscribe event bus.
- [Hermes](http://hermes.allegro.tech) - Fast and reliable message broker built on top of Kafka.
- <b><code>&nbsp;&nbsp;2313⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;482🍴</code></b> [JeroMQ](https://github.com/zeromq/jeromq)) - Implementation of ZeroMQ.
- <b><code>&nbsp;&nbsp;&nbsp;945⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;290🍴</code></b> [Nakadi](https://github.com/zalando/nakadi)) - Provides a RESTful API on top of Kafka.
- <b><code>&nbsp;&nbsp;1216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;560🍴</code></b> [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client)) - RabbitMQ client.
- <b><code>&nbsp;&nbsp;2364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;879🍴</code></b> [Smack](https://github.com/igniterealtime/Smack)) - Cross-platform XMPP client library.
- <b><code>&nbsp;&nbsp;&nbsp;531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [NATS client](https://github.com/nats-io/nats.java)) - NATS client.

### Microservice

_Tools for creating and managing microservices._

- 🌎 [ActiveRPC](rpc.activej.io) - Lightweight and fast library for complex high-load distributed applications and Memcached-like solutions.
- 🌎 [Apollo](spotify.github.io/apollo/) - Libraries for writing composable microservices.
- <b><code>&nbsp;&nbsp;4644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;868🍴</code></b> [Armeria](https://github.com/line/armeria)) - Asynchronous RPC/REST client/server library built on top of Java 8, Netty, HTTP/2, Thrift and gRPC.
- <b><code>&nbsp;&nbsp;&nbsp;417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [consul-api](https://github.com/Ecwid/consul-api)) - Client for the Consul API: a distributed, highly available and datacenter-aware registry/discovery service.
- <b><code>&nbsp;12183⭐</code></b> <b><code>&nbsp;&nbsp;3709🍴</code></b> [Eureka](https://github.com/Netflix/eureka)) - REST-based service registry for resilient load balancing and failover.
- 🌎 [Helidon](helidon.io) - Two-style approach for writing microservices: Functional-reactive and as an implementation of MicroProfile.
- <b><code>&nbsp;&nbsp;4096⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;715🍴</code></b> [JDA](https://github.com/DV8FromTheWorld/JDA)) - Wrapping of the Discord REST API and its WebSocket events.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [KeenType](https://github.com/DaveJarvis/KeenType)) - Modernized version of a Java-based implementation of the New Typesetting System, which was heavily based on Donald E. Knuth's original TeX.
- <b><code>&nbsp;&nbsp;3277⭐</code></b> <b><code>&nbsp;&nbsp;1431🍴</code></b> [kubernetes-client](https://github.com/fabric8io/kubernetes-client)) - Client provides access to the full Kubernetes & OpenShift REST APIs via a fluent DSL.
- 🌎 [Micronaut](micronaut.io) - Modern full-stack framework with focus on modularity, minimal memory footprint and startup time.
- 🌎 [Nacos](nacos.io) - Dynamic service discovery, configuration and service management platform for building cloud native applications.
- <b><code>&nbsp;&nbsp;4485⭐</code></b> <b><code>&nbsp;&nbsp;1116🍴</code></b> [OpenAI-Java](https://github.com/TheoKanning/openai-java)) - Java libraries for using OpenAI's GPT-3 API.
- 🌎 [Quarkus](quarkus.io) - Kubernetes stack tailored for the HotSpot and Graal VM.
- <b><code>&nbsp;21877⭐</code></b> <b><code>&nbsp;&nbsp;7873🍴</code></b> [Sentinel](https://github.com/alibaba/Sentinel)) - Flow control component enabling reliability, resilience and monitoring for microservices.

### Miscellaneous

_Everything else._

- <b><code>&nbsp;&nbsp;2054⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;773🍴</code></b> [AWS SDK for Java 2.0](https://github.com/aws/aws-sdk-java-v2)) - Wrapper around AWS' API.
- <b><code>&nbsp;&nbsp;1671⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;248🍴</code></b> [CQEngine](https://github.com/npgall/cqengine)) - Ultra-fast, SQL-like queries on Java collections.
- <b><code>&nbsp;86176⭐</code></b> <b><code>&nbsp;25847🍴</code></b> [Design Patterns](https://github.com/iluwatar/java-design-patterns)) - Implementation and explanation of the most common design patterns.
- <b><code>&nbsp;&nbsp;1343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;274🍴</code></b> [FF4J](https://github.com/ff4j/ff4j)) - Feature Flags for Java.
- <b><code>&nbsp;20374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;742🍴</code></b> [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition)) - No-nonsense implementation of FizzBuzz made by serious businessmen for serious business purposes. (No explicit license)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [IP2Location.io Java SDK](https://github.com/ip2location/ip2location-io-java)) - Wrapper for the IP2Location.io Geolocation API and the IP2WHOIS domain WHOIS API.
- <b><code>&nbsp;&nbsp;5976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;953🍴</code></b> [J2ObjC](https://github.com/google/j2objc)) - Java-to-Objective-C translator for porting Android libraries to iOS.
- 🌎 [JBake](jbake.org) - Static website generator.
- <b><code>&nbsp;&nbsp;1200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;351🍴</code></b> [JBot](https://github.com/rampatra/jbot)) - Framework for building chatbots. (GPL-3.0-only)
- [JCuda](http://jcuda.org) - JCuda offers Java bindings for CUDA and CUDA-related libraries.
- <b><code>&nbsp;&nbsp;2371⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [Jimfs](https://github.com/google/jimfs)) - In-memory file system.
- [JObfuscator![c]](https://www.pelock.com/products/jobfuscator) - Source code obfuscator.
- 🌎 [Joda-Money](www.joda.org/joda-money/) - Basic currency and money classes and algorithms not provided by the JDK.
- <b><code>&nbsp;&nbsp;&nbsp;486⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [jOOX](https://github.com/jooq/joox)) - Simple wrapper for the org.w3c.dom package, to allow for fluent XML document creation and manipulation with an API inspired by jQuery.
- [JPad](http://jpad.io) - Snippet runner.
- <b><code>&nbsp;&nbsp;1429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [jsweet](https://github.com/cincheo/jsweet)) - Source transpiler to TypeScript/JavaScript.
- <b><code>&nbsp;&nbsp;1588⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;235🍴</code></b> [Maven Wrapper](https://github.com/takari/maven-wrapper)) - Analogue of Gradle Wrapper for Maven, allows building projects without installing maven.
- <b><code>&nbsp;&nbsp;&nbsp;440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Membrane Service Proxy](https://github.com/membrane/service-proxy)) - Open-source, reverse-proxy framework.
- <b><code>&nbsp;&nbsp;&nbsp;154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [MinimalFTP](https://github.com/Guichaguri/MinimalFTP)) - Lightweight, small and customizable FTP server.
- <b><code>&nbsp;&nbsp;2021⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;776🍴</code></b> [LittleProxy](https://github.com/adamfisk/LittleProxy)) - High performance HTTP proxy atop Netty's event-based networking library.
- <b><code>&nbsp;16586⭐</code></b> <b><code>&nbsp;&nbsp;4022🍴</code></b> [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial)) - Popular Java 8 guide.
- <b><code>&nbsp;&nbsp;&nbsp;354⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Modernizer](https://github.com/gaul/modernizer-maven-plugin)) - Detect uses of legacy Java APIs.
- <b><code>&nbsp;&nbsp;5233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [OctoLinker](https://github.com/OctoLinker/OctoLinker)) - Browser extension which allows to navigate through code on GitHub more efficiently.
- [OpenRefine](http://openrefine.org) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
- <b><code>&nbsp;&nbsp;&nbsp;386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [PipelinR](https://github.com/sizovs/pipelinr)) - Small utility library for using handlers and commands with pipelines.
- <b><code>&nbsp;&nbsp;&nbsp;864⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [Polyglot for Maven](https://github.com/takari/polyglot-maven)) - Extensions for Maven 3.3.1+ that allows writing the POM model in dialects other than XML.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [RR4J](https://github.com/Kartikvk1996/RR4J)) - RR4J is a tool that records java bytecode execution and later allows developers to replay locally.
- <b><code>&nbsp;&nbsp;1168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [Simple Java Mail](https://github.com/bbottema/simple-java-mail)) - Mailing with a clean and fluent API.
- <b><code>&nbsp;&nbsp;&nbsp;380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;354🍴</code></b> [Smooks](https://github.com/smooks/smooks)) - Framework for fragment-based message processing. (Apache-2.0 OR LGPL-3.0-or-later)
- <b><code>&nbsp;&nbsp;2017⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [Svix](https://github.com/svix/svix-webhooks/tree/main/java)) - Library for the Svix API to send webhooks and verify signatures.
- 🌎 [Togglz](www.togglz.org) - Implementation of the Feature Toggles pattern.
- <b><code>&nbsp;&nbsp;&nbsp;605⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [TypeTools](https://github.com/jhalterman/typetools)) - Tools for resolving generic types.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [XMLBeam](https://github.com/SvenEwald/xmlbeam)) - Processes XML by using annotations or XPath within code.
- <b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [yGuard](https://github.com/yWorks/yGuard)) - Obfuscation via renaming and shrinking.

### Mobile Development

_Tools for creating or managing mobile applications._

- 🌎 [Codename One](www.codenameone.com) - Cross-platform solution for writing native mobile apps. (GPL-2.0-only WITH Classpath-exception-2.0)
- 🌎 [MobileUI](mobileui.dev) - Cross-platform framework for developing mobile apps with native UI in Java and Kotlin.
- 🌎 [Multi-OS Engine](multi-os-engine.org) - Open-source, cross-platform engine to develop native mobile (iOS, Android, etc.) apps.

### Monitoring

_Tools that observe/monitor applications in production by providing telemetry._

- <b><code>&nbsp;&nbsp;&nbsp;566⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [Automon](https://github.com/stevensouza/automon)) - Combines the power of AOP with monitoring and/or logging tools.
- [Datadog ![c]](https://github.com/DataDog/dd-trace-java) - Modern monitoring & analytics.
- <b><code>&nbsp;&nbsp;7793⭐</code></b> <b><code>&nbsp;&nbsp;1801🍴</code></b> [Dropwizard Metrics](https://github.com/dropwizard/metrics)) - Expose metrics via JMX or HTTP and send them to a database.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Failsafe Actuator](https://github.com/zalando/failsafe-actuator)) - Out of the box monitoring of Failsafe Circuit Breaker in Spring-Boot environment.
- 🌎 [Glowroot](glowroot.org) - Open-source Java APM.
- <b><code>&nbsp;&nbsp;4418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;768🍴</code></b> [HertzBeat](https://github.com/dromara/hertzbeat)) - Real-time monitoring system with custom-monitor and agentless.
- <b><code>&nbsp;&nbsp;5125⭐</code></b> <b><code>&nbsp;&nbsp;1118🍴</code></b> [hippo4j](https://github.com/opengoofy/hippo4j/blob/develop/README-EN.md)) - Dynamic and observable thread pool framework.
- 🌎 [inspectIT](www.inspectit.rocks) - Captures detailed run-time information via hooks that can be changed on the fly. It supports tracing over multiple systems via the OpenTracing API and can correlate the data with end user monitoring.
- [Instrumental ![c]](https://instrumentalapp.com) - Real-time Java application performance monitoring. A commercial service with free development accounts.
- <b><code>&nbsp;&nbsp;&nbsp;490⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [Jaeger client](https://github.com/jaegertracing/jaeger-client-java)) - Jaeger client.
- <b><code>&nbsp;&nbsp;2898⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;735🍴</code></b> [JavaMelody](https://github.com/javamelody/javamelody)) - Performance monitoring and profiling.
- <b><code>&nbsp;&nbsp;1704⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;505🍴</code></b> [jmxtrans](https://github.com/jmxtrans/jmxtrans)) - Connect to multiple JVMs and query them for their attributes via JMX. Its query language is based on JSON, which allows non-Java programmers to access the JVM attributes. Supports different output writes, including Graphite, Ganglia, and StatsD.
- 🌎 [Jolokia](jolokia.org) - JMX over REST.
- <b><code>&nbsp;&nbsp;4300⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;943🍴</code></b> [Micrometer](https://github.com/micrometer-metrics/micrometer)) - Vendor-neutral metrics/observability facade for the most popular metrics/observability libraries.
- <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Micrometer Tracing](https://github.com/micrometer-metrics/tracing)) - Vendor-neutral distributed tracing facade for the most popular tracer libraries.
- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [nudge4j](https://github.com/lorenzoongithub/nudge4j)) - Remote developer console from the browser for Java 8 via bytecode injection.
- <b><code>&nbsp;13183⭐</code></b> <b><code>&nbsp;&nbsp;3734🍴</code></b> [Pinpoint](https://github.com/naver/pinpoint)) - Open-source APM tool.
- <b><code>&nbsp;&nbsp;2124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;768🍴</code></b> [Prometheus](https://github.com/prometheus/client_java)) - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.
- [Sentry ![c]](https://github.com/getsentry/sentry-java) - Integration with <b><code>&nbsp;36625⭐</code></b> <b><code>&nbsp;&nbsp;3957🍴</code></b> [Sentry](https://github.com/getsentry/sentry)), an application error tracking and performance analysis platform.
- [SPM ![c]](https://github.com/sematext/sematext-agent-java) - Performance monitor with distributing transaction tracing for JVM apps.
- <b><code>&nbsp;&nbsp;1707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [Stagemonitor](https://github.com/stagemonitor/stagemonitor)) - Open-source performance monitoring and transaction tracing for JVM apps.
- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Sysmon](https://github.com/palantir/Sysmon)) - Lightweight platform monitoring tool for Java VMs.
- 🌎 [zipkin](zipkin.io) - Distributed tracing system which gathers timing data needed to troubleshoot latency problems in microservice architectures.

### Native

_For working with platform-specific native libraries._

- <b><code>&nbsp;&nbsp;&nbsp;459⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Aparapi](https://github.com/Syncleus/aparapi)) - Converts bytecode to OpenCL which allows execution on GPUs.
- <b><code>&nbsp;&nbsp;4349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;569🍴</code></b> [JavaCPP](https://github.com/bytedeco/javacpp)) - Provides efficient and easy access to native C++.
- <b><code>&nbsp;&nbsp;8226⭐</code></b> <b><code>&nbsp;&nbsp;1648🍴</code></b> [JNA](https://github.com/java-native-access/jna)) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries.
- <b><code>&nbsp;&nbsp;1193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [JNR](https://github.com/jnr/jnr-ffi)) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. Same goals as JNA, but faster, and serves as the basis for the upcoming [Project Panama](http://openjdk.java.net/projects/panama).

### Natural Language Processing

_Libraries that specialize in processing text._

- <b><code>&nbsp;&nbsp;&nbsp;470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [CogCompNLP](https://github.com/CogComp/cogcomp-nlp)) - Provides common annotators for plain text input. (Research and Academic Use License)
- 🌎 [CoreNLP](nlp.stanford.edu/software/corenlp.shtml) - Provides a set of fundamental tools for tasks like tagging, named entity recognition, and sentiment analysis. (GPL-3.0-or-later)
- 🌎 [DKPro](dkpro.github.io) - Collection of reusable NLP tools for linguistic pre-processing, machine learning, lexical resources, etc.
- [LingPipe](http://alias-i.com/lingpipe/) - Toolkit for tasks ranging from POS tagging to sentiment analysis.

### Networking

_Libraries for building network servers._

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Commons-networking](https://github.com/CiscoSE/commons-networking)) - Client for server-sent events (SSE).
- <b><code>&nbsp;&nbsp;&nbsp;601⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [Comsat](https://github.com/puniverse/comsat)) - Integrates standard Java web-related APIs with Quasar fibers and actors.
- <b><code>&nbsp;39929⭐</code></b> <b><code>&nbsp;26229🍴</code></b> [Dubbo](https://github.com/apache/dubbo)) - High-performance RPC framework.
- 🌎 [Grizzly](javaee.github.io/grizzly/) - NIO framework. Used as a network layer in Glassfish.
- <b><code>&nbsp;11110⭐</code></b> <b><code>&nbsp;&nbsp;3738🍴</code></b> [gRPC](https://github.com/grpc/grpc-java)) - RPC framework based on protobuf and HTTP/2.
- <b><code>&nbsp;&nbsp;1797⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;417🍴</code></b> [KryoNet](https://github.com/EsotericSoftware/kryonet)) - Provides a clean and simple API for efficient TCP and UDP client/server network communication using NIO and Kryo.
- 🌎 [MINA](mina.apache.org) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
- 🌎 [Netty](netty.io) - Framework for building high-performance network applications.
- <b><code>&nbsp;&nbsp;&nbsp;236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Drift](https://github.com/airlift/drift)) - Easy-to-use, annotation-based library for creating Thrift clients and serializable types.
- <b><code>&nbsp;&nbsp;&nbsp;887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [ServiceTalk](https://github.com/apple/servicetalk)) - Framework built on Netty with APIs tailored to specific protocols and support for multiple programming paradigms.
- <b><code>&nbsp;&nbsp;2423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;580🍴</code></b> [sshj](https://github.com/hierynomus/sshj)) - Programmatically use SSH, SCP or SFTP.
- <b><code>&nbsp;&nbsp;&nbsp;178⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [TLS Channel](https://github.com/marianobarrios/tls-channel)) - Implements a ByteChannel interface over SSLEngine, enabling easy-to-use (socket-like) TLS.
- [Undertow](http://undertow.io) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly. (LGPL-2.1-only)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [urnlib](https://github.com/slub/urnlib)) - Represent, parse and encode URNs, as in RFC 2141. (GPL-3.0-only)
- <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Fluency](https://github.com/komamitsu/fluency)) - High throughput data ingestion logger to Fluentd and Fluent Bit.

### ORM

_APIs that handle the persistence of objects._

- 🌎 [Apache Cayenne](cayenne.apache.org) - Provides a clean, static API for data access. Also includes a GUI Modeler for working with database mappings, and DB reverse engineering and generation.
- <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Doma](https://github.com/domaframework/doma)) - Database access framework that verifies and generates source code at compile time using annotation processing as well as native SQL templates called two-way SQL.
- 🌎 [Ebean](ebean.io) - Provides simple and fast data access.
- 🌎 [EclipseLink](www.eclipse.org/eclipselink/) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
- [Hibernate](http://hibernate.org/orm/) - Robust and widely used, with an active community. (LGPL-2.1-only)
- <b><code>&nbsp;19324⭐</code></b> <b><code>&nbsp;12639🍴</code></b> [MyBatis](https://github.com/mybatis/mybatis-3)) - Couples objects with stored procedures or SQL statements.
- <b><code>&nbsp;&nbsp;1264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [ObjectiveSql](https://github.com/braisdom/ObjectiveSql)) - ActiveRecord ORM for rapid development and convention over configuration.
- <b><code>&nbsp;&nbsp;&nbsp;397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Permazen](https://github.com/permazen/permazen)) - Language-natural persistence layer.
- <b><code>&nbsp;&nbsp;&nbsp;431⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper)) - Simple database and CSV mapper.

### PaaS

_Java platform as a service._

- [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk/) - AWS-based, with support for Tomcat and Jetty.
- [AWS Lambda ![c]](https://aws.amazon.com/lambda/) - Serverless computation.
- [Google Cloud ![c]](https://cloud.google.com) - Google's cloud infrastructure.
- [Heroku ![c]](https://www.heroku.com) - Abstract computing environments.
- [Microsoft Azure ![c]](https://azure.microsoft.com/en-us/) - Microsoft's cloud infrastructure.
- [OpenShift ![c]](https://www.openshift.com) - Provides additionally an on-premise solution.

### PDF

_Tools to help with PDF files._

- 🌎 [Apache FOP](xmlgraphics.apache.org/fop/) - Creates PDFs from XSL-FO.
- 🌎 [Apache PDFBox](pdfbox.apache.org) - Toolbox for creating and manipulating PDFs.
- [Dynamic Jasper](http://dynamicjasper.com) - Abstraction layer to JasperReports. (LGPL-3.0-only)
- <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [DynamicReports](https://github.com/dynamicreports/dynamicreports)) - Simplifies JasperReports. (LGPL-3.0-only)
- 🌎 [Eclipse BIRT](www.eclipse.org/birt) - Report engine for creating PDF and other formats (DOCX, XLSX, HTML, etc) using Eclipse-based visual editor.
- <b><code>&nbsp;&nbsp;1906⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;544🍴</code></b> [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer)) - XML/XHTML and CSS 2.1 renderer. (LGPL-2.1-or-later)
- [iText ![c]](https://itextpdf.com/en) - Creates PDF files programmatically.
- 🌎 [JasperReports](community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine. (LGPL-3.0-only)
- <b><code>&nbsp;&nbsp;1821⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;336🍴</code></b> [Open HTML to PDF](https://github.com/danfickle/openhtmltopdf)) - Properly supports modern PDF standards based on flyingsaucer and Apache PDFBox.
- <b><code>&nbsp;&nbsp;3237⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;547🍴</code></b> [OpenPDF](https://github.com/LibrePDF/OpenPDF)) - Open-source iText fork. (LGPL-3.0-only & MPL-2.0)
- <b><code>&nbsp;&nbsp;1720⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;402🍴</code></b> [Tabula](https://github.com/tabulapdf/tabula-java)) - Extracts tables from PDF files.

### Performance analysis

_Tools for performance analysis, profiling and benchmarking._

- [fastThread ![c]](https://fastthread.io) - Analyze and visualize thread dumps with a free cloud-based upload interface.
- [GCeasy ![c]](https://gceasy.io) - Tool to analyze and visualize GC logs. It provides a free cloud-based upload interface.
- <b><code>&nbsp;&nbsp;1243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler)) - Low-overhead, bias-free sampling profiler.
- <b><code>&nbsp;&nbsp;&nbsp;673⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [jHiccup](https://github.com/giltene/jHiccup)) - Logs and records platform JVM stalls.
- <b><code>&nbsp;&nbsp;2997⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;427🍴</code></b> [JITWatch](https://github.com/AdoptOpenJDK/jitwatch)) - Analyze the JIT compiler optimisations made by the HotSpot JVM.
- [JMH](http://openjdk.java.net/projects/code-tools/jmh/) - Harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM. (GPL-2.0 only WITH Classpath-exception-2.0)
- <b><code>&nbsp;&nbsp;&nbsp;450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils)) - Utilities for latency measurement and reporting.

### Platform

_Frameworks that are suites of multiple libraries encompassing several categories._

#### Apache Commons

- [BCEL](http://commons.apache.org/proper/commons-bcel/) - Byte Code Engineering Library - analyze, create, and manipulate Java class files.
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils/) - Easy-to-use wrappers around the Java reflection and introspection APIs.
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2/) - Redesign of Commons BeanUtils.
- [BSF](http://commons.apache.org/proper/commons-bsf/) - Bean Scripting Framework - interface to scripting languages, including JSR-223.
- [Chain](http://commons.apache.org/proper/commons-chain/) - Chain of Responsibility pattern implementation.
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan/) - Find Class interfaces, methods, fields, and annotations without loading.
- [CLI](http://commons.apache.org/proper/commons-cli/) - Command-line arguments parser.
- [CLI2](http://commons.apache.org/sandbox/commons-cli2/) - Redesign of Commons CLI.
- [Codec](http://commons.apache.org/proper/commons-codec/) - General encoding/decoding algorithms, e.g. phonetic, base64 or URL.
- [Collections](http://commons.apache.org/proper/commons-collections/) - Extends or augments the Java Collections Framework.
- [Compress](http://commons.apache.org/proper/commons-compress/) - Defines an API for working with tar, zip and bzip2 files.
- [Configuration](http://commons.apache.org/proper/commons-configuration/) - Reading of configuration/preferences files in various formats.
- [Convert](http://commons.apache.org/sandbox/commons-convert/) - Commons-Convert aims to provide a single library dedicated to the task of converting an object of one type to another.
- [CSV](http://commons.apache.org/proper/commons-csv/) - Component for reading and writing comma separated value files.
- [Daemon](http://commons.apache.org/proper/commons-daemon/) - Alternative invocation mechanism for unix-daemon-like java code.
- [DBCP](http://commons.apache.org/proper/commons-dbcp/) - Database connection pooling services.
- [DbUtils](http://commons.apache.org/proper/commons-dbutils/) - JDBC helper library.
- [Digester](http://commons.apache.org/proper/commons-digester/) - XML-to-Java-object mapping utility.
- [Email](http://commons.apache.org/proper/commons-email/) - Library for sending e-mail from Java.
- [Exec](http://commons.apache.org/proper/commons-exec/) - API for dealing with external process execution and environment management in Java.
- [FileUpload](http://commons.apache.org/proper/commons-fileupload/) - File upload capability for your servlets and web applications.
- [Finder](http://commons.apache.org/sandbox/commons-finder/) - Java library inspired by the UNIX find command.
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile/) - Java library for working with flat data structures.
- [Functor](http://commons.apache.org/proper/commons-functor/) - Function that can be manipulated as an object, or an object representing a single, generic function.
- [Graph](http://commons.apache.org/sandbox/commons-graph/) - General purpose graph APIs and algorithms.
- [I18n](http://commons.apache.org/sandbox/commons-i18n/) - Adds the feature of localized message bundles that consist of one or many localized texts that belong together.
- [Id](http://commons.apache.org/sandbox/commons-id/) - Id is a component used to generate identifiers.
- [Imaging](http://commons.apache.org/proper/commons-imaging/) - Image library.
- [IO](http://commons.apache.org/proper/commons-io/) - Collection of I/O utilities.
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow/) - Continuation implementation to capture the state of the application.
- [JCI](http://commons.apache.org/proper/commons-jci/) - Java Compiler Interface.
- [JCS](http://commons.apache.org/proper/commons-jcs/) - Java Caching System.
- [Jelly](http://commons.apache.org/proper/commons-jelly/) - XML based scripting and processing engine.
- [Jexl](http://commons.apache.org/proper/commons-jexl/) - Expression language which extends the Expression Language of the JSTL.
- [JNet](http://commons.apache.org/sandbox/commons-jnet/) - JNet allows to use dynamically register url stream handlers through the java.net API.
- [JXPath](http://commons.apache.org/proper/commons-jxpath/) - Utilities for manipulating Java Beans using the XPath syntax.
- [Lang](http://commons.apache.org/proper/commons-lang/) - Provides extra functionality for classes in java.lang.
- 🌎 [Logging](commons.apache.org/proper/commons-logging/) - Wrapper around a variety of logging API implementations.
- [Math](http://commons.apache.org/proper/commons-math/) - Lightweight, self-contained mathematics and statistics components.
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring/) - Monitoring aims to provide a simple but extensible monitoring solution for Java applications.
- [Nabla](http://commons.apache.org/sandbox/commons-nabla/) - Nabla provides automatic differentiation classes that can generate derivative of any function implemented in the Java language.
- [Net](http://commons.apache.org/proper/commons-net/) - Collection of network utilities and protocol implementations.
- [OGNL](http://commons.apache.org/proper/commons-ognl/) - Object-graph navigation language.
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp/) - Interface to signing and verifying data using OpenPGP.
- [Performance](http://commons.apache.org/sandbox/commons-performance/) - Small framework for microbenchmark clients, with implementations for Commons DBCP and Pool.
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline/) - Provides a set of pipeline utilities designed around work queues that run in parallel to sequentially process data objects.
- [Pool](http://commons.apache.org/proper/commons-pool/) - Generic object pooling component.
- [Proxy](http://commons.apache.org/proper/commons-proxy/) - Library for creating dynamic proxies.
- 🌎 [RDF](commons.apache.org/proper/commons-rdf/) - Common implementation of RDF 1.1 that could be implemented by systems on the JVM.
- 🌎 [RNG](commons.apache.org/proper/commons-rng/) - Commons Rng provides implementations of pseudo-random numbers generators.
- [SCXML](http://commons.apache.org/proper/commons-scxml/) - Implementation of the State Chart XML specification aimed at creating and maintaining a Java SCXML engine.
- [Validator](http://commons.apache.org/proper/commons-validator/) - Framework to define validators and validation rules in an xml file.
- [VFS](http://commons.apache.org/proper/commons-vfs/) - Virtual File System component for treating files, FTP, SMB, ZIP and such like as a single logical file system.
- [Weaver](http://commons.apache.org/proper/commons-weaver/) - Provides an easy way to enhance (weave) compiled bytecode.

#### Other

- 🌎 [CUBA Platform](www.cuba-platform.com/) - High-level framework for developing enterprise applications with a rich web interface, based on Spring, EclipseLink and Vaadin.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Light-4J](https://github.com/networknt/light-4j/)) - Fast, lightweight and productive microservices framework with built-in <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [security](https://github.com/networknt/light-oauth2/)).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Orienteer](https://github.com/OrienteerBAP/Orienteer/)) - Open-source business application platform for rapid configuration/development of CRM, ERP, LMS and other applications.
- 🌎 [Spring](spring.io/projects/) - Provides many packages for dependency injection, aspect-oriented programming, security, etc.

### Processes

_Libraries that help the management of operating system processes._

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec)) - Convenient API around Apache Commons Exec.
- <b><code>&nbsp;&nbsp;&nbsp;867⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [zt-exec](https://github.com/zeroturnaround/zt-exec)) - Provides a unified API to Apache Commons Exec and ProcessBuilder.
- <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer)) - Stops processes started from Java or the system processes via PID.

### Reactive libraries

_Libraries for developing reactive applications._

- 🌎 [Akka](akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
- <b><code>&nbsp;&nbsp;4734⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;521🍴</code></b> [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm)) - Provides a standard for asynchronous stream processing with non-blocking backpressure.
- <b><code>&nbsp;&nbsp;4799⭐</code></b> <b><code>&nbsp;&nbsp;1166🍴</code></b> [Reactor](https://github.com/reactor/reactor-core)) - Library for building reactive fast-data applications.
- <b><code>&nbsp;47595⭐</code></b> <b><code>&nbsp;&nbsp;7566🍴</code></b> [RxJava](https://github.com/ReactiveX/RxJava)) - Allows for composing asynchronous and event-based programs using observable sequences.
- 🌎 [vert.x](vertx.io) - Polyglot event-driven application framework.

### REST Frameworks

_Frameworks specifically for creating RESTful services._

- <b><code>&nbsp;&nbsp;8446⭐</code></b> <b><code>&nbsp;&nbsp;3438🍴</code></b> [Dropwizard](https://github.com/dropwizard/dropwizard)) - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
- 🌎 [Elide](elide.io) - Opinionated framework for JSON- or GraphQL-APIs based on a JPA data model.
- 🌎 [Jersey](jersey.github.io) - JAX-RS reference implementation.
- <b><code>&nbsp;&nbsp;&nbsp;939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;215🍴</code></b> [Microserver](https://github.com/aol/micro-server)) - Convenient, extensible microservices plugin system for Spring & Spring Boot. With more than 30 plugins and growing, it supports both micro-monolith and pure microservices styles.
- 🌎 [Rapidoid](www.rapidoid.org) - Simple, secure and extremely fast framework consisting of an embedded HTTP server, GUI components and dependency injection.
- <b><code>&nbsp;&nbsp;2435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;542🍴</code></b> [rest.li](https://github.com/linkedin/rest.li)) - Framework for building robust, scalable RESTful architectures using typesafe bindings and asynchronous, non-blocking IO with an end-to-end developer workflow that promotes clean practices, uniform interface design and consistent data modeling.
- 🌎 [RESTEasy](resteasy.github.io) - Fully certified and portable implementation of the JAX-RS specification.
- <b><code>&nbsp;&nbsp;&nbsp;938⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;288🍴</code></b> [RestExpress](https://github.com/RestExpress/RestExpress)) - Thin wrapper on the JBoss Netty HTTP stack that provides scaling and performance.
- <b><code>&nbsp;&nbsp;&nbsp;641⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [Restlet Framework](https://github.com/restlet/restlet-framework-java)) - Pioneering framework with powerful routing and filtering capabilities, and a unified client and server API.
- [Spark](http://sparkjava.com) - Sinatra inspired framework.
- [Crnk](http://www.crnk.io) - Implementation of the JSON API specification to build resource-oriented REST endpoints with sorting, filtering, paging, linking, object graphs, type-safety, bulk updates, integrations and more.
- <b><code>&nbsp;&nbsp;3050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;457🍴</code></b> [springdoc-openapi](https://github.com/springdoc/springdoc-openapi)) - Automates the generation of API documentation using Spring Boot projects.
- 🌎 [Swagger](swagger.io) - Standard, language-agnostic interface to REST APIs.

### Science

_Libraries for scientific computing, analysis and visualization._

- 🌎 [BioJava](biojava.org/) - Facilitates processing biological data by providing algorithms, file format parsers, sequencing and 3D visualization commonly used in bioinformatics.
- <b><code>&nbsp;&nbsp;&nbsp;473⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [Chart-FX](https://github.com/GSI-CS-CO/chart-fx)) - Scientific charting library with focus on performance optimised real-time data visualisation at 25 Hz update rates for large data sets.
- 🌎 [DataMelt](datamelt.org/) - Environment for scientific computation, data analysis and data visualization. (GPL-3.0-or-later)
- <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Erdos](https://github.com/Erdos-Graph-Framework/Erdos)) - Modular, light and easy graph framework for theoretic algorithms.
- [GraphStream](http://graphstream-project.org) - Library for modeling and analyzing dynamic graphs.
- [JFreeChart](http://www.jfree.org/jfreechart/) - 2D chart library for Swing, JavaFX and server-side applications. (LGPL-2.1-only)
- <b><code>&nbsp;&nbsp;2505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;814🍴</code></b> [JGraphT](https://github.com/jgrapht/jgrapht)) - Graph library that provides mathematical graph-theory objects and algorithms.
- <b><code>&nbsp;&nbsp;&nbsp;659⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;364🍴</code></b> [JGraphX](https://github.com/jgraph/jgraphx)) - Library for visualizing (mainly Swing) and interacting with node-edge graphs.
- <b><code>&nbsp;&nbsp;&nbsp;126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [LogicNG](https://github.com/logic-ng/LogicNG)) - Library for creating, manipulating and solving Boolean and Pseudo-Boolean formulas.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Mines Java Toolkit](https://github.com/MinesJTK/jtk)) - Library for geophysical scientific computation, visualization and digital signal analysis.
- <b><code>&nbsp;&nbsp;&nbsp;238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Morpheus](https://github.com/zavtech/morpheus-core)) - Provides a versatile two-dimensional memory efficient tabular data structure called a DataFrame to enable efficient in-memory analytics for scientific computing on the JVM.
- 🌎 [Orekit](www.orekit.org/) - A low level space flight dynamics library providing basic elements (orbits, dates, attitude, frames...) and various algorithms (conversions, propagations, pointing...) to handle them.
- <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Orson-Charts](https://github.com/jfree/orson-charts)) - Generates a wide variety of 3D charts that can be displayed with Swing and JavaFX or exported to PDF, SVG, PNG and JPEG. (GPL-3.0-only)
- <b><code>&nbsp;&nbsp;3425⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;623🍴</code></b> [Tablesaw](https://github.com/jtablesaw/tablesaw)) - Includes a data-frame, an embedded column store, and hundreds of methods to transform, summarize, or filter data.
- <b><code>&nbsp;&nbsp;1458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;386🍴</code></b> [XChart](https://github.com/knowm/XChart)) - Light-weight library for plotting data. Many customizable chart types are available.

### Search

_Engines that index documents for search and analysis._

- 🌎 [Apache Lucene](lucene.apache.org) - High-performance, full-featured, cross-platform, text search engine library.
- 🌎 [Apache Solr](lucene.apache.org/solr/) - Enterprise search engine optimized for high-volume traffic.
- 🌎 [Elasticsearch](www.elastic.co) - Distributed, multitenant-capable, full-text search engine with a RESTful web interface and schema-free JSON documents.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Indexer4j](https://github.com/haeungun/indexer4j)) - Simple and light full text indexing and searching library.

### Security

_Libraries that handle security, authentication, authorization or session management._

- 🌎 [Apache Shiro](shiro.apache.org) - Performs authentication, authorization, cryptography and session management.
- 🌎 [Bouncy Castle](www.bouncycastle.org/java.html) - All-purpose cryptographic library and JCA provider offering a wide range of functions, from basic helpers to PGP/SMIME operations.
- <b><code>&nbsp;&nbsp;5810⭐</code></b> <b><code>&nbsp;&nbsp;1196🍴</code></b> [DependencyCheck](https://github.com/jeremylong/DependencyCheck)) - Detects publicly disclosed vulnerabilities contained within a project's dependencies.
- 🌎 [Cryptomator](cryptomator.org) - Multiplatform, transparent, client-side encryption of files in the cloud. (GPL-3.0-only)
- <b><code>&nbsp;&nbsp;&nbsp;211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Hdiv](https://github.com/hdiv/hdiv)) - Runtime application that repels application security risks included in the OWASP Top 10, including SQL injection, cross-site scripting, cross-site request forgery, data tampering, and brute force attacks.
- <b><code>&nbsp;&nbsp;9782⭐</code></b> <b><code>&nbsp;&nbsp;1280🍴</code></b> [jjwt](https://github.com/jwtk/jjwt)) - JSON web token for Java and Android.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [jwt-java](https://github.com/BastiaanJansen/jwt-java)) - Easily create and parse JSON Web Tokens and create customized JWT validators using a fluent API.
- <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Jwks RSA](https://github.com/auth0/jwks-rsa-java)) - JSON Web Key Set parser.
- <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Kalium](https://github.com/abstractj/kalium)) - Binding for the Networking and Cryptography (NaCl) library.
- 🌎 [Keycloak](www.keycloak.org) - Integrated SSO and IDM for browser apps and RESTful web services.
- <b><code>&nbsp;&nbsp;2614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [Keywhiz](https://github.com/square/keywhiz)) - System for distributing and managing secrets.
- <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz)) - Advanced password strength estimation.
- [OACC](http://oaccframework.org) - Provides permission-based authorization services.
- <b><code>&nbsp;&nbsp;&nbsp;707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [OpenAM](https://github.com/OpenIdentityPlatform/OpenAM)) - Access management solution that includes authentication, SSO, authorization, federation, entitlements and web services security.
- <b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [OTP-Java](https://github.com/BastiaanJansen/OTP-Java)) - One-time password generator library according to RFC 4226 (HOTP) and RFC 6238 (TOTP).
- <b><code>&nbsp;&nbsp;2372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;673🍴</code></b> [pac4j](https://github.com/pac4j/pac4j)) - Security engine.
- [Passay](http://www.passay.org/) - Enforce password policy by validating candidate passwords against a configurable rule set.
- <b><code>&nbsp;&nbsp;&nbsp;326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Password4j](https://github.com/Password4j/password4j)) - User-friendly cryptographic library that supports Argon2, Bcrypt, Scrypt, PBKDF2 and various other cryptographic hash functions.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [SecurityBuilder](https://github.com/tersesystems/securitybuilder)) - Fluent Builder API for JCA and JSSE classes and especially X.509 certificates.
- <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [SSLContext-Kickstart](https://github.com/Hakky54/sslcontext-kickstart)) - High-level SSL context builder for configuring HTTP clients with SSL/TLS.
- <b><code>&nbsp;&nbsp;1795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [Themis](https://github.com/cossacklabs/themis)) - Multi-platform high-level cryptographic library provides easy-to-use encryption for protecting sensitive data: secure messaging with forward secrecy, secure data storage (AES256GCM); suits for building end-to-end encrypted applications.
- <b><code>&nbsp;13457⭐</code></b> <b><code>&nbsp;&nbsp;1176🍴</code></b> [Tink](https://github.com/google/tink)) - Provides a simple and misuse-proof API for common cryptographic tasks.
- 🌎 [Topaz](www.topaz.sh) - Fine-grained authorization for applications with support for RBAC, ABAC, and ReBAC.

### Serialization

_Libraries that handle serialization with high efficiency._

- <b><code>&nbsp;21923⭐</code></b> <b><code>&nbsp;&nbsp;3148🍴</code></b> [FlatBuffers](https://github.com/google/flatbuffers)) - Memory-efficient serialization library that can access serialized data without unpacking and parsing it.
- <b><code>&nbsp;&nbsp;1564⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [FST](https://github.com/RuedigerMoeller/fast-serialization)) - JDK-compatible, high-performance object graph serialization.
- <b><code>&nbsp;&nbsp;2557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [Fury](https://github.com/alipay/fury)) - Blazing fast object graph serialization framework powered by JIT and zero-copy.
- <b><code>&nbsp;&nbsp;6037⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;815🍴</code></b> [Kryo](https://github.com/EsotericSoftware/kryo)) - Fast and efficient object graph serialization framework.
- <b><code>&nbsp;&nbsp;1374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;317🍴</code></b> [MessagePack](https://github.com/msgpack/msgpack-java)) - Efficient binary serialization format.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [PHP Serializer](https://github.com/marcospassos/java-php-serializer)) - Serializing objects in the PHP serialization format.

### Server

_Servers specifically used to deploy applications._

- 🌎 [Apache Tomcat](tomcat.apache.org) - Robust, all-round server for Servlet and JSP.
- 🌎 [Apache TomEE](tomee.apache.org) - Tomcat plus Java EE.
- 🌎 [Jetty](www.eclipse.org/jetty/) - Provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations.
- <b><code>&nbsp;&nbsp;6816⭐</code></b> <b><code>&nbsp;&nbsp;1689🍴</code></b> [nanohttpd](https://github.com/NanoHttpd/nanohttpd)) - Tiny, easily embeddable HTTP server.
- 🌎 [WildFly](www.wildfly.org) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support. (LGPL-2.1-only)

### Template Engine

_Tools that substitute expressions in a template._

- 🌎 [Freemarker](freemarker.apache.org) - Library to generate text output (HTML web pages, e-mails, configuration files, source code, etc.) based on templates and changing data.
- 🌎 [Handlebars.java](jknack.github.io/handlebars.java/) - Logicless and semantic Mustache templates.
- <b><code>&nbsp;&nbsp;&nbsp;706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Jade4J](https://github.com/neuland/jade4j)) - Implementation of Pug (formerly known as Jade).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Jamal](https://github.com/verhas/jamal)) - Extendable template engine embedded into Maven/JavaDoc, supporting multiple extensions (Groovy, Ruby, JavaScript, JShell, PlantUml) with support for snippet handling.
- <b><code>&nbsp;&nbsp;&nbsp;203⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [jstachio](https://github.com/jstachio/jstachio)) - Typesafe Mustache templating engine.
- <b><code>&nbsp;&nbsp;&nbsp;684⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [jte](https://github.com/casid/jte)) - Compiles to classes, and uses an easy syntax, several features to make development easier and provides fast execution and a small footprint.
- <b><code>&nbsp;&nbsp;&nbsp;298⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Jtwig](https://github.com/jtwig/jtwig)) - Modular, configurable and fully tested template engine.
- 🌎 [Pebble](pebbletemplates.io) - Inspired by Twig and separates itself with its inheritance feature and its easy-to-read syntax. It ships with built-in autoescaping for security and it includes integrated support for internationalization.
- <b><code>&nbsp;&nbsp;&nbsp;719⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Rocker](https://github.com/fizzed/rocker)) - Optimized, memory efficient and speedy template engine producing statically typed, plain objects.
- <b><code>&nbsp;&nbsp;&nbsp;920⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [StringTemplate](https://github.com/antlr/stringtemplate4)) - Template engine for generating source code, web pages, emails, or any other formatted text output.
- 🌎 [Thymeleaf](www.thymeleaf.org) - Aims to be a substitute for JSP and works for XML files.

### Testing

_Tools that test from model to the view._

#### Asynchronous

_Tools that simplify testing asynchronous services._

- <b><code>&nbsp;&nbsp;3662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;227🍴</code></b> [Awaitility](https://github.com/awaitility/awaitility)) - DSL for synchronizing asynchronous operations.
- <b><code>&nbsp;&nbsp;&nbsp;414⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [ConcurrentUnit](https://github.com/jhalterman/concurrentunit)) - Toolkit for testing multi-threaded and asynchronous applications.
- 🌎 [GreenMail](greenmail-mail-test.github.io/greenmail/) - In-memory email server for integration testing. Supports SMTP, POP3 and IMAP including SSL. (GPL-2.0-only)
- <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java)) - Native bindings for Hoverfly, a proxy which allows you to simulate HTTP services.
- <b><code>&nbsp;&nbsp;7807⭐</code></b> <b><code>&nbsp;&nbsp;1906🍴</code></b> [Karate](https://github.com/intuit/karate)) - DSL that combines API test-automation, mocks and performance-testing making testing REST/HTTP services easy.
- <b><code>&nbsp;&nbsp;6685⭐</code></b> <b><code>&nbsp;&nbsp;1851🍴</code></b> [REST Assured](https://github.com/rest-assured/rest-assured)) - DSL for easy testing of REST/HTTP services.
- <b><code>&nbsp;&nbsp;&nbsp;352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [WebTau](https://github.com/testingisdocumenting/webtau)) - Test across REST-API, Graph QL, Browser, Database, CLI and Business Logic with consistent set of matchers and concepts.

#### BDD

_Testing for the software development process that emerged from TDD and was heavily influenced by DDD and OOAD._

- <b><code>&nbsp;&nbsp;2656⭐</code></b> <b><code>&nbsp;&nbsp;2007🍴</code></b> [Cucumber](https://github.com/cucumber/cucumber-jvm)) - Provides a way to describe features in a plain language which customers can understand.
- <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Cukes-REST](https://github.com/ctco/cukes)) - Collection of Gherkin steps for REST-service testing using Cucumber.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [J8Spec](https://github.com/j8spec/j8spec)) - Follows a Jasmine-like syntax.
- 🌎 [JBehave](jbehave.org) - Extensively configurable framework that describes stories.
- [JGiven](http://jgiven.org) - Provides a fluent API which allows for simpler composition.
- <b><code>&nbsp;&nbsp;&nbsp;254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave)) - Aims to provide a fluent API to write tests in long and descriptive sentences that read like plain English.
- <b><code>&nbsp;&nbsp;&nbsp;706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;510🍴</code></b> [Serenity BDD](https://github.com/serenity-bdd/serenity-core)) - Automated Acceptance testing and reporting library that works with Cucumber, JBehave and JUnit to make it easier to write high quality executable specifications.

#### Fixtures

_Everything related to the creation and handling of random data._

- <b><code>&nbsp;&nbsp;&nbsp;114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Beanmother](https://github.com/keepcosmos/beanmother)) - Sets up beans from YAML fixtures.
- <b><code>&nbsp;&nbsp;&nbsp;967⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [Datafaker](https://github.com/datafaker-net/datafaker)) - Modern fake data generator forked from Java Faker.
- <b><code>&nbsp;&nbsp;&nbsp;442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [Fixture Factory](https://github.com/six2six/fixture-factory)) - Generates fake objects from a template.
- <b><code>&nbsp;&nbsp;&nbsp;739⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [jFairy](https://github.com/Devskiller/jfairy)) - Fake data generator.
- <b><code>&nbsp;&nbsp;&nbsp;737⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Instancio](https://github.com/instancio/instancio)) - Automates data setup in unit tests by generating fully-populated, reproducible objects. Includes JUnit 5 extension.
- <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting)) - JUnit test runner and plugins for running JUnit tests with pseudo-randomness.
- <b><code>&nbsp;&nbsp;4529⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;832🍴</code></b> [Java Faker](https://github.com/DiUS/java-faker)) - Port of Ruby's fake data generator.
- <b><code>&nbsp;&nbsp;&nbsp;523⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Mockneat](https://github.com/nomemory/mockneat)) - Another fake data generator.

#### Frameworks

_Provide environments to run tests for a specific use case._

- <b><code>&nbsp;&nbsp;3039⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [ArchUnit](https://github.com/TNG/ArchUnit)) - Test library for specifying and asserting architecture rules.
- [Apache JMeter](http://jmeter.apache.org) - Functional testing and performance measurements.
- [Arquillian](http://arquillian.org) - Integration and functional testing platform for Java EE containers.
- 🌎 [Citrus](citrusframework.org) - Integration testing framework that focuses on both client- and server-side messaging.
- 🌎 [Gatling](gatling.io) - Load testing tool designed for ease of use, maintainability and high performance.
- 🌎 [JUnit](junit.org/junit5/) - Common testing framework.
- 🌎 [jqwik](jqwik.net) - Engine for property-based testing built on JUnit 5.
- <b><code>&nbsp;&nbsp;1050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;472🍴</code></b> [Pact JVM](https://github.com/DiUS/pact-jvm)) - Consumer-driven contract testing.
- [PIT](http://pitest.org) - Fast mutation-testing framework for evaluating fault-detection abilities of existing JUnit or TestNG test suites.

#### Matchers

_Libraries that provide custom matchers._

- 🌎 [AssertJ](joel-costigliola.github.io/assertj/) - Fluent assertions that improve readability.
- [Hamcrest](http://hamcrest.org/JavaHamcrest/) - Matchers that can be combined to create flexible expressions of intent.
- [JSONAssert](http://jsonassert.skyscreamer.org) - Simplifies testing JSON strings.
- <b><code>&nbsp;&nbsp;&nbsp;854⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [JsonUnit](https://github.com/lukas-krecan/JsonUnit)) - Library that simplifies JSON comparison in tests.
- 🌎 [Truth](truth.dev) - Google's fluent assertion and proposition framework.
- <b><code>&nbsp;&nbsp;&nbsp;286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [XMLUnit](https://github.com/xmlunit/xmlunit)) - Simplifies testing for XML output.

#### Miscellaneous

_Other stuff related to testing._

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [ConsoleCaptor](https://github.com/Hakky54/console-captor)) - Captures console output for unit testing purposes.
- <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [junit-dataprovider](https://github.com/TNG/junit-dataprovider)) - TestNG-like data provider/runner for JUnit.
- <b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [LogCaptor](https://github.com/Hakky54/log-captor)) - Captures log entries for unit testing purposes.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [log-capture](https://github.com/dm-drogeriemarkt/log-capture)) - Captures log entries and provides assertions for unit and integration testing.
- <b><code>&nbsp;&nbsp;&nbsp;236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector)) - Reports whether instances of a given class are immutable.
- 🌎 [pojo-tester](www.pojo.pl) - Automatically performs tests on basic POJO methods. (LGPL-3.0-only)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [raml-tester](https://github.com/nidi3/raml-tester)) - Tests if a request/response matches a given RAML definition.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Selfie](https://github.com/diffplug/selfie)) - Snapshot testing (inline and on disk).
- <b><code>&nbsp;&nbsp;7702⭐</code></b> <b><code>&nbsp;&nbsp;1579🍴</code></b> [TestContainers](https://github.com/testcontainers/testcontainers-java)) - Provides throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.

#### Mocking

_Tools which mock collaborators to help testing single, isolated units._

- [JMockit](http://jmockit.github.io) - Integration testing, API mocking and faking, and code coverage.
- <b><code>&nbsp;14520⭐</code></b> <b><code>&nbsp;&nbsp;2511🍴</code></b> [Mockito](https://github.com/mockito/mockito)) - Mocking framework that lets you write tests with a clean and simple API.
- 🌎 [MockServer](www.mock-server.com) - Allows mocking of systems integrated with HTTPS.
- <b><code>&nbsp;&nbsp;4306⭐</code></b> <b><code>&nbsp;&nbsp;1075🍴</code></b> [Moco](https://github.com/dreamhead/moco)) - Concise web services for stubs and mocks.
- <b><code>&nbsp;&nbsp;4124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;582🍴</code></b> [PowerMock](https://github.com/powermock/powermock)) - Mocks static methods, constructors, final classes and methods, private methods, and removal of static initializers.
- [WireMock](http://wiremock.org) - Stubs and mocks web services.
- <b><code>&nbsp;&nbsp;&nbsp;809⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;313🍴</code></b> [EasyMock](https://github.com/easymock/easymock)) - EasyMock is a Java library that provides an easy way to use Mock Objects in unit testing.

### Utility

_Libraries which provide general utility functions._

- <b><code>&nbsp;34511⭐</code></b> <b><code>&nbsp;&nbsp;7305🍴</code></b> [Arthas](https://github.com/alibaba/arthas)) - Allows to troubleshoot production issues for applications without modifying code or restarting servers.
- <b><code>&nbsp;&nbsp;2140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;270🍴</code></b> [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j)) - Rate limiting library based on token-bucket algorithm.
- <b><code>&nbsp;&nbsp;&nbsp;724⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [cactoos](https://github.com/yegor256/cactoos)) - Collection of object-oriented primitives.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Chocotea](https://github.com/cleopatra27/chocotea)) - Generates postman collection, environment and integration tests from java code.
- [CRaSH](http://www.crashub.org) - Provides a shell into a JVM that's running CRaSH. Used by Spring Boot and others. (LGPL-2.1-or-later)
- <b><code>&nbsp;&nbsp;1314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;318🍴</code></b> [Dex](https://github.com/PatMartin/Dex)) - Java/JavaFX tool capable of powerful ETL and data visualization.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [dregex](https://github.com/marianobarrios/dregex)) - Regular expression engine that uses deterministic finite automata. It supports some Perl-style features and yet retains linear matching time, and also offers set operations.
- <b><code>&nbsp;&nbsp;1723⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Embulk](https://github.com/embulk/embulk)) - Bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [fswatch](https://github.com/vorburger/ch.vorburger.fswatch)) - Micro library to watch for directory file system changes, simplifying java.nio.file.WatchService.
- <b><code>&nbsp;&nbsp;5654⭐</code></b> <b><code>&nbsp;&nbsp;1555🍴</code></b> [Gephi](https://github.com/gephi/gephi)) - Cross-platform for visualizing and manipulating large graph networks. (GPL-3.0-only)
- <b><code>&nbsp;49266⭐</code></b> <b><code>&nbsp;10740🍴</code></b> [Guava](https://github.com/google/guava)) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and more.
- 🌎 [JADE](jade.tilab.com) - Framework and environment for building and debugging multi-agent systems. (LGPL-2.0-only)
- 🌎 [Java Diff Utils](java-diff-utils.github.io/java-diff-utils/) - Utilities for text or data comparison and patching.
- <b><code>&nbsp;&nbsp;2607⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions)) - Library that helps with constructing difficult regular expressions.
- 🌎 [JGit](www.eclipse.org/jgit/) - Lightweight, pure Java library implementing the Git version control system.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [JKScope](https://github.com/evpl/jkscope)) - Java scope functions inspired by Kotlin.
- <b><code>&nbsp;&nbsp;1016⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;457🍴</code></b> [minio-java](https://github.com/minio/minio-java)) - Provides simple APIs to access any Amazon S3-compatible object storage server.
- 🌎 [Protégé](protege.stanford.edu) - Provides an ontology editor and a framework to build knowledge-based systems.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Semver4j](https://github.com/semver4j/semver4j)) - Lightweight library that helps you handling semantic versioning with different modes.
- <b><code>&nbsp;&nbsp;&nbsp;514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Underscore-java](https://github.com/javadev/underscore-java)) - Port of Underscore.js functions.

### Version Managers

_Utilities that help create the development shell environment and switch between different Java versions._

- <b><code>&nbsp;&nbsp;2844⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [jabba](https://github.com/shyiko/jabba)) - Java Version Manager inspired by nvm. Supports macOS, Linux and Windows.
- <b><code>&nbsp;&nbsp;5425⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;359🍴</code></b> [jenv](https://github.com/jenv/jenv)) - Java Version Manager inspired by rbenv. Can configure globally or per project. Tested on Debian and macOS.
- <b><code>&nbsp;&nbsp;5801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;623🍴</code></b> [SDKMan](https://github.com/sdkman/sdkman-cli)) - Java Version Manager inspired by RVM and rbenv. Supports UNIX-based platforms and Windows.

### Web Crawling

_Libraries that analyze the content of websites._

- 🌎 [Apache Nutch](nutch.apache.org) - Highly extensible, highly scalable web crawler for production environments.
- <b><code>&nbsp;&nbsp;4483⭐</code></b> <b><code>&nbsp;&nbsp;1920🍴</code></b> [Crawler4j](https://github.com/yasserg/crawler4j)) - Simple and lightweight web crawler.
- 🌎 [jsoup](jsoup.org) - Scrapes, parses, manipulates and cleans HTML.
- [StormCrawler](http://stormcrawler.net) - SDK for building low-latency and scalable web crawlers.
- <b><code>&nbsp;11203⭐</code></b> <b><code>&nbsp;&nbsp;4163🍴</code></b> [webmagic](https://github.com/code4craft/webmagic)) - Scalable crawler with downloading, url management, content extraction and persistent.

### Web Frameworks

_Frameworks that handle the communication between the layers of a web application._

- 🌎 [ActiveJ](activej.io) - Lightweight asynchronous framework built from the ground up for developing high-performance web applications.
- 🌎 [Apache Tapestry](tapestry.apache.org) - Component-oriented framework for creating dynamic, robust, highly scalable web applications.
- 🌎 [Apache Wicket](wicket.apache.org) - Component-based web application framework similar to Tapestry, with a stateful GUI.
- <b><code>&nbsp;&nbsp;5826⭐</code></b> <b><code>&nbsp;&nbsp;1162🍴</code></b> [Blade](https://github.com/lets-blade/blade)) - Lightweight, modular framework that aims to be elegant and simple.
- 🌎 [Bootique](bootique.io) - Minimally opinionated framework for runnable apps.
- [Firefly](http://www.fireflysource.com) - Asynchronous framework for rapid development of high-performance web application.
- 🌎 [Javalin](javalin.io/) - Microframework for web applications.
- [Jooby](http://www.jooby.org) - Scalable, fast and modular micro-framework that offers multiple programming models.
- [Ninja](http://www.ninjaframework.org) - Full-stack web framework.
- [Pippo](http://www.pippo.ro) - Small, highly modularized, Sinatra-like framework.
- 🌎 [Play](www.playframework.com) - Built on Akka, it provides predictable and minimal resource consumption (CPU, memory, threads) for highly-scalable applications in Java and Scala.
- 🌎 [PrimeFaces](www.primefaces.org) - JSF framework with both free and commercial/support versions and frontend components.
- 🌎 [Ratpack](ratpack.io) - Set of libraries that facilitate fast, efficient, evolvable and well-tested HTTP applications.
- <b><code>&nbsp;&nbsp;&nbsp;795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [Takes](https://github.com/yegor256/takes)) - Opinionated web framework which is built around the concepts of True Object-Oriented Programming and immutability.
- 🌎 [Vaadin](vaadin.com) - Event-driven framework that uses standard web components. Server-side architecture with Ajax on the client side.

### Workflow Orchestration Engines

- 🌎 [Cadence](cadenceworkflow.io) - Stateful code platform from Uber.
- <b><code>&nbsp;&nbsp;7300⭐</code></b> <b><code>&nbsp;&nbsp;2490🍴</code></b> [flowable](https://github.com/flowable/flowable-engine)) - Compact and efficient workflow and business process management platform.
- 🌎 [Temporal](temporal.io) - Microservice orchestration platform, forked from Cadence but gRPC based.

## Resources

### Related Awesome Lists

_Awesome Lists related to the Java & JVM ecosystem._

- <b><code>&nbsp;&nbsp;&nbsp;436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Awesome Annotation Processing](https://github.com/gunnarmorling/awesome-annotation-processing))
- <b><code>&nbsp;&nbsp;&nbsp;354⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Awesome Graal](https://github.com/neomatrix369/awesome-graal))
- <b><code>&nbsp;&nbsp;&nbsp;444⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle))
- <b><code>&nbsp;&nbsp;3006⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;443🍴</code></b> [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX))
- <b><code>&nbsp;&nbsp;2015⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [Awesome JVM](https://github.com/deephacks/awesome-jvm))
- <b><code>&nbsp;12863⭐</code></b> <b><code>&nbsp;&nbsp;1768🍴</code></b> [Awesome Microservices](https://github.com/mfornos/awesome-microservices))
- <b><code>&nbsp;&nbsp;3517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;400🍴</code></b> [Awesome REST](https://github.com/marmelab/awesome-rest))
- <b><code>&nbsp;&nbsp;&nbsp;974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Awesome Hybris](https://github.com/eminyagiz42/awesome-hybris))
- <b><code>&nbsp;&nbsp;1784⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;189🍴</code></b> [ciandcd](https://github.com/ciandcd/awesome-ciandcd))
- <b><code>&nbsp;&nbsp;5740⭐</code></b> <b><code>&nbsp;&nbsp;1185🍴</code></b> [Useful Java Links](https://github.com/Vedenin/useful-java-links))
- <b><code>&nbsp;&nbsp;1247⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [Java Concurrency Checklist](https://github.com/code-review-checklists/java-concurrency))
- <b><code>&nbsp;&nbsp;3726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;522🍴</code></b> [Java Developer Roadmap](https://github.com/s4kibs4mi/java-developer-roadmap))

### Communities

_Active discussions._

- 🌎 [r/java](www.reddit.com/r/java/) - Subreddit for the Java community.
- 🌎 [Stack Overflow](stackoverflow.com/questions/tagged/java) - Question/answer platform.

### Frontends

_Websites that provide a frontend for this list. Please note, there won't be an official website. We don't associate with a particular website and everybody is allowed to create one._

- 🌎 [java.libhunt.com](java.libhunt.com)

### Influential Books

_Books that made a big impact and are still worth reading._

- 🌎 [Core Java Volume I--Fundamentals](www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- 🌎 [Core Java, Volume II--Advanced Features](www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- 🌎 [Effective Java (3rd Edition)](www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- 🌎 [Java Concurrency in Practice](www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- 🌎 [Thinking in Java](www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)
- 🌎 [Head First Java (3rd Edition)](www.oreilly.com/library/view/head-first-java/9781492091646/)

### Podcasts and Screencasts

_Something to look at or listen to while programming._

- 🌎 [140 Second Ducklings](twitter.com/debugagent/status/1491075324805001219) - Short videos on Twitter explaining Java debugging in depth.
- 🌎 [A Bootiful Podcast](bootifulpodcast.fm)
- 🌎 [Foojay Podcast](foojay.io/today/category/podcast/)
- 🌎 [Inside Java](inside.java/podcast) (Official)
- [Java Off Heap](http://www.javaoffheap.com)
- [The Java Posse](http://www.javaposse.com) - Discontinued as of 02/2015.

### People

#### Twitter

_Active accounts to follow. Descriptions from Twitter._

- 🌎 [Adam Bien](twitter.com/AdamBien) - Freelance author, JavaOne Rockstar speaker, consultant, Java Champion.
- 🌎 [Aleksey Shipilëv](twitter.com/shipilev) - Performance geek, benchmarking czar, concurrency bug hunter.
- 🌎 [Antonio Goncalves](twitter.com/agoncal) - Java Champion, JUG Leader, Devoxx France, Java EE 6/7, JCP, Author.
- 🌎 [Arun Gupta](twitter.com/arungupta) - Java Champion, JavaOne Rockstar, JUG Leader, Devoxx4Kids-er, VP of Developer Advocacy at Couchbase.
- 🌎 [Brian Goetz](twitter.com/BrianGoetz) - Java Language Architect at Oracle.
- 🌎 [Bruno Borges](twitter.com/brunoborges) - Product Manager/Java Jock at Oracle.
- 🌎 [Chris Engelbert](twitter.com/noctarius2k) - Open Source Enthusiast, Speaker, Developer, Developer Advocacy at TimescaleDB.
- 🌎 [Chris Richardson](twitter.com/crichardson) - Software architect, consultant, and serial entrepreneur, Java Champion, JavaOne Rock Star, \*POJOs in Action- author.
- 🌎 [Ed Burns](twitter.com/edburns) - Consulting Member of the Technical Staff at Oracle.
- 🌎 [Eugen Paraschiv](twitter.com/baeldung) - Author of the Spring Security Course.
- 🌎 [Heinz Kabutz](twitter.com/heinzkabutz) - Java Champion, speaker, author of The Java Specialists' Newsletter, concurrency performance expert.
- 🌎 [Holly Cummins](twitter.com/holly_cummins) - Technical Lead of IBM London's Bluemix Garage, Java Champion, developer, author, JavaOne rockstar.
- 🌎 [James Weaver](twitter.com/JavaFXpert) - Java/JavaFX/IoT developer, author and speaker.
- 🌎 [Java EE](twitter.com/Java_EE) - Official Java EE Twitter account.
- 🌎 [Java Magazine](twitter.com/Oraclejavamag) - Official Java Magazine account.
- 🌎 [Java](twitter.com/java) - Official Java Twitter account.
- 🌎 [Javin Paul](twitter.com/javinpaul) - Well-known Java blogger.
- 🌎 [Josh Long](twitter.com/starbuxman) - Spring Advocate at Pivotal, author of O'Reilly's Cloud Native Java- and Building Microservices with Spring Boot, JavaOne Rock Star.
- 🌎 [Lukas Eder](twitter.com/lukaseder) - Java Champion, speaker, Founder and CEO Data Geekery (jOOQ).
- 🌎 [Mani Sarkar](twitter.com/theNeomatrix369) - Java champion, Polyglot, Software Crafter involved with @graalvm, AI/ML/DL, Data Science, Developer communities, speaker & blogger. Creator of couple of awesome lists like this one.
- 🌎 [Mario Fusco](twitter.com/mariofusco) - RedHatter, JUG coordinator, frequent speaker and author.
- 🌎 [Mark Heckler](twitter.com/MkHeck) - Pivotal Principal Technologist and Developer Advocate, conference speaker, published author, and Java Champion, focusing on Internet of Things and the cloud.
- 🌎 [Mark Reinhold](twitter.com/mreinhold) - Chief Architect, Java Platform Group, Oracle.
- 🌎 [Markus Eisele](twitter.com/myfear) - Java EE evangelist, Red Hat.
- 🌎 [Martijn Verburg](twitter.com/karianna) - London JUG co-leader, speaker, author, Java Champion and much more.
- 🌎 [Martin Thompson](twitter.com/mjpt777) - Pasty faced performance gangster.
- 🌎 [Monica Beckwith](twitter.com/mon_beck) - Performance consultant, JavaOne Rock Star.
- 🌎 [OpenJDK](twitter.com/OpenJDK) - Official OpenJDK account.
- 🌎 [Peter Lawrey](twitter.com/PeterLawrey) - Peter Lawrey, Java performance expert.
- 🌎 [Randy Shoup](twitter.com/randyshoup) - Stitch Fix VP Engineering, speaker, JavaOne Rock Star.
- 🌎 [Reza Rahman](twitter.com/reza_rahman) - Java EE/GlassFish/WebLogic evangelist, author, speaker, open source hacker.
- 🌎 [Sander Mak](twitter.com/Sander_Mak) - Java Champion, author.
- 🌎 [Simon Maple](twitter.com/sjmaple) - Java Champion, VirtualJUG founder, LJC leader, RebelLabs author.
- 🌎 [Spencer Gibb](twitter.com/spencerbgibb) - Software Engineer, Dad, Geek, Co-founder and Lead of Spring Cloud Core @pivotal.
- 🌎 [Stephen Colebourne](twitter.com/jodastephen) - Java Champion, speaker.
- 🌎 [Trisha Gee](twitter.com/trisha_gee) - Java Champion and speaker.
- 🌎 [Venkat Subramaniam](twitter.com/venkat_s) - Author, University of Houston professor, MicroSoft MVP award recipient, JavaOne Rock Star, Java Champion.
- 🌎 [Vlad Mihalcea](twitter.com/vlad_mihalcea) - Java Champion working on Hypersistence Optimizer, database aficionado, author of High-Performance Java Persistence book.

#### Other

- 🌎 [Groundbreakers](apexapps.oracle.com/pls/apex/f?p=119297:3::::::) - Oracle ACEs, Groundbreaker Ambassadors and Java Champions.

### Websites

_Sites to read._

- 🌎 [Baeldung](www.baeldung.com)
- 🌎 [Dzone](dzone.com)
- 🌎 [foojay.io](foojay.io)
- 🌎 [Google Java Style](google.github.io/styleguide/javaguide.html)
- 🌎 [InfoQ](www.infoq.com)
- 🌎 [Java Algorithms and Clients](algs4.cs.princeton.edu/code)
- 🌎 [Java, SQL, and jOOQ](blog.jooq.org)
- 🌎 [Java.net](community.oracle.com/community/java)
- 🌎 [Javalobby](dzone.com/java-jdk-development-tutorials-tools-news)
- 🌎 [JavaWorld](www.javaworld.com)
- 🌎 [JAXenter](jaxenter.com)
- 🌎 [RebelLabs](zeroturnaround.com/rebellabs)
- 🌎 [OverOps Blog](blog.overops.com)
- [TheServerSide.com](http://www.theserverside.com)
- 🌎 [Vanilla Java](vanilla-java.github.io)
- 🌎 [Voxxed](www.voxxed.com)
- 🌎 [Java Weekly](discu.eu/weekly/java/)

## Contributing

Contributions are very welcome!

Please have a look at the [CONTRIBUTING](https://github.com/correia-jpv/fucking-awesome-java/blob/master/CONTRIBUTING.md) guidelines and <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [the validation tools](https://github.com/akullpp/awesome-java-lint)).

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg

## Source
<b><code>&nbsp;39640⭐</code></b> <b><code>&nbsp;&nbsp;7241🍴</code></b> [akullpp/awesome-java](https://github.com/akullpp/awesome-java))
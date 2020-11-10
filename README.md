# hibernate-dsl
Kotlin DSL for Hibernate

# Current project status: Development

Currently the project is in its initial phase and still under local development. First tests to create a SessionFactory with Kotlin-DSL went quite well, but the implementation is still more like a test.

Within the next week the test project will be completely reworked and then the development will start here on Github.

# Why Kotlin DSL for Hibernate

It allows easy configuration and use of hibernate in kotlin.

# How did I get this idea?

I wanted to create the SessionFactory with Kotlin DSL and omit the hibernate.cfg.xml

For a while I wrote a helper class in Java (later Kotlin) that configures and creates the SessionFactory for me at runtime and finds and registers the entities. 

Later my goal was to use a configuration file, but to use a single language in the project: Kotlin!
Since Gradle manages to use Kotlin script files for its purposes, my goal was to do something similar for Hibernate.

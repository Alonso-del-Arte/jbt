# jbt &mdash; Just a Build Tool

WORK IN PROGRESS. This is going to be just a build tool for Java. Nothing else.
No dependency management, none of those things that are best left to integrated
development environments (IDEs) like Apache NetBeans or IntelliJ IDEA.

In the Java ecosystem, build tools are a crucial part of the software 
development process. But they also add a lot of their own complexity.

You can see a similar phenomenon with Scala: sbt is the most used build tool for 
Scala projects. Originally referred to as "Simple Build Tool" but first released 
as just "sbt," some people started calling it "Scala Build Tool." Both acronym 
expansions are incorrect: sbt has always been able to build Java-only projects, 
and if it was ever simple, it sure as hell no longer is.

In this project, I aim to create a build tool for Java-only projects that is as 
simple as I can make it, and opinionated only when necessary to avoid 
complexity.

Instead of using XML files, this build tool will use markdown files to describe 
the project structure.

This project started out in another repository as an Apache Ant project. Then I 
thought about the build tool building itself somehow. But now I'm thinking I'll 
just build this "by hand" on the command line.

I could have removed all traces of Apache Ant from the earlier repository, but 
then decided it would just be easier to start over from scratch. Though then 
again, I hadn't made much progress. The earlier repository will probably be 
archived.

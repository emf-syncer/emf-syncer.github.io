## EMF-Syncer 

**EMF-Syncer** facilitates the adoption of Model-Driven Engineering techniques, and EMF-supported tooling, in JVM programs.

More information can be found in the publication:

*Artur Boronat. Code-First Model-Driven Engineering: On the Agile Adoption of MDE Tooling. In Proceedings of 34th IEEE/ACM International Conference on Automated Software Engineering (ASE 2019). Mon 11 - Fri 15 November 2019 San Diego, California, United States.*

### Configuring a Gradle build script to use EMF-Syncer

Add the following repository:

	repositories {
		maven {
			url "https://github.com/yamtl/yamtl.github.io/raw/mvn-repo/mvn-repo/snapshot-repo"
		}
	}

Declare the following dependencies:

	dependencies {
		compile "org.eclipse.xtend:org.eclipse.xtend.lib:2.18.0"
		compile "yamtl:emf-syncer:0.0.1-SNAPSHOT"
	}

### Examples

The tool has been evaluated with the TCP-DS benchmark. Software, data sets and results used in the experiments can be found [here](https://github.com/emf-syncer/emf-syncer.tpcds).


***
&copy; [Artur Boronat](arturboronat.info), 2019
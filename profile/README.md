The Eclipse Orbit project provides bundled versions of third-party libraries that are approved for reuse in one or more Eclipse projects.

#
# Update Sites

Orbit's primary update site is the following:

- https://download.eclipse.org/tools/orbit/simrel/orbit-aggregation/

The `orbit-aggregation` update site, as the name suggests, is an aggregtion of the following sites:

- https://download.eclipse.org/tools/orbit/simrel/orbit-legacy/
- https://download.eclipse.org/tools/orbit/simrel/maven-osgi/
- https://download.eclipse.org/tools/orbit/simrel/maven-sign/
- https://download.eclipse.org/tools/orbit/simrel/orbit-legacy

As a convenience, this Jetty site is also provided:

- https://download.eclipse.org/tools/orbit/simrel/maven-jetty/

All these sites are managed by JustJ's [`org.eclipse.justj.p2.manager`](https://eclipse.dev/justj/?page=tools#p2-anatomy) application
and hence follow the general documented structure.
Morever, the sites are self documenting, so please visit the above links to determine the most appropriate URL to use for your project's builds.

# Eclipse Orbit SimRel

The Eclipse Orbit SimRel repository provides infrastructure for managing 3rd party dependencies based directly on libraries hosted at Maven Central:

- https://github.com/eclipse-orbit/orbit-simrel
- https://github.com/eclipse-orbit/orbit-simrel#readme
- https://github.com/eclipse-orbit/orbit-simrel/issues
- https://github.com/eclipse-orbit/orbit-simrel/discussions

# Eclipse Orbit Legacy

The Eclipse Orbit Legacy repository provides 3rd party dependencies directly as source bundles. 
This is primarily for the case of libraries for which there is no source hosted at Maven Central:

- https://github.com/eclipse-orbit/orbit-legacy
- https://github.com/eclipse-orbit/orbit-legacy#readme
- https://github.com/eclipse-orbit/orbit-legacy/issues
- https://github.com/eclipse-orbit/orbit-legacy/discussions

#

### ~~Eclipse Bundle Recipes - Archvied~~

~~The Eclipse Bundle Recipes (EBR) repository provides Maven plug-ins for wrapping plain old Java jars as OSGi bundles:~~

- ~~https://github.com/eclipse-orbit/ebr~~

### ~~Eclipse Orbit - Archived~~

~~The Eclipse Orbit repository provides recipes for building OSGi bundles using EBR:~~

- ~~https://github.com/eclipse-orbit/orbit~~

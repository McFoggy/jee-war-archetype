# jee-war-archetype

Ready to use maven archetype generating jee compliant maven web project.

## Generated project content:

- war based project
- versioning using [jgitver](https://github.com/jgitver/jgitver-maven-plugin)
- CDI enabled
- JAX-RS activated
- unit testing enabled:
  - unit testing
  - integration tests using arquillian chameleon
  
## Usage

simply call `mvn archetype:generate -Dfilter=fr.brouillard.oss:jee-war-archetype` and follow instructions

## Development

use `mvn archetype:generate -DarchetypeCatalog=local` to use only archetypes built locally and thus avoid to retrieve remote versions 
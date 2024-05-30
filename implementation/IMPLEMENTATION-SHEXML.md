This is the report of the RSMD guidelines implementation for the [ShExML engine](https://github.com/herminiogg/ShExML)

# Before

## Aspect 1
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-1.1](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-11) |  ⭐⭐⭐ | ✅ | The repository contains a README and the project uses build.sbt file for dependency management containing metedata. Codemeta can be included as an improvement |
| [RSMD-1.2](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-12) |  ⭐⭐⭐ | ⚠️ | The software is present in [Maven Central](https://central.sonatype.com/artifact/com.herminiogarcia/shexml_3) and in [Scaladex](https://index.scala-lang.org/herminiogg/shexml). Registering this repository in Zenodo could improve the coverage of this recommendation. |
| [RSMD-1.3](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-13) |  ⭐⭐ | ✅ | The project uses Git as the version control system. The CodeRepository property can be included ti improve the metadata. |
| [RSMD-1.4](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-14) |  ⭐ | ⚠️ | The software is developed using normal Scala, idiomatic constructions and supporting cross-compilation, however no guidelines are explicitly mentioned |
| [RSMD-1.5](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-15) |  ⭐ | ❌ | The metadata is not centralised |

## Aspect 2
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-2.1](https://fair-impact.github.io/RSMD-guidelines/2.Accessibility_preservation/#rsmd-21) |  ⭐⭐⭐ | ❌ | Not archived anywhere apart from the Github repository |
| [RSMD-2.2](https://fair-impact.github.io/RSMD-guidelines/2.Accessibility_preservation/#rsmd-22) |  ⭐⭐⭐ | ❌ | Not archived in a scholarly repository |
| [RSMD-2.3](https://fair-impact.github.io/RSMD-guidelines/2.Accessibility_preservation/#rsmd-23) |  ⭐⭐ | ❌ | Not registered in a disciplinary registry. However, it is difficult to determine in which it should be registered. |

## Aspect 3
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-3.1](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-31) |  ⭐⭐⭐ | ✅ | Versions are provided both through he [version control system in form of releases](https://github.com/herminiogg/ShExML/releases) and also through  Maven central. |
| [RSMD-3.2](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-32) |  ⭐⭐⭐ | ⚠️ | The SWHID system is not adopted but it is possible to access unambigously different parts of the code throught the Github URL system (to clarify the reach of this method to cover this recommendation.) |
| [RSMD-3.3](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-33) |  ⭐⭐⭐ | ⚠️ | Software versions, modules and projects can be identified through the Scala project in the Github structure which is exported to Maven Central and Scaladex. However, it can benefit from using DOIs through Zenodo as part of the RSMD-2.2 implementation. |
| [RSMD-3.4](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-34) |  ⭐ | ✅ | The project tries to follow semver as much as possible while also using git tags to mark the versions. |
| [RSMD-3.5](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-35) |  ⭐⭐ | ❓ | TO DO: Clarify |

## Aspect 4
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-4.1](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-41) |  ⭐⭐⭐ | ✅ | The README file provides the software's name and description. Additionally when the codemeta file is provided these attributes will be provided here too. |
| [RSMD-4.2](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-42) |  ⭐⭐ | ❌ | Right now only limited extrinsic descriptive metadata is included. When implementing codemeta in the repository this should be solved. |
| [RSMD-4.3](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-43) |  ⭐⭐ | ⚠️ | Related scientific publications are present in the README file, however, they do not include a DOI. |
| [RSMD-4.4](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-44) |  ⭐⭐ | ⚠️ | A package manager is present in the project, however, implementing the codemeta metadata file could potentially make it more accesible.  |
| [RSMD-4.5](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-45) |  ⭐ | ⚠️ | Some of the proposed attributes are present (i.e., website and list of functionality) but the others should be included in the future to improve this aspect. |

## Aspect 5
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-5.1](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-51) |  ⭐⭐⭐ | ⚠️ | The authors and contributors are identified by the Github repository and they are also identified in the package manager metadata. However, including them in the codemeta metadata could benefit its findability. |
| [RSMD-5.2](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-52) |  ⭐⭐⭐ | ❌ | The authors are identified by the Github repository and they are also identified in the package manager metadata. However, including them in the codemeta file could benefit its findability. |
| [RSMD-5.3](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-53) |  ⭐⭐ | ❌ | People are not identified with a non-ambiguous identifier. |
| [RSMD-5.4](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-54) |  ⭐⭐ | ❌ | Roles for software actors are not included right now. |
| [RSMD-5.5](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-55) |  ⭐⭐ | ⚠️ | The citation preference is included in the README. It could be interesting to include the CITATION.cff, but what to cite: the software via for example Zenodo, or the scientific publications. |
| [RSMD-5.6](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-56) |  ⭐ | ❌ | This is not implemented. |
| [RSMD-5.7](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-57) |  ⭐ | ⚠️ | While this is not explicitly supported the software only an author. |

## Aspect 6
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-6.1](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-61) |  ⭐⭐⭐ | ✅ | The software does not belong to any organisation in particular as it has been funded by different funding schemes. Therefore, the most suitable license is the most open as possible licence which the project implements in the form of a MIT license. |
| [RSMD-6.2](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-62) |  ⭐⭐⭐ | ✅ | A LICENSE file is provided within the repository. |
| [RSMD-6.3](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-63) |  ⭐⭐⭐ | ⚠️ | The software provides some extrinsic metadata about the license by means of the package manager. Therefore, this information is offered through Maven Central to the library users. However, including this information in order extrinsic metadata providers, like Zenodo, could benefit other potential users. |
| [RSMD-6.4](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-64) |  ⭐⭐ | ⚠️ | The study was done prior to the selection of the license and it is taken into account when changing a library. However, this study was never published. |
| [RSMD-6.5](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-65) |  ⭐ | ❌ | Not implemented. |

## Aspect 7
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-7.1](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-71) |  ⭐⭐⭐ | ✅ | The dependencies are enlisted in the build.sbt file required by the SBT package manager. |
| [RSMD-7.2](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-72) |  ⭐⭐⭐ | ⚠️ | This is only partially mentioned stating that is a JVM compatible library with a CLI interface. Minimal versions can contribute to a further understanding of the limitations. |
| [RSMD-7.3](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-73) |  ⭐⭐ | ❌ | The hardware requirements are not mentioned. |
| [RSMD-7.4](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-74) |  ⭐⭐ | ❌ | The build instructions are not included. However, there is an ample suite of tests. |
| [RSMD-7.5](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-75) |  ⭐⭐ | ⚠️ | There is some degree of user documentation but more examples and a link to the specification can improve this aspect. |
| [RSMD-7.6](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-76) |  ⭐ | ❌ | Not implemented. |
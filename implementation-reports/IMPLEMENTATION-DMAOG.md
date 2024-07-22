This is the report of the RSMD guidelines implementation for the [DMAOG tool](https://github.com/herminiogg/DMAOG) including the pre-assesment, the list of taken actions and the post-assesment

# Before

## Aspect 1
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-1.1](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-11) |  ⭐⭐⭐ | ✅ | The repository contains a README and the project uses build.sbt file for dependency management containing metedata. Codemeta can be included as an improvement |
| [RSMD-1.2](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-12) |  ⭐⭐⭐ | ⚠️ | The software is present in [Maven Central](https://central.sonatype.com/artifact/com.herminiogarcia/dmaog_3) and in [Scaladex](https://index.scala-lang.org/herminiogg/dmaog). Registering this repository in Zenodo could improve the coverage of this recommendation. |
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
| [RSMD-3.1](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-31) |  ⭐⭐⭐ | ✅ | Versions are provided both through he [version control system in form of releases](https://github.com/herminiogg/DMAOG/releases) and also through Maven central. |
| [RSMD-3.2](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-32) |  ⭐⭐⭐ | ⚠️ | The SWHID system is not adopted but it is possible to access unambigously different parts of the code throught the Github URL system (to clarify the reach of this method to cover this recommendation.) |
| [RSMD-3.3](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-33) |  ⭐⭐⭐ | ⚠️ | Software versions, modules and projects can be identified through the Scala project in the Github structure which is exported to Maven Central and Scaladex. However, it can benefit from using DOIs through Zenodo as part of the RSMD-2.2 implementation. |
| [RSMD-3.4](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-34) |  ⭐ | ✅ | The project tries to follow semver as much as possible while also using git tags to mark the versions. |
| [RSMD-3.5](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-35) |  ⭐⭐ | ❌ | It is necessary to provide more intrinsic and extrinsic identifiers through Zenodo, HAL, and Software Heritage. |

## Aspect 4
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-4.1](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-41) |  ⭐⭐⭐ | ✅ | The README file provides the software's name and description. Additionally when the CodeMeta file is provided these attributes will be provided here too. |
| [RSMD-4.2](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-42) |  ⭐⭐ | ❌ | Right now only limited extrinsic descriptive metadata is included. When implementing CodeMeta in the repository this should be solved. |
| [RSMD-4.3](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-43) |  ⭐⭐ | ⚠️ | There are not related publications to be cited as the only one is still under review . |
| [RSMD-4.4](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-44) |  ⭐⭐ | ⚠️ | A package manager is present in the project, however, implementing the CodeMeta metadata file could potentially make it more accesible.  |
| [RSMD-4.5](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-45) |  ⭐ | ⚠️ | Some of the proposed attributes are present (i.e., list of functionalities) but the others should be included in the future to improve this aspect, both in the CodeMeta and in the README. Special attention requires the website which has been developed but never included here. |

## Aspect 5
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-5.1](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-51) |  ⭐⭐⭐ | ⚠️ | The authors and contributors are identified by the Github repository and they are also identified in the package manager metadata. However, including them in the CodeMeta metadata could benefit its findability. |
| [RSMD-5.2](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-52) |  ⭐⭐⭐ | ❌ | The authors are identified on the Github repository and they are also identified in the package manager metadata. However, including them in the CodeMeta file could benefit their findability. |
| [RSMD-5.3](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-53) |  ⭐⭐ | ❌ | People are not identified with a non-ambiguous identifier. |
| [RSMD-5.4](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-54) |  ⭐⭐ | ❌ | Roles for software actors are not included right now. |
| [RSMD-5.5](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-55) |  ⭐⭐ | ❌ | The citation preference is not included anywhere as there is not a proper scientific article describing it. However, including a CITATION.cff to cite the software can be helpful. |
| [RSMD-5.6](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-56) |  ⭐ | ❌ | This is not implemented. |
| [RSMD-5.7](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-57) |  ⭐ | ⚠️ | While this is not explicitly supported, the software only has an author. |

## Aspect 6
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-6.1](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-61) |  ⭐⭐⭐ | ✅ | The software does not belong to any organisation in particular. Therefore, the most suitable license is the most open as possible licence which the project implements in the form of a MIT license. |
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
| [RSMD-7.5](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-75) |  ⭐⭐ | ⚠️ | There is some degree of user documentation but more examples and developing a proper documentation can help future users. |
| [RSMD-7.6](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-76) |  ⭐ | ❌ | Not implemented. |

# Taken actions
1. First step for this tool was to upload it to Zenodo so the already generated workflow for the CodeMeta file generation could be adapted to it.
2. The workflow for generating a CodeMeta file for ShExML was adapted to DMAOG. As both projects are quite similar and they are coded following the same conventions the adaptation was small and quite straightforward.
3. Request made on Software Heritage to archive the repository.
4. CodeMeta file added to the repository and badges for Zenodo and Software Heritage.
5. Added CITATION.cff file using the DOI provided by Zenodo.
6. Using the new SWHID the software was deposit to the HAL repository.
7. The README was improved including some of the suggested sections that were missing. Additionaly, a link to the main website was also included.

# After
## Aspect 1
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-1.1](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-11) |  ⭐⭐⭐ | ✅ | Already compliant before. |
| [RSMD-1.2](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-12) |  ⭐⭐⭐ | ✅ | The sofware artefact is now available on [Zenodo](https://zenodo.org/records/12782290) too. |
| [RSMD-1.3](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-13) |  ⭐⭐ | ✅ | Already compliant before. |
| [RSMD-1.4](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-14) |  ⭐ | ⚠️ | The software is developed using normal Scala, idiomatic constructions and supporting cross-compilation, however no guidelines are explicitly mentioned |
| [RSMD-1.5](https://fair-impact.github.io/RSMD-guidelines/1.General/#rsmd-15) |  ⭐ | ❌ | The metadata generation is not yet centralised, even though it has improve a lot. |

## Aspect 2
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-2.1](https://fair-impact.github.io/RSMD-guidelines/2.Accessibility_preservation/#rsmd-21) |  ⭐⭐⭐ | ✅ | The repository is now archived in the Software Heritage archive. |
| [RSMD-2.2](https://fair-impact.github.io/RSMD-guidelines/2.Accessibility_preservation/#rsmd-22) |  ⭐⭐⭐ | ✅ | Now it is available in Zenodo and HAL. |
| [RSMD-2.3](https://fair-impact.github.io/RSMD-guidelines/2.Accessibility_preservation/#rsmd-23) |  ⭐⭐ | ⚠️ | Not registered in a disciplinary registry as it is difficult to determine one that applies to this field. Nevertheless, it is now much more visible thanks to its inclusion in Zenodo, HAL and Software Heritage. |

## Aspect 3
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-3.1](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-31) |  ⭐⭐⭐ | ✅ | Already compliant before. |
| [RSMD-3.2](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-32) |  ⭐⭐⭐ | ✅ | The SWHID system is adapted through its inclusing in Software Heritage. |
| [RSMD-3.3](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-33) |  ⭐⭐⭐ | ✅ | The software has now a DOI thanks to its inclusion in Zenodo. |
| [RSMD-3.4](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-34) |  ⭐ | ✅ | Already compliant before. |
| [RSMD-3.5](https://fair-impact.github.io/RSMD-guidelines/3.Reference_identification/#rsmd-35) |  ⭐⭐ | ✅ | A good level of intrinsic and extrinsic identifiers is now provided due to the use of Zenodo, HAL and Software Heritage. |

## Aspect 4
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-4.1](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-41) |  ⭐⭐⭐ | ✅ | Already compliant before. |
| [RSMD-4.2](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-42) |  ⭐⭐ | ✅ | A CodeMeta file was included in the repository including extrinsic and intrinsic metadata. |
| [RSMD-4.3](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-43) |  ⭐⭐ | ⚠️ | There are not related publications to be cited as the only one is still under review . |
| [RSMD-4.4](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-44) |  ⭐⭐ | ✅ | The CodeMeta file gets metadata from the package manager to populate the concerning fields.  |
| [RSMD-4.5](https://fair-impact.github.io/RSMD-guidelines/4.Description_Classification/#rsmd-45) |  ⭐ | ✅ | More information have been introduced to improve the README. |

## Aspect 5
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-5.1](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-51) |  ⭐⭐⭐ | ✅ | Authors are defined in the package manager and in the CodeMeta file. |
| [RSMD-5.2](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-52) |  ⭐⭐⭐ | ✅ | Authors are present in the CodeMeta file. |
| [RSMD-5.3](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-53) |  ⭐⭐ | ✅ | ORCID identifiers are used for authors. |
| [RSMD-5.4](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-54) |  ⭐⭐ | ✅ | Roles for software actors are included right now. Future improvement, use a controlled vocabullary. |
| [RSMD-5.5](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-55) |  ⭐⭐ | ✅ | A citation file was introduced in the repository that allows to cite the research software. |
| [RSMD-5.6](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-56) |  ⭐ | ❌ | This is not implemented. |
| [RSMD-5.7](https://fair-impact.github.io/RSMD-guidelines/5.Credit_Attribution/#rsmd-57) |  ⭐ | ⚠️ | There is only one author who is the owner. |

## Aspect 6
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-6.1](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-61) |  ⭐⭐⭐ | ✅ | Already compliant before. |
| [RSMD-6.2](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-62) |  ⭐⭐⭐ | ✅ | Already compliant before. |
| [RSMD-6.3](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-63) |  ⭐⭐⭐ | ✅ | This data has been introduced in the CodeMeta file as well as in the Zenodo records. |
| [RSMD-6.4](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-64) |  ⭐⭐ | ✅ | The study on the licenses of the used dependencies has been added to the README. |
| [RSMD-6.5](https://fair-impact.github.io/RSMD-guidelines/6.Reuse_legal/#rsmd-65) |  ⭐ | ❌ | Not implemented. |

## Aspect 7
| Recommendation | Priority | Status | Note |
|----------------|----------|--------|------|
| [RSMD-7.1](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-71) |  ⭐⭐⭐ | ✅ | Already compliant before. |
| [RSMD-7.2](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-72) |  ⭐⭐⭐ | ✅ | Minimal versions are now provided in the README. |
| [RSMD-7.3](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-73) |  ⭐⭐ | ❌ | The hardware requirements are not mentioned. |
| [RSMD-7.4](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-74) |  ⭐⭐ | ✅ | The build instructions are now included in the README file. |
| [RSMD-7.5](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-75) |  ⭐⭐ | ⚠️ | There is some degree of user documentation but more examples and developing a proper documentation can help future users. |
| [RSMD-7.6](https://fair-impact.github.io/RSMD-guidelines/7.Re-execute/#rsmd-76) |  ⭐ | ❌ | Not implemented. |
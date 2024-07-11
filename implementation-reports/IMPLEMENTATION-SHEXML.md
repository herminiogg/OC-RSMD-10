This is the report of the RSMD guidelines implementation for the [ShExML engine](https://github.com/herminiogg/ShExML) including the before assesment, the list of taken actions and the after assesment

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

# Taken actions
1. Given the already existing extrinsic metadata providers (i.e., Github and Maven) I developed the crosswalks for both of them.
2. As ShExML was not on Zenodo I enabled the repository synchronisation but this inevitably forces to create a new release which interrupts the normal release workflow in the tool. Therefore, a "fake" payload was sent to Zenodo's API to have an older version of ShExML registered.
3. Once on Zenodo the crosswalk for Zenodo was also developed.
4. After having the three main crosswalks implemented a customised codemeta generation workflow was designed for ShExML based on these three providers and some custom attributes.
5. The conversion worked well, but when trying to validate it against the [Codemeta generator validator](https://codemeta.github.io/codemeta-generator/) it failed due to ShExML always generating a non-framed JSON-LD version.
6. After some investigation on how to frame JSON-LD files, two contexts files were developed for the crosswalks and for the ShExML custom mapping alongside a Groovy script that reads the non-framed output, the context file and generates a framed version which is correctly validated by the Codemeta generator.
7. In order to provide persistent identifiers for the different parts of the code as suggested by the guidelines, I started to investigate the possibilty to add the repository to the Software Heritage archive which to my surprise was already added. Therefore, I just only asked to "Save the code now" to have a more recent version.
8. Badges for Zenodo and Software Heritage archive were added to the repository README
9. A CITATION.cff was included in the repository using the DOI provided by Zenodo. As for the remaining question on what is preferrable to cite I left the academic publications in the README but also included a proper way to cite the software as it is [suggested by Github](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files) in order to get a better recognition of these contributions.
10. A new version of ShExML was released (v0.5.3) including the codemeta.json file in the root of the repository. The workflow works well but given the link between Github releases and Zenodo publications it requires a two-step process (before and after Zenodo). This is not a problem for now but whenever Zenodo implements CodeMeta imports it might require to leave some problematic attributes out of the process (e.g., releaseNotes) and keep only the generic ones.
11. In order to avoid the two-step CodeMeta generation process and avoid future problems when Zenodo implementens the support for CodeMeta, the two conflicting attributes (namely, the publicationDate and the releaseNotes) which are now pulled from the Github releases API path. In addition, the attributes issueTracker and downloadUrl were not processed in the JSON-LD framed version due to a problem in the IRI format. Apart from that, the role of the author was added and a referencePublication too.
12. The README was improved including the minimal requirements for executing the software, the DOIs for the related publications, build and testing instructions and a summary of the dependencies used alognside their license. Moreover, the new version of the CodeMeta file (generated in the step 11) was included.
13. The new content of the ShExML repository was saved again in Software Heritage to then import this metadata in HAL.

# After

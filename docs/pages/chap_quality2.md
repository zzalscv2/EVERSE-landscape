## Quality aspects: Standardization

### Relevance of quality aspects

![Relevance of quality aspects](figures/plot_multirating_A94_software_implemented.png)
### Implementation of quality aspects

![Implementation of quality aspects](figures/plot_multirating_A94_software_importance.png)
### Tools to Use standard protocols and APIs

|    | Which specific guidelines or tools are you aware of that help to enable the quality aspects? Provide short descriptions and/or URLs if possible, leave empty if there are no specific guidelines or tools. Use standard protocols and APIs :Guidelines                   | Which specific guidelines or tools are you aware of that help to enable the quality aspects? Provide short descriptions and/or URLs if possible, leave empty if there are no specific guidelines or tools. Use standard protocols and APIs :Tools   |
|---:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  2 | For instance GA4GH Cloud Workstream standards                                                                                                                                                                                                                            | [https://www.ga4gh.org/work_stream/cloud/](https://www.ga4gh.org/work_stream/cloud/)                                                                                                                                                                |
| 12 | Use standard API specifications like OpenAPI and standard query languages like SPARQL                                                                                                                                                                                    | [https://www.openapis.org/what-is-openapi](https://www.openapis.org/what-is-openapi) [https://www.w3.org/TR/sparql11-query/](https://www.w3.org/TR/sparql11-query/)                                                                                 |
| 20 | For back-end implementations use standard HTTP responses with meaningful descriptions of errors. Error from the client and the server needs to have different error codes, and it should not respond with an ok status code but containing an error in the response body |                                                                                                                                                                                                                                                     |

### Tools to Use coding conventions and style

|    | Which specific guidelines or tools are you aware of that help to enable the quality aspects? Provide short descriptions and/or URLs if possible, leave empty if there are no specific guidelines or tools. Use coding conventions and style :Guidelines   | Which specific guidelines or tools are you aware of that help to enable the quality aspects? Provide short descriptions and/or URLs if possible, leave empty if there are no specific guidelines or tools. Use coding conventions and style :Tools   |
|---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  2 | Community accepted coding conventions                                                                                                                                                                                                                     |                                                                                                                                                                                                                                                      |
| 10 | There are many different conventions in the community - several use the google coding styles                                                                                                                                                              | [https://google.github.io/styleguide/cppguide.html](https://google.github.io/styleguide/cppguide.html)                                                                                                                                               |
| 12 | Use IDEs like pyCharm, which have suggestions to follow established guidelines                                                                                                                                                                            | [https://www.jetbrains.com/pycharm/](https://www.jetbrains.com/pycharm/)                                                                                                                                                                             |
| 20 | Use standard developer tools, with automatic formatting and linters, which highlight errors and ensure standard code convenstions                                                                                                                         | The JetBrains suite for code development                                                                                                                                                                                                             |

### Tools to Ensure reusability of code

|    | Which specific guidelines or tools are you aware of that help to enable the quality aspects? Provide short descriptions and/or URLs if possible, leave empty if there are no specific guidelines or tools. Ensure reusability of code:Guidelines   | Which specific guidelines or tools are you aware of that help to enable the quality aspects? Provide short descriptions and/or URLs if possible, leave empty if there are no specific guidelines or tools. Ensure reusability of code:Tools   |
|---:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  2 | If you are publishing reusable components, like libraries, provide both semantic versioning and a stable API through the lifecycle, labeling backward incompatible changes with major semver changes, for instance                                 |                                                                                                                                                                                                                                               |
| 12 | same as above                                                                                                                                                                                                                                      | [https://www.jetbrains.com/pycharm/](https://www.jetbrains.com/pycharm/)                                                                                                                                                                      |
| 20 | Publish code into standard repositories, publish Docker containers to easily install softwares                                                                                                                                                     | GitHub, Docker, Docker registries, apt repository (for Debian/Ubuntu linux)                                                                                                                                                                   |

## Auto-created summary
### Summary of Mentioned Practices:

- **Use Standard Protocols and APIs**
  - **GA4GH Cloud Workstream Standards**: Standards provided by GA4GH for cloud workstream interoperability.
  - **OpenAPI and SPARQL**: Use standard API specifications like OpenAPI and query languages like SPARQL.
  - **Standard HTTP Error Responses**: Implement standard HTTP responses with meaningful error code distinctions between client and server errors.

- **Use Coding Conventions and Style**
  - **Community Accepted Conventions**: Follow coding conventions recognized by the community.
  - **Google Coding Styles**: Several community conventions align with Google's coding styles.
  - **IDE Tools like PyCharm**: Utilize integrated development environments like PyCharm for suggestions on following established guidelines.
  - **Automatic Formatting and Linters**: Employ developer tools with automatic formatting and error highlighting to maintain standard coding conventions.

- **Ensure Reusability of Code**
  - **Semantic Versioning and Stable API**: Provide semantic versioning and a stable API, marking backward incompatible changes with significant version updates.
  - **Publishing and Repositories**: Publish reusable code in standard repositories and provide Docker containers for easy software installation.

### Table of Linked URLs

| URL                                                                                  | Description                                                     |
|--------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| [https://www.ga4gh.org/work_stream/cloud/](https://www.ga4gh.org/work_stream/cloud/) | GA4GH Cloud Workstream standards                                |
| [https://www.openapis.org/what-is-openapi](https://www.openapis.org/what-is-openapi) | Information on OpenAPI specification                            |
| [https://www.w3.org/TR/sparql11-query/](https://www.w3.org/TR/sparql11-query/)       | W3C documentation for SPARQL 1.1 Query Language                  |
| [https://google.github.io/styleguide/cppguide.html](https://google.github.io/styleguide/cppguide.html) | Google coding style guidelines for C++                        |
| [https://www.jetbrains.com/pycharm/](https://www.jetbrains.com/pycharm/)             | PyCharm IDE by JetBrains                                        |
## Quality aspects: Standardization


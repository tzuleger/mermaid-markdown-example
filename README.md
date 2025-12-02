# mermaid-markdown-example
This repository has examples of how GitHub implicitly handles Mermaid markdown codeblocks and directly converts them into their appropriate charts/diagrams. 

Write the following code in your README (or any `.md` document):

````
```mermaid
# Mermaid code goes here
```
````

Example:

````
```mermaid
flowchart TD
    A[Christmas] -->|Get White Elephant Gift| B(Go shopping)
    B --> C{Plan for individual gift?}
    C -->|Plan for Jim| D[Free get-out-of-HR card]
    C -->|Plan for Katie| E[fa:fa-car hotwheel]
    C -->|Plan for Chris| F[fa:fa-guitar rad guitar]
```
````

```mermaid
flowchart TD
    A[Christmas] -->|Get White Elephant Gift| B(Go shopping)
    B --> C{Plan for individual gift?}
    C -->|Plan for Jim| D[Free get-out-of-HR card]
    C -->|Plan for Katie| E[fa:fa-car hotwheel]
    C -->|Plan for Chris| F[fa:fa-guitar guitar]
```

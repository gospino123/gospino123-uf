# Notes

## Current Websites
* [Admissions](https://admissions.ufl.edu)
* [Admissions Blog](https://admissions.ufl.edu/blog/)
* [Enrollment Management](https://em.ufl.edu)
* [Registrar](https://registrar.ufl.edu/)
* [Veterans Affairs](https://veterans.ufl.edu/)

## Helpful Links
* [HTML URL Encoding Reference](https://www.w3schools.com/tags/ref_urlencode.ASP) _Helpful for use with API calls with input text_
* [WebAIM Contrast Checker](https://open.spotify.com/track/2grjqo0Frpf2okIBiifQKs?si=003d98da1a004084) _Helpful for manual checks for color contrast issues_
* [Font Size Change in Browser for Users](https://www.computerhope.com/issues/ch000779.htm#:~:text=Press%20and%20hold%20the%20Ctrl,and%20decrease%20the%20font%20size.) _Helpful to see how people use resizing to view content better_
<!-- [myAssets - External User Portal](https://myassets.fa.ufl.edu/ext/#/home) _Helpful for foreign travel requests, off-site certification for assets and online shopping_ -->

<!--
## Emails
-->

## Useful Shortcuts

### General
| Windows | Web Browser | Xd | Zoom |
| :---: | :---: | :---: | :---: |
| Screen Record<br> `Win + Alt + R` | Recover Tab<br> `Ctrl + Shift + T` | Scroll Horizontally<br> `Shift + Scroll` | Hide Bar (for remote IT help)<br> `Ctrl + Alt + Shift + H` |
| Screen Capture<br> `Win + Shift + S` | | | Microphone Toggle<br> `Alt + A` |
| | | | Share Screen Prompt<br> `Alt + S` |

### Web Development

#### Bash (WIP)
`npm run dev` (admissions)

`npm run start` (em?)

#### Node
`npm install cmder` &rarr; Install Cmder

##### VSCode
From Command Prompt, `code .` opens current folder in code

##### Git (WIP)
* `git cherry-pick`
  * `git cherry-pick commit-SHA` _Merges a particular commit_
  * `git cherry-pick first-commit-SHA-in-range^..last-commit-SHA-in-range` _Merges a range of commits including the first in range_
    * In `git cherry-pick A..B`, A should be older than B
  * `git cherry-pick first-commit-SHA-in-range..last-commit-SHA-in-range` _Merges a range of commits **NOT** including the first in range_

##### Bookmarklets (WIP)
<!--
`javascript:alert($(window).height());` &rarr; Get current window height in a browser alert

`javascript:alert($(window).width());` &rarr; Get current window width in a browser alert

_Note: These cannot be copy/pasted into the URL and some pages may prevent the alert from appearing._
-->

## Terminology

### EM
Yield: Period in which students get accepted and decide where they will go to university

#### Designers
_Example View_

Orphan
```
    ~~~
    ~~~
~~~   
 x
```
Widow
```
     x
    ~~~
~~~ ~~~
~~~
```
Runt
```
     x
~~~ ~~~
~~~
~~~
```

### ITSM
#### ITSM Workflow Process
```mermaid
flowchart LR
    A[Detect] --> B[Record];
    B --> C{Classify};
    C -.-> D[Incident];
    D -.-> E[Investigate];
    E -.-> I[Resolve];
    C -.-> F[Request];
    F -.-> G[Fulfill];
    G -.-> I[Resolve];
    I --> J[Close];
```

#### Incident Triage

|   | Low Impact | Medium Impact | High Impact |
| :---: |  :---: | :---: | :---: |
| Low Urgency | 1 | 2 | 3 |
| Medium Urgency | 2 | 3 | 4 |
| High Urgency | 3 | 4 | 5 |

*Impact: Number of users/items affected/influenced*
*Urgency: Based on time until significant impact*

### T4\*
[T4 Training Resources](https://webservices.it.ufl.edu/t4/t4-training/)

**\* Side project**

## In Progress

### Workflow

* Remember to frequently use `git fetch` and `git pull`

<!-- HIDDEN UF WORKFLOW TEMPLATE
#### mermaid

```mermaid
gantt
title Deadlines
dateFormat MM/DD/YY
section Am I In
section Yield
section MLK
Add Alert     :done,      a1, 01/14/22, 1d
Monitor Alert :active,    a2, 01/14/22,01/18/22
MLK Day       :milestone, a3, 01/18/22, 24h
Remove Alert  :after a2     , 0d
```
-->

[Mermaid Documentation](https://mermaid-js.github.io/mermaid/#/)
##### Flowchart
```
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```  

##### Sequence Diagram
```
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

##### Gantt Diagram
```mermaid
gantt MD;
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```

### Hueso

#### Row
| M &rarr; L | B | M &rarr; T | B | M &rarr; L |
| :---: | :---: | :---: | :---: | :---: |
| 1 to 4 | 1 | 1 to 2 | 1 | 1 to 4 |

<!-- 
### Run

#### Naming Conventions
- camelCase for vars
- underscores for images
- dashes for filenames
-->

#### Tips
<details><summary>Very Basic Sass Filing and <a href="https://itnext.io/structuring-your-sass-projects-c8d41fa55ed4">Article on Sass Filing</a> with more complex suggestions</summary>
    <pre>
        _base.scss
        _layout.scss
        _components.scss
        main.scss
    </pre>
</details>

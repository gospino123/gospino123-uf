# Notes

## Websites
<details><summary>Main Websites</summary>
 
 * [Admissions](https://admissions.ufl.edu)
 * [Admissions Blog](https://admissions.ufl.edu/blog/)
 * [Enrollment Management](https://em.ufl.edu)
 * [Registrar](https://registrar.ufl.edu/)
 * [Veterans Affairs](https://veterans.ufl.edu/)
 
</details>

<hr style="border:1px solid gray"> </hr>

* [Slate Emails](https://my.admissions.ufl.edu/manage/)

## Helpful Links

<details><summary>Web Accessibility</summary>
 
* [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)<br> _For manual checks for color contrast issues_
* [Font Size Change in Browser for Users](https://www.computerhope.com/issues/ch000779.htm#:~:text=Press%20and%20hold%20the%20Ctrl,and%20decrease%20the%20font%20size.)<br> _To see how people use resizing to view content better_
* [Color Blindness Filter Checker](https://www.toptal.com/designers/colorfilter/)<br> _Check ADA, CTA effectiveness and Gradient use_
* [Parallax Effects](https://webflow.com/accessibility/checklist/task/avoid-parallax-effects)
</details>

<hr>

<details><summary>Design</summary>
 
* [Image Optimization Perspective](https://www.jimdo.com/blog/optimize-website-images-for-better-design-seo/)<br> _Info on optimizing images for web_
* [Color Palette Generator](https://coolors.co)<br> _Tool to randomize a color palette_
* [Expand Palette on One Color](https://mycolor.space/)<br> _Tool to expand palette based on input_
* [Color Mixer](https://colordesigner.io/color-mixer)<br> _Tool for mixing colors_
* [Behance](https://www.behance.net/)<br> _Creative network for showcasing and discovering creative work_
* [Mobile First Design - Article by Adobe](https://xd.adobe.com/ideas/process/ui-design/what-is-mobile-first-design/)
</details>

<hr>

<details><summary>Development</summary>
 
* [HTML URL Encoding Reference](https://www.w3schools.com/tags/ref_urlencode.ASP)<br> _For use with API calls with input text_
* [Squoosh](https://squoosh.app/)<br> _For making image files smaller so they load faster (not necessary if using Image Optimizer on macOS)_
* [Lorem Picsum](https://picsum.photos/)<br> _For populating with random image with specified measurements_
* [Image Optimization Perspective](https://www.jimdo.com/blog/optimize-website-images-for-better-design-seo/)<br> _Info on optimizing images for web_
* [Git Stash Explained](https://www.freecodecamp.org/news/git-stash-explained/)<br> _Quick code/example on stash use_ 
* [Campaign URL Builder](https://ga-dev-tools.web.app/campaign-url-builder/)
* [QR Code Generator](https://www.qrcode-monkey.com/)
* [Approximate Hex Color to Filter for SVGs](https://codepen.io/sosuke/pen/Pjoqqp)<br> _Inaccurate approximation for color to filter use on SVGs_
* [Styling svg use Content](https://tympanus.net/codrops/2015/07/16/styling-svg-use-content-css/)<br> _Tips on using svg with css, specifically using svg use_
* [Fixing Focus Outlines](https://stackoverflow.com/questions/57605812/why-a-tags-set-as-displayblock-have-irregular-focus-outline-shape)<br> _For correcting the blob shape on outlines_
* [Favicons and OS Differences](https://sympli.io/blog/heres-everything-you-need-to-know-about-favicons-in-2020/)
* [Favicon Cheat Sheet](https://gist.github.com/leommoore/6415005)
* [Pug Beginners Guide](https://www.sitepoint.com/a-beginners-guide-to-pug/)

* [Web Accessible Nav Types from W3](https://www.w3.org/TR/wai-aria-practices/examples/menubar/menubar-navigation.html)
* [Web Accessible Website from Perkins School for the Blind](https://www.perkins.org/)

</details>
 
<!-- [myAssets - External User Portal](https://myassets.fa.ufl.edu/ext/#/home)<br> _For foreign travel requests, off-site certification for assets and online shopping_ -->
<!-- * [13 Days of Accessibility](http://a11ycalendar.kaseybon.com/)<br> _For gradually learning accessibility standards_ -->
<!-- [Apple Typography](https://developer.apple.com/design/human-interface-guidelines/ios/visual-design/typography/)<br> _For accessibility with research-backed data_ -->
<!-- [Create timezone date without string representation](https://stackoverflow.com/questions/439630/create-a-date-with-a-set-timezone-without-using-a-string-representation/439871#439871) -->
<!-- [Source for some window size functions](https://www.rapidtables.com/web/tools/window-size.html) _For getting window size and other useful utilities_ -->
<!-- [Why to use noopener noreferrer for links opening in another tab](https://stackoverflow.com/questions/50709625/link-with-target-blank-and-rel-noopener-noreferrer-still-vulnerable)
 -->
<!-- * [Standards for Various Technologies](https://spec.whatwg.org/) -->
<!-- * [Cybersecurity from Federal Agency](https://www.cisa.gov/) -->

<!--
## Emails
-->

## Personal Preferences for Naming Conventions
- **_camelCase_** for variables
    - camelCaseExample
- **_underscores_** for images
    - underscore_example
- **_dashes_** for filenames/folders
    - filename-or-folder-example

## Useful Shortcuts

### General
| Windows | Web Browser | Xd | Zoom |
| :---: | :---: | :---: | :---: |
| Screen Record<br> `Win + Alt + R` | Recover Tab<br> `Ctrl + Shift + T` | Scroll Horizontally<br> `Shift + Scroll` | Hide Bar (for remote IT help)<br> `Ctrl + Alt + Shift + H` |
| Screen Capture<br> `Win + Shift + S` | |Select items over area<br> `Shift + Click/Drag`| Microphone Toggle<br> `Alt + A` |
| | | | Share Screen Prompt<br> `Alt + S` |

### Web Development

<details><summary>Bash (WIP)</summary>
 <code>npm run dev</code> <span>(admissions)</span>
 <code>npm run start</code> <span>(em?)</span>
</details>

<!-- Add mermaid of website creation life cycle (include Continuous Improvement) -->

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

* [Git Stash Explained](https://www.freecodecamp.org/news/git-stash-explained/)
* Git Commit types (not strict):
  * **feat**: The new feature you're adding to a particular application
  * **fix**: A bug fix
  * **style**: Feature and updates related to styling
  * **refactor**: Refactoring a specific section of the codebase
  * **test**: Everything related to testing
  * **docs**: Everything related to documentation
  * **chore**: Regular code maintenance.[ You can also use emojis to represent commit types]
* Git Commit Example: 
  * `type(scope): subject` from [Art of Writing a Good Commit Message - Dev](https://dev.to/wordssaysalot/art-of-writing-a-good-commit-message-56o7)

  * Also, WIP: Work in progress, sort of an overarching miscellaneous


###### Branching Procedures
```mermaid
flowchart LR
 A([Master/Main]) ==> B[Main Commit];
 A -. Create branch to start Feature .-> D[Feature Commit #1];
 B ==> C{{Main Tip}};
 D -.-> E[Feature Commit #2];
 E -.-> F{{Feature Tip}};
 C == No Changes ==> G((New Merge Commit));
 F -- Merge into Master/Main --> G
```


##### Dev Tools
* `[].forEach.call($$("*"),function(a){a.style.outline="1px solid #"+(~~(Math.random()*(1<<24))).toString(16)})` _Input in console: Helpful for checking element layouts_

##### Bookmarklets (WIP)

* [Get window inner width](javascript: void(0); alert(innerWidth);)
* [Get window inner height](javascript: void(0); alert(innerHeight);)
<!--
[Source for some window size functions](https://www.rapidtables.com/web/tools/window-size.html)

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
#### Web Developers
Signifiers/Affordances: Indicators that show users how to interact with new objects/situations.
<!-- title: attribute of any HTML element but is most useful for interactive elements. They are usually defaulted as tooltips-->
<!-- Tip: Add cursor: pointer; to actual a element and not just onto a state of a -->

### ITSM
#### ITSM Workflow Process
```mermaid
flowchart LR
    A([Detect]) --> B[Record];
    B --> C{Classify};
    C -.-> D[Incident];
    D -.-> E[Investigate];
    E -.-> I[Resolve];
    C -.-> F[Request];
    F -.-> G[Fulfill];
    G -.-> I[Resolve];
    I --> J([Close]);
```

#### Incident Triage

|   | Low Impact | Medium Impact | High Impact |
| :---: |  :---: | :---: | :---: |
| Low Urgency | 1 | 2 | 3 |
| Medium Urgency | 2 | 3 | 4 |
| High Urgency | 3 | 4 | 5 |

*Impact: Number of users/items affected/influenced*<br>
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
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

##### Sequence Diagram
```mermaid
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
gantt
 dateFormat  YYYY-MM-DD
 title Adding GANTT diagram to mermaid
 excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2              :         des4, after des3, 5d
```

### Hueso

#### Row
| M &rarr; L | B | M &rarr; T | B | M &rarr; L |
| :---: | :---: | :---: | :---: | :---: |
| 1 to 4 | 1 | 1 to 2 | 1 | 1 to 4 |

#### Tips
<details><summary>Very Basic Sass Filing and <a href="https://itnext.io/structuring-your-sass-projects-c8d41fa55ed4">Article on Sass Filing</a> with more complex suggestions</summary>
    <pre>
        _base.scss
        _layout.scss
        _components.scss
        main.scss
    </pre>
</details>

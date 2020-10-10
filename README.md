# Code_Refactor_01

## User Story:

Marketing agency wants a codebase that follows accessibility standards, for optimization for search engines. Here is the [live site](https://themancalledzac.github.io/Edens_01_Code_Refactor_01/) to view changes.

## Acceptance Criteria:

```
1. Website meets accessibililty standards, including;
2. Semantic HTML Elements
3. HTML elements follow a logical structure independent of styling and positioning.
4. Img Alt attributes
5. Heading attributes in sequential order
6. Title element is a concise, descriptive title

```

## HTML Changes

```
1. Img alt tags for all images on page for accessibility.
2. Semantics change for Header (and child div Nav)
3. Semantics change for Main
4. Semantics change for Footer
5. Search Engine Optimization link now functions properly
6. changed the hero div to an id, added label.
Updated title to better reflect page.

```

![Original HTML](/assets/images/initial_index.PNG) ![Updated HTML](/assets/images/fixed_index.PNG)

## CSS Changes

```
1. Semantics change for header and child nav.
2. Consolidation for .benefits and it's children,
3. Consolidation for .content and it's children Divs, including div children img and h2.
4. Updated Main and Aside (.benefits and .content initially)tags from initial class elements.
5. Moved Main css above Aside css to match HTML
6. Semantics change for footer.
7. Updated .hero to #hero.
```

![Original CSS](/assets/images/initial_css.PNG) ![Updated CSS](/assets/images/fixed_css.PNG)

> The headers in this document say what labels should be attached to a task issue.

# All About Trees

> everything in this document should be under the `must-have` milestone

A simple little website about trees.

---

## `for: site-title` (_label_)

> - the site title should be developed on a _feature branch_ named `site-title`.
> - Each issue in this section should be developed on a branch of `site-title`, and merged with a PR.
> - when all of the issues in this section have been merged to `site-title`, `site-title` can be merged to `master`

### `type: html` (_label_)

> all issues under this header will have `for: site-title` _and_ `type: html`

- A website title for the tab (in the header of the document) (_issue_)
- A title in the web page (_issue_)
  - [ ] uses a class "centered" (_issue checklist_)

### `type: css` (_label_)

> all issues under this header will have `for: site-title` _and_ `type: css`

- "centered" class (_issue_)
  - [ ] centers an element horizontally along the page (_issue checklist_)

---

## `for: introduction` (_label_)

### `type: html` (_label_)

- A section with some fascinating words (_issue_)
  - [ ] uses a "fascinating-words" class
  - [ ] is a section element

### `type: css` (_label_)

- the "fascinating-words" class (_issue_)

---

## `for: main-text` (_label_)

### `type: html` (_label_)

- An article filled with wonder and interesting things (_issue_)
  - [ ] uses and "interesting-things" class

### `type: css` (_label_)

- the "interesting-things" class (_issue_)

---

## `for: further-reading` (_label_)

### `type: html` (_label_)

- An aside with a little text and a link for further reading (_issue_)
  - [ ] a link
  - [ ] the "aside-info" class
  - [ ] the "aside-text" class

### `type: css` (_label_)

- "aside-info" class (_issue_)
- "aside-text" class (_issue_)

---

## `for: site-navigation` (_label_)

### `type: html` (_label_)

- A navbar of site content links, clearly divided from the rest of the page (_issue_)
  - [ ] uses a "spaced-items" class
  - [ ] uses a "bottom-divider" class
- id's on all the site content containers (_issue_)
  - [ ] "summary-info"
  - [ ] "main-info"
  - [ ] "extra-info"

### `type: css` (_label_)

- the "spaced-items" class (_issue_)
- the "bottom-divider" class (_issue_)

---

## `for: contact-info` (_label_)

**As a site visitor, I want to know how I can contact the author so that I can make a new friend**

### `type: html` (_label_)

- A separated footer with some contact links (_issue_)
  - [ ] uses the "spaced-items" class
  - [ ] uses the "top-divider" class

### `type: css` (_label_)

- the "top-divider" class (_issue_)

---

## `for: finishing-touches` (_label_)

**As a perfectionist, I want everything perfect :)**

- Write final, complete README:
  - [makeareadme.com](https://www.makeareadme.com/)
  - [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
  - [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- Check for styling errors with a linter & prettify code
- Validate source code on w3 to check for any last mistakes

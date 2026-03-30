# Weber Lab's Website

In order to edit the website, you should ignore most `.html` files except the main `index.html`

The site is setup with jekyll and github actions. So when you edit the appropriate `.yml` or `.md` files, they will be converted to `.html`

## Config

The `config.yml` file contains the basic information and configuration for the site (theme, title, etc.)

## _pages

In `_pages` you will find folders for the different pages (team, software, etc.). Edit the `.md` file, not the `.html` file

*Note:* Ignore the `_pages/team` and `_pages/projects` folder (see below)

## _data

To change **Team Members**, edit `_data/team.yml`

To change **Projects**, edit `_data/projects.yml`


## Updating the Conferences Page

Conference entries are managed through `_pages/conferences/index.md`.

#### To add or edit a conference entry
1. Open `_pages/conferences/index.md`.
2. Find the correct year section (for example `## 2026`).
3. Add the conference under either:
   - `### Oral Presentations`
   - `### Poster Presentations`
4. Format each entry as:
   - without a separate page:
     ```markdown
     1. **ISMRM 2026:** **Author A, Author B, & Author C.** *Presentation Title.*
     ```
   - with a separate page:
     ```markdown
     1. **ISMRM 2026:** [**Author A & Author B.** *Presentation Title.*](/conferences/conference-lastname/)
     ```

#### When a separate page is needed
Create a new folder inside `_pages/conferences/` if more detail is available for that presentation, such as:
- abstract text
- poster content
- figures/images
- session details
- acknowledgements or references

The structure should look like:

```text
_pages/
  conferences/
    index.md
    conference-lastname/
      index.md
      figure1.png
      figure2.png
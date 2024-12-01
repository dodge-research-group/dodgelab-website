# [Dodge Lab Website](https://dodge-research-group.github.io/dodgelab-website/)

This website is based on the [Hugo Research Group Theme](https://github.com/wowchemy/starter-hugo-research-group). See below for details on how to make changes.

## Useful links

Hugo Blox [templates](https://hugoblox.com/templates/) come in two types of content blocks, those that use [Tailwind](https://hugoblox.com/blocks/) CSS and those that use [Bootstrap](https://bootstrap.hugoblox.com/blocks/). The Hugo Research Group Theme is a Bootstrap template. The Hugo Blox maintainer, George Cushen, [indicated](https://discord.com/channels/722225264733716590/1262792177923391589/1263580594952999084) on the Discord server that some users have adapted the Tailwind-based [Academic CV](https://hugoblox.com/templates/details/academic-cv/) template for use with a research group or university.

## Publications

The Hugo Blox documentation has [instructions](https://docs.hugoblox.com/reference/content-types/#publications) on how
to add publications automatically, but our current preferred method is just to duplicate the directory of an existing
publication and modify the contents accordingly. The directory name should be in the format `last_name-YYYY`, where
`last_name` is the last name of the first author, written all in lower case. Each directory requires an `index.md` file that includes the article title, authors, publication type, publication title, DOI, etc. The `publication-type` field
will typically be either `article-journal` for a published article or `article` for an arXiv preprint. A full list of CSL (citation style language) publication types are available
[here](https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types).
The directory should also include a `cite.bib` file with citation information in BibTeX format, which is usually available
at the journal website. Hugo Blox will link the article title to a separate summary page that can include additional
images and summary information, as described in the
[documentation](https://docs.hugoblox.com/reference/content-types/#enhancing-publications).

### Article PDFs

Check the journal reuse policy before including the PDF of a journal article on the group website. You can always post
the PDF of a preprint that appears on the arXiv, but many journals prohibit authors from posting the version that has
been formatted by the journal. Some journals even prohibit publishing any version that has been revised in response to
their peer review process.

#### Journals policies

- [AIP journals](https://publishing.aip.org/resources/researchers/rights-and-permissions/sharing-content-online/)
  - Includes *Applied Physics Letters* and *Journal of Applied Physics*
  - May post the accepted manuscript immediately after acceptance, using the credit line formatting below
  - May post the Version of Record (VOR) 12 months after publication, with the credit line and a link to the VOR on AIP Publishing’s site
  - After publication please use: “This article may be downloaded for personal use only. Any other use requires prior permission of the author and AIP Publishing. This article appeared in (citation of published article) and may be found at (URL/link for published article abstract).
  - Prior to publication please use: “The following article has been submitted to/accepted by [Name of Journal]. After it is published, it will be found at Link.”
- [Optica journals](https://opg.optica.org/content/author/portal/item/review-copyright-permissions/#posting)
  - *Optics Express*: Open access; version of record
  - *Applied Optics*: Transfer of copyright; accepted version
- [Nature journals](https://www.nature.com/nature-portfolio/editorial-policies/self-archiving-and-license-to-publish)
  - Preprints allowed
  - Accepted version after 6 months
- [Physical Review](https://journals.aps.org/copyrightFAQ.html#post)
  - Version of record

## Hugo Blox documentation links

[![Get Started](https://img.shields.io/badge/-Get%20started-ff4655?style=for-the-badge)](https://hugoblox.com/hugo-themes/)
[![Discord](https://img.shields.io/discord/722225264733716590?style=for-the-badge)](https://discord.com/channels/722225264733716590/742892432458252370/742895548159492138)  
[![Twitter Follow](https://img.shields.io/twitter/follow/GetResearchDev?label=Follow%20on%20Twitter)](https://twitter.com/wowchemy)

Easily write technical content with plain text Markdown, LaTeX math, diagrams, RMarkdown, or Jupyter, and import publications from BibTeX.

[Check out the latest demo](https://research-group.netlify.app/) of what you'll get in less than 60 seconds, or [view the showcase](https://hugoblox.com/creators/).

The integrated [**Wowchemy**](https://hugoblox.com) website builder and CMS makes it easy to create a beautiful website for free. Edit your site in the CMS (or your favorite editor), generate it with [Hugo](https://github.com/gohugoio/hugo), and deploy with GitHub or Netlify. Customize anything on your site with widgets, light/dark themes, and language packs.

- 👉 [**Get Started**](https://hugoblox.com/hugo-themes/)
- 📚 [View the **documentation**](https://docs.hugoblox.com/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- ⬇️ **Automatically import citations from BibTeX** with the [Hugo Academic CLI](https://github.com/GetRD/academic-file-converter)
- 🐦 Share your new site with the community: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- 🗳 [Take the survey and help us improve #OpenSource](https://forms.gle/NioD9VhUg7PNmdCAA)
- 🚀 [Contribute improvements](https://github.com/HugoBlox/hugo-blox-builder/blob/main/CONTRIBUTING.md) or [suggest improvements](https://github.com/HugoBlox/hugo-blox-builder/issues)
- ⬆️ **Updating?** View the [Update Guide](https://docs.hugoblox.com/hugo-tutorials/update/) and [Release Notes](https://github.com/HugoBlox/hugo-blox-builder/releases)

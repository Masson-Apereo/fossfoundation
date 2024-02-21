# How to Suggest Changes

:sparkles: :tada: Thanks for contributing! :tada: :star2:

All submissions **must** be licensed under [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html) or [MIT](https://spdx.org/licenses/MIT) for inclusion.  This provides for maximum re-use by others in other projects and simplifies the licensing [NOTICE](NOTICE) for this repository.

Substantiative changes, or changes to **descriptions** of specific FOSS Foundations should either be made by a GitHub user clearly associated with that Foundation's board or officers, or should include a comment pointing to a link on that Foundation's site validating the change.  Factual data about organizations is simple to verify with a link; however I want to be sure that each organization's officers can have a say in any descriptive text presented here about their Foundation.

## Issues vs. PRs

-  a specific fix or improvement: please open a GitHub Pull Request with the change.
-  a larger change to propose or new idea, add new data fields, or the like: please open a GitHub Issue to **start** a discussion before doing more work.

## How To Update Existing Data

- Ensure you are adding/updating accurate data.  Metadata should all be traceable back to an organization's official web presence, even if it's not a specific URL for each item.
- Markdown at tne end of each foundation.md file should only include factual and general descriptions, not marketing materials.
- Ensure any "last update" fields are filled in (this is an open design question: how do we annotate when various metadata fields were last updated/verified?)
- Submit a GitHub PR for the foundation.md file.
-  

## How To Add A New Foundation

- Copy [_data/foundation-template.md](https://raw.githubusercontent.com/Punderthings/fossfoundation/main/_data/foundation-template.md) as the base for a file.
- Decide on the shortest and most common name used for the foundation that would still be unique in the current open source space.
- Lowercase the name and remove any non-letter characters to make *shortname*.
- Create `_foundations/*shortname*.md` and fill in as many fields as you can verify (no guessing!)
  - Use [Schema.org NonprofitType](https://schema.org/NonprofitType) values, or leave blank if you're not sure
  - Leave both `---` YAML document separators, and update the body of the Markdown document with a single factual sentence that describes the foundation.
- Submit your PR!
- If you are adding a foundation that acts as a host for multiple open source projects, feel free to add a projects listing for that organization as a separate PR.  See examples in `_pages/projects.md` and scrapers in `assets/ruby/scrapers.rb`
  
Reminder: Please be [excellent to each other](CODE_OF_CONDUCT.md)!

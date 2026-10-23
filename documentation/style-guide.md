# Package-URL style guide

This document provides guidance for writing documentation for Package-URL
projects. It specifically applies to documentation for:
- The PURL specification from `package-url/purl-spec`,
- The VERS specification from `package-url/vers-spec,` and
- The Package-URL website from `package-url/packageurl.org`.

It is also recommended for documentation for any other project under the
`package-url` GitHub organization.

A key principle of this style guide is to align with "Ecma style" because much
of our documentation may eventually be added to ECMA-427 or ECMA-xxx-VERS.
See the end of this document and the Diction section for some specific points
about Ecma style.

Another key principle is to keep the grammar and diction simple following the
general principle of clear technical documentation and also to make the text
easier for non-native English speakers to understand or translate.

## Package-URL terminology
- PURL - use PURL all-caps for any general reference including cases such as
  PURL `type`
- VERS - use VERS all-caps for any general reference including cases such as
  VERS `type`
- Package-URL - primary use should be to be to refer the Package-URL
  organization on GitHub

## Specification versus standard
Specification and standard are often used interchangeably in software and
other technical domains and there is no practical way to enforce a distinction
in general. For Package-URL documentation and the website;
- Use "standard" to refer to the normative content of the ECMA standards for
  PURL (ECMA-427) or VERS (ECMA-xxx-VERS).
- Use "specification" to refer to broader informative content about PURL or
  VERS, such as the test schemas and test files. Over time, many elements of
  the broader specifications content will be added to the standards - i.e.,
  changing the content from informative to normative.

## Active voice
In general, use active voice (in which the grammatical subject of the sentence
is the person or thing performing the action) instead of passive voice (in
which the grammatical subject of the sentence is the person or thing being
acted upon). Make clear who is performing the action.

In passive voice, it is easy to neglect to indicate who or what is performing a
particular action. In passive voice, it is often hard for readers
to figure out who is supposed to do something (such as the reader, the
computer, the server, an end user, or a visitor to a web page).

## Use linear sentence structure
- Use linear sentence structure (Subject-Verb-Object) with a strong preference
  for short single topic sentences.
- Avoid concatenating sentences with semi-colons, colons and conjunctions.
  Sentences in a paragraph are inherently connected by their sequence.
- Avoid starting sentences with an introductory clause whenever possible.

## Capitalization
- Don't use unnecessary capitalization. Before you capitalize a word, think
  about why it should be capitalized.
- Don't rely on a difference in capitalization to convey meaning. For example,
  although people who are familiar with Kubernetes probably understand that a
  capitalized Pod is a Kubernetes unit, and a lowercase pod is any other kind
  of pod, that distinction is likely lost on many casual readers or those who
  are new to the domain.
- Don't use all-uppercase, except in the following contexts:
  - in official names
  - in abbreviations that are always written in all-caps
  - when referring to code that is written in all-caps
- Don't use camel case except in official names or when referring to code
  artifacts with a name in camel case.
- Avoid kebab case except except in official names or when referring to code
  artifacts with a name in kebab case.

## Use sentence case in headings, lists and tables
In document titles and headings, use sentence case. That is, capitalize only
the first word in the title, the first word in a subheading after a colon, or
any proper nouns or other terms that are always capitalized a certain way.
- Even though you're using sentence case, don't put a period at the end of a
  title or heading.
- Use sentence case for items in a list.
- Use sentence case for all the elements in a table: contents, headings,
  labels, and captions.

## Articles
- Use “a” or “an” with a singular-count noun when you mean “one of many,”
  “any,” or “in general.” Example: I like a good movie (one of many movies).
- Use “the” with any noun when the meaning is specific; for example, when
  the noun names the only one (or one) of a kind. Example: New York is the
  largest city in the United States (only one city can be “the largest”).
- Don’t use “a,” “an,” or “the” with a noun when you mean “any,” “in
  general.” Example: He gave me information (not specific).

## Diction
- Avoid unnecessary adjectives or adverbs, especially adverbs.
- Prefer singular over plural.
- Avoid using -ing verb forms as the first word in any heading or title.
  An -ing verb form is a present participle or gerund. These verb forms
  are inconsistently translated when they're used as the first word in a
  title, and they increase character count in limited spaces.
- Use Ecma/ISO standard style for key words related to standards in documents
  including description fields in a schema:
  - Use "shall" instead of "must" for format or behaviour that is required
    for conformance with a standard.
  - Use "should" for format or behaviour that is recommended, but not
    required by a standard.
  - Do not use "canonical" or "canonical form" in a standards document
    because standards content is canonical by definition. Use "valid" instead
    of "canonical" in most cases. Use of "canonical" in other non-standards
    documentation shall only refer to format or behaviour that conforms
    to a standard without any normalization.
- Use GB English for Ecma standard documents. Some examples are:
   - Use "artefact" instead of "artifact".
   - Use behaviour instead of behavior.
   - Use "licence" for the noun form and use "license" only for the verb form.
   - Use "normalize" or "normalization" instead of "normalise" or "
     "normalisation". The general rule for the "z" vs "s" cases like this
     is that you use the "z" spelling for words with a Greek origin.
   - Refer to "#" as hash sign, not number sign.
   - Use full stop instead of period.
   - Use license as a verb and licence as a noun.
  - "normalization" (see Section 6.1 Language) of [Ecma Directives: rules for editing and distribution](https://docs.google.com/document/d/1OpMkK5TTyEC38fij-353EOABpkYp_9Lm/edit)

### Package names
- Use “npm package”, not “NPM”, because “npm” is the package manager,
  not the name of a package.
- Use "Ruby gems" not RubyGems” because RubyGems is the name of a package
  distribution service, not the name of a package.

## Markdown text
- Use the GitHub dialect - see https://docs.github.com/en/get-started/writing-on-github
  and https://github.github.com/gfm/ for reference.
- Limit lines in a markdown file to 78 character lines to facilitate more
  accurate change tracking.

# Ecma style for standards

## Terminology
- ECMA is an acronym for the European Computer Manufacturers Association.
  ECMA was renamed to Ecma International in 1994.
- Ecma is an abbreviation for Ecma International.
- Use Ecma International when referring to the organization specifically.
- Use Ecma for most references, such as "Ecma standard" or "Ecma Technical
  Committee".
- Use ECMA only for referring to a standards document such as ECMA-4247 for
  PURL.

### Ecma document formatting
The text of a document may be sub-divided in clauses, which may again be
sub-divided. It is recommended that the number of levels does not exceed 3,
even if the text processing templates developed in Ecma allow for a maximum
of 5 levels.

## Code style (or not)
- Use code style (backticks) formatting when you are referring to a codebase
  file or folder.
- Use code style when you are referring to a field such as PURL `type`.
    - **NB**: this formatting may not apply for:
      - Standards sections like Scope (Clause 1) where PURL component names
        have not yet been defined as terminology.
      - In tables or in special sections like Clause 6.
    - **NB** Prior to Sept 2026 we were using bold instead of code style in
      most documents because of a misunderstanding about Ecma style. When you
      view ECMA-427 the text in code style is very hard to distinguish from
      bold. The actual difference is sans serif for code style vs. serif for
      bold, but this is very hard to see with individual words in the middle
      of text where both words are the same size.
- Use single quotes when you are referring to a field value.
- Use bold or double quotes for defined terms within the context of a
  document, but not for terms that are generally defined like PURL `type`.

## Punctuation for list items
- If every item is a complete sentence, then end each item with a full stop.
- If every item is a sentence fragment, the use a semicolon after each item
  except the last, which gets a full stop.
- If every item a measurement or other short text, then use no punctuation.
- Do not use initial caps or punctuation for a list item unless it is a
  sentence.

## References
- Draft (Feb 2026) of [Ecma Directives: rules for editing and distribution](https://docs.google.com/document/d/1OpMkK5TTyEC38fij-353EOABpkYp_9Lm/edit) - this a copy on the AboutCode package-url shared drive
- Ecmarkup: https://tc39.es/ecmarkup/

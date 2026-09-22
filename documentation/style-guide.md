# Package-URL style guide

This document provides guidance for writing documentation for Package-URL 
projects. It specifically applies to documentation for:
- The PURL specification from `package-url/purl-spec`,
- The VERS specification from `package-url/vers-spec` and
- The Package-URL website from `package-url/packageurl.org`.

It is also recommended for documentation for any other project under the 
`package-url` GitHub organization.

## Package-URL Terminology
- PURL - use PURL all-caps for any general reference including cases such as PURL **type**
- VERS - use VERS all-caps for any general reference including cases such as VERS **type**
- Package-URL - primary use should be to be to refer the Package-URL organization
  on GitHub

## Active voice
In general, use active voice (in which the grammatical subject of the sentence
is the person or thing performing the action) instead of passive voice (in 
which the grammatical subject of the sentence is the person or thing being 
acted upon). Make clear who is performing the action.

In passive voice, it is easy to neglect to indicate who or what is performing a 
particular action. In passive voice, it is often hard for readers 
to figure out who is supposed to do something (such as the reader, the 
computer, the server, an end user, or a visitor to a web page).

## Capitalization
- Don't use unnecessary capitalization; before you capitalize a word, think 
  about why it should be capitalized.
- Don't rely on a difference in capitalization to convey meaning. For example,
  although people who are familiar with Kubernetes probably understand that a 
  capitalized Pod is a Kubernetes unit, and a lowercase pod is any other kind 
  of pod, that distinction is likely lost on many casual readers or those who 
  are new to the domain.
- Don't use all-uppercase, except in the following contexts: in official 
  names, in abbreviations that are always written in all-caps, or when 
  referring to code that uses all-caps.
- Don't use camel case, except in official names or when referring to code 
  artifacts with a name in camel case.

## Use sentence case in headings, lists and tables
In document titles and headings, use sentence case. That is, capitalize only 
the first word in the title, the first word in a subheading after a colon, or 
any proper nouns or other terms that are always capitalized a certain way.
- Even though you're using sentence case, don't put a period at the end of a 
  title or heading.
- Use sentence case for items in a list.
- Use sentence case for all the elements in a table: contents, headings, 
  labels, and captions.

## Diction

- Avoid unnecessary adjectives or adverbs
- Avoid using -ing verb forms as the first word in any heading or title. 
  An -ing verb form is a present participle or gerund. These verb forms
  are inconsistently translated when they're used as the first word in a title,
  and they increase character count in limited spaces.
- Use Ecma/ISO standard style for key words related to standards in documents
  including description fields in a schema:
  - Use "shall" instead of "must" for format or behaviour that is required
    for conformance with a standard.
  - Use "should" for format or behaviour that is recommended, but not
    required by a standard.
  - Do not use "canonical" or "canonical form" in a standards document
    because standards content is canonical by definition. Use of "canonical"
    in other documentation shall only refer to format or behaviour that conforms
    to a standard without any normalization.
- Use GB English for Ecma standard documents. Some examples
  - behaviour
  - normalization (see Section 6.1 Language) of [Ecma Directives: rules for editing and distribution](https://docs.google.com/document/d/1OpMkK5TTyEC38fij-353EOABpkYp_9Lm/edit)
  - licence for the noun form, use license only for the verb form
 
## Line length
Limit lines in a markdown file to 78 character lines to facilitate more 
accurate change tracking.

## Code style (or not)
- Only use code style formatting when you are referring to a codebase file or folder
- Use bold when you are referring to a field such as PURL **type**
- Use single quotes when you are referring to a field value

## References
- Draft (Feb 2026) of [Ecma Directives: rules for editing and distribution](https://docs.google.com/document/d/1OpMkK5TTyEC38fij-353EOABpkYp_9Lm/edit) - this a copy on the AboutCode package-url shared drive
- Ecmarkup: https://tc39.es/ecmarkup/

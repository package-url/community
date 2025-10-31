# Package-URL style guide

This document provides guidance for writing documentation for Package-URL 
projects. It specifically applies to documentation for:
- The PURL specification from `package-url/purl-spec`,
- The VERS specification from `package-url/vers-spec` and
- The Package-URL website from `packag-url/packageurl.org`.

The style guide is also recommended for documentation for any other project 
under the `package-url` GitHub organization, but not mandatory.

## Package-URL Terminology
There is some terminology that we need to standardize for documentation, the 
website and comments in code. The current list is:

- PURL: use PURL (all-caps) to refer to the PURL specification or for a 
reference to a PURL in technical documentation, not code case. This is a 
convention from the ECMA standard.
- VERS: use VERS (all-caps) to refer to the VERS specification or for a 
reference to a VERS in technical documentation, not code case. This is a 
convention from the ECMA standard.
- Package-URL: Package-URL is tricky because we need to distinguish
between its meaning as a community that is reponsible for the PURL and VERS
specifications and its meaning as the full name for PURL. The primary
guideline is to use Package-URL to refer to the community and PURL to refer 
to the specification.
- Specification versus standard: Specification and standard are often used
interchangeably in software and other technical domains and there is no way
to prevent this in our community discussions. For documentation and the 
website;
   - Use **standard** to refer to the content of the ECMA standards for
PURL (first edition submitted to ECMA for December 2025 approval) or VERS 
(first edition to be submitted to ECMA for approval in June or December 2026).
   - Use **specification** to refer to the broader set of information about 
 PURL or VERS, such as the test schemas and test files. Over time, many
 elements of the specifications will be added to the standards

## Active voice

In general, use active voice (in which the grammatical subject of the sentence
is the person or thing performing the action) instead of passive voice (in 
which the grammatical subject of the sentence is the person or thing being 
acted upon), although there are exceptions. Make clear who's performing the 
action.

In passive voice, it's easy to neglect to indicate who or what is performing a particular action. In this kind of construction, it's often hard for readers 
to figure out who's supposed to do something (such as the reader, the 
computer, the server, an end user, or a visitor to a web page).

## Capitalization

- Don't use unnecessary capitalization; before you capitalize a word, think 
about why (and whether) it should be capitalized.
- Don't rely on a difference in capitalization to convey meaning. For example,
 although people who are familiar with Kubernetes probably understand that a 
 capitalized Pod is a Kubernetes unit, and a lowercase pod is any other kind 
 of pod, that distinction is likely lost on many casual readers or those who 
 are new to the domain.
- Don't use all-uppercase, except in the following contexts: in official 
names , in abbreviations that are always written in all-caps, or when 
referring to code that uses all-caps.
- Don't use camel case, except in official names or when referring to code 
that uses camel case.

## Use sentence case in headings, lists and tables

In document titles and headings, use sentence case. That is, capitalize only 
the first word in the title, the first word in a subheading after a colon, or 
any proper nouns or other terms that are always capitalized a certain way.
- Don't put a period at the end of a title or heading.
- Use sentence case for items in a list.
- Use sentence case for all the elements in a table: contents, headings, 
labels, and captions.

## Diction

When possible, avoid using -ing verb forms as the first word in any heading or  title. An -ing verb form is a present participle or gerund. These verb forms
are inconsistently translated when they're used as the first word in a title,
and they increase character count in limited spaces.

- Avoid unnecessary adjective or adverbs
- A vs the vs nothing
- GB English for Ecma standard documents


### Line length
Limit lines in a markdown file to 78 character lines to facilitate more 
accurate change tracking


### Code style
- When to use code style (or not)


## URL references
- How to refer to URLs - many options


## Ecma / ECMA
from the Ecma directives
The text of a document may be sub-divided in clauses, which may again be sub-divided. It is recommended that the number of levels does not exceed 3, 
even if the text processing templates developed in Ecma allow for a maximum 
of 5 levels.

### Terminology
- ECMA is an acronym for the European Computer Manufacturers Association. 
ECMA was renamed to Ecma International in 1994.
- Ecma is an abbreviation for Ecma International.
- Use Ecma International when referring to the organization specifically.
- Use Ecma for most references, such as "Ecma standard" or "Ecma Technical 
Committee".
- Use ECMa only for referring to a standard document such as ECMA-424 for 
CycloneDX.

### GB English
The following conventions apply to any text that is part of the Ecma standard
for PURL or VERS. 
- Use Oxford commas,
- Spelling:
   - behaviour
   - 
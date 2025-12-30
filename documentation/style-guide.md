# Package-URL style guide

This document provides guidance for writing documentation for Package-URL 
projects. It specifically applies to documentation for:
- The PURL specification from `package-url/purl-spec`,
- The VERS specification from `package-url/vers-spec` and
- The Package-URL website from `packag-url/packageurl.org`.

It is also recommended for documentation for any other project under the 
`package-url` GitHub organization.

## Package-URL Terminology
- PURL - use PURL all-caps for any general reference including cases such as PURL **type**
- VERS - use VERS all-caps for any general reference
- Package-URL

## Active voice
In general, use active voice (in which the grammatical subject of the sentence
is the person or thing performing the action) instead of passive voice (in 
which the grammatical subject of the sentence is the person or thing being 
acted upon), although there are exceptions. Make clear who's performing the 
action.

In passive voice, it's easy to neglect to indicate who or what is performing a 
particular action. In this kind of construction, it's often hard for readers 
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
- Even though you're using sentence case, don't put a period at the end of a 
title or heading.
- Use sentence case for items in a list.
- Use sentence case for all the elements in a table: contents, headings, 
labels,  and captions.

## Diction

When possible, avoid using -ing verb forms as the first word in any heading or  title. 
An -ing verb form is a present participle or gerund. These verb forms
are inconsistently translated when they're used as the first word in a title,
and they increase character count in limited spaces.

- Avoid unnecessary adjective or adverbs
- A vs the vs nothing
- GB English for Ecma standard documents

## Line length
Limit lines in a markdown file to 78 character lines to facilitate more 
accurate change tracking

## Code style (or not)
- Only use code style formatting when you are referring to a codebase file or folder
- Use bold when you are referring to a field such as PURL **type**
- Use single quotes when you are referring to a field value

## URL references
- How to refer to URLs - many options

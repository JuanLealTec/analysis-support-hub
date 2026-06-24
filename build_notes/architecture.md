# Architecture

## 1. Purpose of the Site

Provide a practical support resource that helps students identify, understand, and overcome common analysis challenges encountered while working with information, evidence, observations, findings, and conclusions.

The site is designed as a problem-oriented reference hub rather than a sequential learning resource. Students should be able to quickly locate a specific analysis challenge and access methods, frameworks, tools, and resources that may help them move forward.

## 2. Target Audience

Primary Audience

Students enrolled in PS5006 (Social Media and Information Technology) who are developing Analysis & Information projects during Weeks 06–07.

Secondary Audience

Students working on other academic projects that involve information organization, exploration, analysis, interpretation, validation, and conclusion development.

Expected User Characteristics

* Limited formal training in analysis methods.
* Working with diverse project types.
* Seeking practical guidance for specific problems.
* Using a variety of digital tools and environments.

## 3. Site Structure

The site consists of:

* Home
* Quick Problem Finder
* About
* 13 Problem Pages

Problem Pages are grouped visually within the navigation structure according to the following categories:

* Prepare Information
* Discover Patterns & Relationships
* Interpret & Validate Findings
* Develop Conclusions

Categories exist solely for navigation and organization purposes.

Categories do not have dedicated pages.

Users should be able to access any problem page directly from the persistent navigation menu or through the Quick Problem Finder.

## 4. Navigation Structure

The following structure appears in the persistent navigation menu.

Home

Quick Problem Finder

About

Prepare Information
* Incomplete Information
* Too Much Information
* Information Relevance

Discover Patterns & Relationships
* Meaningful Patterns
* Relationships
* Information Trustworthiness

Interpret & Validate Findings
* Observation Meaning
* Strongest Interpretation
* Supported Findings
* Why Is This Happening?

Develop Conclusions
* Important Findings
* Supported Conclusions
* Analysis Sufficiency

## 5. Standard Problem Page Structure

All problem pages follow the same structure.

Page Header

* Navigation Label

  Used for navigation menus and links.

* Problem Title

  Used as the page title.

Always Visible Sections

* This May Happen When
* Questions to Ask Yourself

Expandable Sections

* Possible Approaches
* Support Frameworks & Techniques
* Possible Tools
* Online Sources

## 6. Expandable Sections

Purpose

Expandable sections reduce visual clutter while allowing students to access additional guidance when needed.

Always Visible

* This May Happen When
* Questions to Ask Yourself
* Possible Approaches

Expandable
* Support Frameworks & Techniques
* Possible Tools
* Online Sources (placeholder initially)

Removed Elements

The following elements were considered and intentionally excluded:

* Problem Summary
* Related Problems
* Back to Home links
* Back to Quick Problem Finder links
* Category landing pages

## 7. Naming Conventions

Each problem uses two names.

Navigation Label

Used in menus and navigation structures.
Should be concise and easily scannable.

Problem Title

Used as the page title.
Should describe the problem completely and explicitly.

Example

Navigation Label:
Information Trustworthiness

Problem Title:
I Am Not Sure Whether My Information Is Trustworthy

## 8. Asset Management

All non-Markdown assets are stored inside:

docs/assets/

Asset Categories

docs/assets/css/

Optional custom stylesheets.

docs/assets/images/

Images, diagrams, screenshots, and visual references.

Guidelines

* Assets should be reusable across multiple pages whenever possible.
* Assets should remain independent from specific problem pages.
* Problem-specific content should be written in Markdown rather than embedded as images whenever practical.
* New asset categories should only be created when a clear need exists.

## 9. GitHub Pages Strategy

The public website will be published from the `docs/` folder inside the GitHub repository.

Repository structure:

```text
analysis_support_hub/
├── README.md
├── .gitignore
└── docs/
    ├── index.md
    ├── quick-problem-finder.md
    ├── about.md
    ├── problems/
    └── assets/
```

GitHub Pages source:

Branch: main

Folder: /docs

Only the contents of the repository folder will be uploaded to GitHub.

Development materials, source documents, and build notes remain outside the public repository:

```text
source/
build_notes/
```

The site should remain portable. If the `docs/` folder is moved to another compatible static site environment, internal links and assets should continue to work.

## 10. Future Enhancements

Potential future improvements include:

* Replace Online Sources placeholders with curated external resources.
* Add direct links to selected tools when appropriate.
* Add additional problem pages if recurring analysis challenges are identified.

## 11. Technology Stack

* MkDocs
* Material for MkDocs
* GitHub Pages
* Markdown-based content
* Minimal custom CSS
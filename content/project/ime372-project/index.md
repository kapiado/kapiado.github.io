---
title: Predicting Likelihood of Obtaining H-1B Visa
summary: |
  Term project using data cleaning and predictive modeling based on U.S. Department of Labor data. 
  Course: [IME 372: Applications of Enterprise Analytics](https://catalog.calpoly.edu/coursesaz/ime/#:~:text=IME%C2%A0372.%20Applications%20of%20Enterprise%20Analytics)
tags:
  - Data Analytics
date: '2022-06-03T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Image from [EB5 Investors](https://www.eb5investors.com/visa-information/what-is-h1b/)
  focal_point: Smart

links:
  - icon: file
    icon_pack: fas
    name: Report
    url: uploads/IME 372 Final Report.pdf
  - icon: file-powerpoint
    icon_pack: fas
    name: Presentation
    url: uploads/372 Final Presentation.pdf
  - icon: database
    icon_pack: fab
    name: Dataset
    url: https://www.dol.gov/agencies/eta/foreign-labor/performance
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Course: [IME 372: Applications of Enterprise Analytics](https://catalog.calpoly.edu/coursesaz/ime/#:~:text=IME%C2%A0372.%20Applications%20of%20Enterprise%20Analytics) *(Spring 2022)*

**Problem Description**

“More than 100,000 legal immigrants — 28 percent of the family-sponsored and
employment-based lines with quotas — waited a decade or more to apply for a green card in
2018, up from 3 percent in 1991”. Currently, the demand for the application process for a
green card has increased over the years, but the supply for green cards have been restricted by a
need for a sponsor and the H1-B visa lottery system, where they only take 20,000 out of the
65,000 capped applicants. The 20,000 selected are not guaranteed a visa as they undergo
another process that checks eligibility and visa requirements where 32% are only accepted,
which further restricts applicants in a time-consuming process. For this project, the main goal is
to analyze the likelihood of an international applicant in receiving an H1-B visa based on
descriptive features like country of birth, employer, etc.

In order to see the success rate of obtaining a visa, the objective of this project will be to create a model that will be able to predict what critically affects the application process for an H1-B visa based on different types of features.

**Data**

The data collected is from the following dataset ["H1-B FY2018"](https://www.dol.gov/agencies/eta/foreign-labor/performance#:~:text=2018-,H%2D1B%20FY2018.xlsx,-H1B%20Record%20Layout) from the U.S. Department of Labor Performance Data.
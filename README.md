<img src="https://aumni-public.s3.amazonaws.com/AumniLogoColor.png" alt="Aumni Logo" width="200" height="55">

# Aumni Backend Coding Challenge

The purpose of this coding challenge is to gauge knowledge in Ruby/Rails. In the coding challenge you will build a Ruby on Rails application that contains a very small subset of our domain at Aumni. Below you will find some helpful terminology to help you understand what these domain specific terms mean.

## Terminology

- **Fund** - A Fund is a type of [Investment Vehicle](https://www.investopedia.com/terms/i/investmentvehicle.asp) that invests the money that it has raised into various **Companies**.

- **Company** - A Company that a **Fund** invests in. Traditionally called a Portfolio Company from the perspective of the **Fund**. This is typically a start-up company that is trying to raise money.

- **Equity Financing** - Is a round of funding when stock is issued by the **Company** to **Fund**s investing in the **Company**. A **Company** can have multiple **Equity Financing** rounds in which multiple **Fund**s can invest. A **Fund** can invest in the same **Company** in multiple **Equity Financing**s.

- **Investment** - A generic term used for simplicity in the coding challenge. A **Fund** can invest in a **Company** in myriad ways, but for simplicity, we are just contemplating a simple transaction whereby a **Fund** purchases shares in a **Company** for a certain amount of dollars during an **Equity Financing**.

## Setup/Notes

1. Clone/Download this repository. This is a default Rails application with PostgreSQL used as the database and some testing gems to help you get started.

2. Make your first commit by filling out the `code-challenge-notes.md` file in the root of this directory.

3. Once you have made your first commit you will have 72 hours to make your final commit to complete the code challenge.

4. Please do **NOT** push your code challenge solution to a public repository.

5. This is a backend coding challenge. Please do **NOT** spend your time building out any kind of UI.

6. You are allowed to install and use third-party packages.

## Getting Started

1. Run: `bundle install`
2. Run: `bundle exec rails db:create`
3. Run: `bundle exec rspec`

## Base Model Columns

- **Fund**
  - name - `String`
- **Company**
  - name - `String`
  - founded - `Date`
- **Equity Financing**
  - date - `Date`
  - total_shares - `Big Int`
- **Investment**
  - shares - `Big Int`
  - amount - `Decimal (10,2)`

## Goals

- [ ] The code passes the test suite.

## Acceptance Criteria

- [ ] You have filled out the _required_ parts of the `code-challenge-notes.md` and made your first commit.
- [ ] The code is well organized.
- [ ] The code follows Ruby/Rails best practices.
- [ ] Your Git commit history is clean and meaningful.

## Submission

1. When you have your final commit complete, please zip up your entire folder.
2. We use Breezy as our ATS (Applicant Tracking System), you should have received and email with a link to Breezy to submit your zip file. If you did not get the email or can't find it, reach out to recruiting_eng@aumni.fund for a new link.

---
layout: page
title: Untitled
sidebar: true
---

In this project you'll use Ruby on Rails to build an online commerce platform to facilitate online ordering.

## Introduction

### Learning Goals

* Use TDD to drive all layers of Rails development including unit, integration, and user acceptance tests
* Design a system of models which use one-to-one, one-to-many, and many-to-many relationships
* Practice mixing HTML, CSS, and Rails templates to create an inviting and usable User Interface
* Differentiate responsibilities between components of the Rails stack
* Build a logical user-flow that moves across multiple controllers and models

### Restrictions

Project implementation may **not** use:

* Any external library for authentication except `bcrypt`
* A pre-existing, externally created CSS/HTML design/template (however, you may use [Bootstrap](http://getbootstrap.com/), [Zurb Foundation](http://foundation.zurb.com/), etc.)

### Getting Started

1. One team member creates a repository with the name of your online ordering platform
2. Add the other team members as collaborators
3. Add your project to Waffle.io 
4. Configure [Hound](https://houndci.com/) for style guide violations
5. Use [waffle.io](http://waffle.io) to write and track user stories

## Base Expectations

You will build an online ordering platform. Customers should be able to place orders and view placed order details. The site owner should be able to manage products and categories in addition to processing and completing orders. 

## Process

(insert here)

## Extensions

The extensions listed below are a non-exhaustive list of extension ideas. 

* product reviews
* product recommendations based on past orders
* product and category search
* credit card processing with Stripe or Paypal
* phone or text message order confirmation

## Evaluation Process

For the evaluation we'll work through the expectations above and look at the
following criteria:

### 1. Feature Completeness

* 4: All features are correctly implemented along with two extensions
* 3: All features defined in the assignment are correctly implemented
* 2: There are one or two features missing or incorrectly implemented
* 1: There are bugs/crashes in the features present

### 2. Views

* 4: Views show logical refactoring into layout(s), partials and helpers, with no logic present
* 3: Views make use of layout(s), partials and helpers, but some logic leaks through
* 2: Views don't make use of partials or show weak understanding of `render`
* 1: Views are poorly organized

### 3. Controllers

* 4: Controllers show significant effort to push logic down the stack
* 3: Controllers are generally well organized with three or fewer particularly ugly parts
* 2: There are four to seven ugly controller methods that should have been refactored
* 1: There are more than seven unsatisfactory controller methods

### 4. Models

* 4: Models show excellent organization, refactoring, and appropriate use of Rails features
* 3: Models show an effort to push logic down the stack, but need more internal refactoring
* 2: Models are somewhat messy and/or make poor use of Rails features
* 1: Models show weak use of Ruby and weak structure

### 5. Testing

* 4: Project has a running test suite that exercises the application at multiple levels
* 3: Project has a running test suite that tests and multiple levels but fails to cover some features
* 2: Project has sporadic use of tests and multiple levels
* 1: Project did not really attempt to use TDD

### 6. Usability

* 4: Project is highly usable and ready to deploy to customers
* 3: Project is highly usable, but needs more polish before it'd be customer-ready
* 2: Project needs significantly more attention to the User Experience, but works
* 1: Project is difficult or unpleasant to use

### 7. Workflow

* 4: Excellent use of branches, pull requests, and a project management tool.
* 3: Good use of branches, pull requests, and a project-management tool. 
* 2: Sporadic use of branches, pull requests, and/or project-management tool. 
* 1: Little use of branches, pull requests, and/or a project-management tool.
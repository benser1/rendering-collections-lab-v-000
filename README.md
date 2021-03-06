# Rendering Collections Lab

## Objectives

 1. Use the `collection` keyword with partials
 2. Pass a collection to the render method 
 3. Handle empty collections

## Overview

Let's go back to our store domain.  We had an admin portion of the site where admins could check on their orders and invoices.  We've changed it slightly  so that rather than static pages with stub's for orders we've seeded the database with actual order data.  Let's refactor the admin portion of the store to use partials and render collections.

## Instructions

First, fork and clone this lab. <em>Before anything</em>, note that when you generate models, controllers, etc, be sure to include this option, so that it skips tests (which we already have): `--no-test-framework`

We've provided a seeds file so you can have some data to play around with - run `rake db:seed` once your migrations and models are complete.

1. Refactor the `invoices.html.erb` view to render a collection of partials.
2. Refactor the `orders.html.erb` view to render a collection of partials.


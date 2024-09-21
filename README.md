<h2>Liquid Tutorial</h2>

<h3>What is Liquid?</h3>

Liquid is a template language used for creating and modifying Shopify themes. Liquid is written in Ruby but the syntax is much different than Ruby and other languages.

Important consideration: You cannot retrieve data from other websites using liquid, only from Shopify's database

To learn more about Shopify's attributes & objects, go to https://shopify.dev/docs/api/liquid

<h3>Tags</h3>

[Tags](https://shopify.dev/docs/api/liquid/tags) are the programming logic that tells templates what to do.

Tags look like this: {% ... %}

**Control Flow Tags** are the tags you can use to create conditions (if, unless, else/elsif, case/when, and/or)

**Iterations tags** are tags that you can use to repeat blocks of code using the "for/endfor" tag

**Theme Tags** are tags that generate template-specific html codes, divide arrays into multiple pages, or make themes using custom layouts/snippets

**Variable Tags** create Liquid variables. You can either use "assign", or "capture" tags

<h3>Filters</h3>

Methods that modifies the values of an object. They consist of an object tag (first word) and a pipe symbol "|". For example:

{{ product.title | upcase }}



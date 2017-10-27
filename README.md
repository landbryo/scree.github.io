# Scree LLC. Website Readme

As my description states, this is my business' site built using Jekyll and hosted with Github pages.

###Requirements
* Jekyll
* Jekyll Swiss theme

###Features
* Ajax contact form
* Blog
* Portfolio
* Disqus commenting


###Front Matter

Exclude **pages** from being added to the menu:

```ruby
exclude: true
```

Include Disqus commenting on **posts**:

```ruby
comments: true
```

###Extras

Local config added for use with [Cloud9](https://c9.io/){:target="\_blank"}

I've found that there's some confusion out there about how to target a new windows with Jekyll. Here's an example of how I do it:

```markdown
[Cloud9](https://c9.io/){:target="\_blank"}
```
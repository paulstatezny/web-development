# Schema.org

> [Schema.org](http://schema.org/) is a collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet, on web pages, in email messages, and beyond.

Mark up important information with special Schema.org attributes to help search engines more easily understand the content.

## Example

```html
<p itemscope itemtype="http://schema.org/Organization">
  <span itemprop="name">Widget Corp</span>
  <span itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
    <span itemprop="streetAddress">123 Sesame Street</span>
    <span itemprop="addressLocality">San Diego</span>,
    <span itemprop="addressRegion">CA</span>
    <span itemprop="postalCode">92125</span>
  </span>
</p>
```

## Tools

 - Google's [Structured Data Markup helper](https://www.google.com/webmasters/markup-helper/u/0/)

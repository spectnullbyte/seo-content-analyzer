# SEO CONTENT ANALYZER

This package performs checks against a given HTML text input, and it will provide a SEO score based on several criteria

Based on the package wahyunurarizky/seo-content-analyzer, this fork adds additional checks that are not part of the original package. The main changes are related to text readability which can be a direct, or indirect, factor to better SEO results.

## Usage/Examples

```javascript
//NODEJS
import SEOContentAnalyzer from "@spectnullbyte/seo-content-analyzer";
const result = SEOContentAnalyzer({
  keyword: "your-keyword-here",
  title: "your-title-here",
  descriptionMeta: "your-description-meta-here",
  content: "<h1>your content here</h1><p>cool</p>",
});

//JAVSASCRIPT
import SEOContentAnalyzer from "@spectnullbyte/seo-content-analyzer/dist/client";
const result = SEOContentAnalyzer({
  keyword: "your-keyword-here",
  title: "your-title-here",
  descriptionMeta: "your-description-meta-here",
  content: "<h1>your content here</h1><p>cool</p>",
});

// WITH LANGUAGE
const result = SEOContentAnalyzer(
  {
    keyword: "your-keyword-here",
    title: "your-title-here",
    descriptionMeta: "your-description-meta-here",
    content: "<h1>your content here</h1><p>cool</p>",
  },
  "id"
);
```

## Contributing

Contributions are always welcome!

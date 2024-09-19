<!--

author:   Raul Ortiz
email:    raul.ortiz@tudelft,nl
version:  0.0.1
language: en
narrator: UK English Female

icon:     

comment:  This document shall provide an example built with [LiaScript](https://LiaScript.github.io).

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css
link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css
link:     https://raw.githubusercontent.com/vibbits/material-liascript/master/img/org.css
link:     https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.min.css
link:     https://fonts.googleapis.com/css2?family=Saira+Condensed:wght@300&display=swap
link:     https://fonts.googleapis.com/css2?family=Open+Sans&display=swap
link:     https://raw.githubusercontent.com/vibbits/material-liascript/master/vib-styles.css

tutor:    Beer
edition:  1st 

@JSONLD
<script run-once>
  let json = @0 

  const script = document.createElement('script');
  script.type = 'application/ld+json';
  script.text = JSON.stringify(json);

  document.head.appendChild(script);

  // this is only needed to prevent and output,
  // as long as the result of a script is undefined,
  // it is not shown or rendered within LiaScript
  console.debug("added json to head")
</script>
@end

orcid:    [@0](@1)<!--class="orcid-logo-for-author-list"-->
-->

# Beer basics

```json   @JSONLD
{
  "@context": "https://schema.org/",
  "@type": "LearningResource",
  "@id": "https://elixir-europe-training.github.io/ELIXIR-TrP-TeSS/",
  "http://purl.org/dc/terms/conformsTo": {
    "@type": "CreativeWork",
    "@id": "https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE"
  },
  "description": "TeSS, how can I help you? This is our interactive hands-on course about beer",
  "keywords": "FAIR, OPEN, Teaching, beer",
  "name": "TeSS, how can I help you?",
  "license": "https://creativecommons.org/licenses/by/4.0/",
  "educationalLevel": "beginner",
  "competencyRequired": "none",
  "teaches": [
    "What is beer",
    "Main beer styles"
  ],
  "audience": "training providers",
  "inLanguage": "en-US",
  "learningResourceType": [
    "tutorial"
  ],
  "author": [
    {
      "@type": "Person",
      "name": "Raul Ortiz"
    }
  ],
  "contributor": [
    {
      "@type": "Person",
      "name": "Raul Ortiz"
    }
  ]
}
```
# Beer basics

- What is beer?
- What are the main beer types?
- What is a lager?
- What is an ale?
- What other types are possible?

# What is beer?

Beer is a fermented beverage made from the following main components:

- Water
- Malt
- Hops
- Yeast  

# What are the main beer types?

Beers can be classified mainly classified in:

- Lagers
- Ales

# What is a lager?

Main characteristics of lagers include:

- Top fermentation
- Low brewing temperature (0-2 C)
- hybrid yeast (Saccharomyces cerevisiae x S. eubayanus)

# What is an ale?

- Bottom fermentation
- High brewing temperature (20-22 C)
- (mostly) pure yeast (S. cerevisiae)

# What other types are possible?

- Spontaneous fermentation
-- Diverse microorganisms (yeast + lactic acid bacteria)

- Additional ingredients
-- Wheat, spices, fruit(s)
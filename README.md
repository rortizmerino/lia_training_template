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


<section>

Hello and welcome to our @tutor workshop! We are very happy to have you here.

This is the @edition edition of this workshop, jointly organised by your organisation and ELIXIR.

> We are using the interactive Open Educational Resource online/offline course infrastructure called LiaScript.
> It is a distributed way of creating and sharing educational content hosted on github.
> To see this document as an interactive LiaScript rendered version, click on the
> following link/badge: [LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/vibbits/training_material_template/main/README.md)

## General context

Welcome to our beer workshop! We are very happy to have you here.

This is the 1st edition of this workshop!

- The first session (18 & 19 September 2024) is dedicated to development and practice.

The **presentation** which goes alongside this material can be found [here](https://liascript.github.io/course/?https://raw.githubusercontent.com/rortizmerino/lia_training_template/main/presentation.md#1).

## Proposed Schedule

Schedule:

- What is beer?

- What are the main beer types?

- What is a lager?

- What is an ale?

- What other types are possible?

</section>

# Lesson overview

> <i class="fa fa-lock"></i> **License:** [Creative Commons Attribution share alike 4.0 International  License](https://creativecommons.org/licenses/by-sa/4.0/deed.en)
>
> <i class="fa fa-user"></i> **Target Audience:** Researchers, trainers, training providers
>
> <svg xmlns="http://www.w3.org/2000/svg" height="14" width="16" viewBox="0 0 576 512"><!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2023 Fonticons, Inc.--><path d="M384 64c0-17.7 14.3-32 32-32H544c17.7 0 32 14.3 32 32s-14.3 32-32 32H448v96c0 17.7-14.3 32-32 32H320v96c0 17.7-14.3 32-32 32H192v96c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h96V320c0-17.7 14.3-32 32-32h96V192c0-17.7 14.3-32 32-32h96V64z"/></svg> **Level:** Beginner  
>
> <i class="fa fa-arrow-left"></i> **Prerequisites**  
> To be able to follow this course, there are no prerequisites 
>
> <i class="fa fa-bookmark"></i> **Description**  This course consist of 3 slides
> 
> <i class="fa fa-arrow-right"></i> **Learning Outcomes:**  
> By the end of the course, learners will be able to:
>
> 1. Define what is beer..... [Remembering] 
>
> 2. Discuss and explain what are the main beer styles..... [Understanding] 
>
> 3. Be able to talk to beer snobs about beer..... [Applying] 
>
> 4. Compare one beer style to another ..... [Analysing] 
>
> 5. Evaluate and select beers from a wide selection ..... [Evaluating] 
>
> 6. Create and integrate a quick beer snob conversation ..... [Creating]
>
>> Check more about [Bloom's taxonomy](https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/) to categorize the levels in educational goals
>
> <i class="fa fa-hourglass"></i> **Time estimation**: 5 minutes
>
> <i class="fa fa-asterisk"></i> **Requirements:** No technical installation needed.
>
> <i class="fa fa-envelope-open-text"></i> **Supporting Materials**:
> 
> 1. [Exercises and solutions](https://github.com/vibbits/nextflow-workshop)
> 2. [Slides]()  
> 
> <i class="fa fa-life-ring"></i> **Acknowledgement**:
>
> * [ELIXIR Belgium](https://www.elixir-belgium.org/)
> * [VIB Technologies](https://www.vib.be/)
>
> <i class="fa fa-money-bill"></i> **Funding:** This project has received funding from the ELIXIR Programme 2022-2023.
>
> <i class="fa fa-anchor"></i> **PURL**:  


# Authors and Contributors

Authors

- [Raul Ortiz](@[orcid](https://orcid.org/0000-0003-4186-8941)

Contributors

- [Raul Ortiz](@[orcid](https://orcid.org/0000-0003-4186-8941))

## Citing this lesson

Please cite as:

  1. ...

# Chapters List

| Chapter | Title                                                   |
| :---- | :------------------------------------------------         |
| 1     | [What is beer?](https://liascript.github.io/course/?https://raw.githubusercontent.com/rortizmerino/lia_training_template/main/presentation.md#3)                                             |
| 2     | [What are the main beer types?](https://liascript.github.io/course/?https://raw.githubusercontent.com/rortizmerino/lia_training_template/main/presentation.md#4)                                             |
| 3     | [What is a lager?](https://liascript.github.io/course/?https://raw.githubusercontent.com/rortizmerino/lia_training_template/main/presentation.md#5)                                             |
| 4     | [What is an ale?](https://liascript.github.io/course/?https://raw.githubusercontent.com/rortizmerino/lia_training_template/main/presentation.md#6)    |
| 5     | [What other types are possible](https://liascript.github.io/course/?https://raw.githubusercontent.com/rortizmerino/lia_training_template/main/presentation.md#7)    |

# References

Here are some great tips for learning and to get inspired:

- 

# About us



--------------------------------------------

License: [![CC BY SA](img/picture003.jpg)](https://creativecommons.org/licenses/by-sa/4.0/deed.en)


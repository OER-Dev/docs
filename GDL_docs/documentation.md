# The Global Digital Library

The COVID-19 outbreak has created a situation that poses a colossal threat, now and in the future, to children and their families. A grim reality especially compounded among children already affected by poverty, disability or social exclusion. Experts predict that, given high contagion risks and the time needed to distribute a vaccine, COVID-19 is poised to be a long-term global health and welfare crisis.

The global school shutdowns and health crisis exacerbate already challenging realities for lower-income countries: with the limited or non-existent access to learning resources in underserved languages, their current education, as well as future opportunities and welfare, are significantly set back. According to the UN, [100 million more children fail basic reading skills because of COVID-19.](https://news.un.org/en/story/2021/03/1088392)

## Educational resources as digital public goods

This situation proves how critical it is to accelerate the development of open educational resources and make them available in relevant languages for children and their communities.

Too often, scarce public and international development resources are spent investing in new software code, tools, data collection, content and innovations for sector-specific solutions that are locked away behind licensing fees, with data only used by and available to specific initiatives.

With our open approach to digital development we aim to help increase collaboration in the digital development community and avoid duplicating work that has already been done. Programs can maximize their resources — and ultimately their impact — through open standards, open data, open source technologies and open innovation. By taking advantage of existing investments when you are able, you can apply finite digital development resources toward creating global goods.

Norad refers to the Digital Public Goods Alliance and the [DPGA Standard](https://digitalpublicgoods.net/standard/) as definitions of digital public goods. Both resources and future GDL platforms must be compliant with the DPGA standard.

GDL is a platform that aims to support other platforms and projects. It is a clearly defined goal that the content on GDL should be available on other relevant platforms as well as on the GDL. An open and platform agnostic design is therefore central to the project&#39;s architecture and methodology.

## GDL architecture
![](https://github.com/OER-Dev/docs/blob/main/GDL_docs/images/gdl-design.png)

The Global Digital Library is developed based on a number of open source platforms and products. The resources on the platform are licensed under Creative Commons.

The portfolio of open source products in use to develop GDL includes:

- Wordpress
- H5P
- Strapi
- React and Next.js
- MongoDb
- Google Cloud storage
- Materials and components from Material-UI are used on parts of the portfolio
- Machine learning - Apache Airflow with Cloud Composer, Postgresql and Python


## EduPix

In February 2022, EduPix.io was launched. EduPix is a spin-off project from the Global Digital Library (GDL) and contains images from a subset of the GDL books and games. In addition to GDL content, the EduPix collection contains objects provided by the Asia Foundation, Pratham Books, BookDash, African Storybooks, All Children Reading, USAID, the Norwegian Digital Learning Arena (NDLA), Holland Warchild, and Curious Learning. EduPix currently has 20.000+ images and illustrations. Our backlog of unpublished objects to vet for publication is currently at around 50.000.

Images and illustrations are made available through an open search, open APIs and a Wordpress plugin.

## API 
The openly licensed resources on the GDL are made available to the public through open APIs and through a Wordpress plugin.
[Link to API doc for the GDL](https://digitallibrary.io/api/)

## GDL structure
![](https://github.com/OER-Dev/docs/blob/main/GDL_docs/images/basic_structure.png)

### Languages

The technical architecture of the Global Digital Library starts with language. The platform currently offers 96 languages and all topics, badges and resources are directly or indirectly related to a language.

### Topics

Structure and navigation on the GDL is based on topics. Topics can be nested with subtopics. For example &quot;Library Books&quot; as parent for &quot;Level 1&quot; and &quot;Level 2&quot;. The structure and presentation for math topics are different from reading. Topics can have a specific H5P defined as &quot;Level up resource&quot; Some topic can have an Achievement/Badge related to the topic and the level up H5P. The subtopics can be contextualized in a sequence defined by the "Topic Sequence order" metadata field on topics. 

Topics are defined by the following metadata:
- "Name". Example: "Adding 1s or 10s".
- "Slug". Example: "adding-1s-or-10s".
- Desctiption 
- "Parent Category". Example: "Early Math"
- "Image"
- "Landingpage layout" (["List all", "Learn and practice"]). Different user interfaces for topic landingpage. 
- "Is featured term" (For featured topics)
- "Featured H5P ID". The H5P used will be featured on the topic landing page.
- "Topic Achievement ID". Links topic to achivment and badge.
- "Topic Sequence order". Defines the sequence of topics on the same level. 
- "Level Up URL". URL to the level-up task that triggers a badge related to a topic.
- "Add language overrides". Supports translation to different languages for topic metadata.   

### Resources

The GDL currently includes 7000 resources. Books implemented as H5P are the main category of content for all languages. Some selected languages also now include other resources and games. This includes videos and interactive content in different categories. This content portfolio is developed based on H5P and the different H5P content types. The GDL team has developed some custom content types for our platform.

### File formats
The main file format on the GDL is H5P. Some resources are available as H5P, PDF and EPUB. Others are only available as H5P. In 9 languages the resources are only available as PDF. Amharic and Sidamo are examples of languages that contain these "PDF-only" resources. 

## Badges and adaptive learning
![](https://github.com/OER-Dev/docs/blob/main/GDL_docs/images/badges.png)

Badges can be earned for selected languages. A badge is based on a specific H5P ID and related to a topic or a resource. H5Ps unique for each language. A badge is unique for each language. A badge can be related directly to a resource without being related to a topic. The GDL startet using badges in May 2022 on Early Math, expanding the use in different other topic aries over time.

### Adaptive learning path (under construction)

An adaptive learning path is undeere developement for selected topics in Early Math. A first beta will be launched in September 2022.

## Content development building blocks

![](https://github.com/OER-Dev/docs/blob/main/GDL_docs/images/layers.png)

Platform agnostic implementation and development of educational materials is key to meet the needs of underserved communities and for global scale.

Many organizations and countries already have platforms under development. Our APIs are developed to support reuse of content from the GDL on other platforms. All content and curriculum metadata on the GDL platform can be used across all major global platforms and any new projects that come into development.

The Global Digital Library content and resources are developed to be platform agnostic and usable in different contexts.

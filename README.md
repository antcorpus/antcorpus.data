ANT Corpus
=============================

This documentation details information about different available versions for download of [ANT (Arabic News Texts) Corpus](http://antcorpus.github.io).
You can find other details on the main website page.

Version details
---------------
> **Current version:** v1.0

| Version  | Articles number | Words number | Number of categories | Source
| :------: | :-------------: | :---------: | :-------------------: | :-----:|
| v1.0 **(current)** | 6 005  | > 865 500 | 9 | [JawharaFM](http://www.jawharafm.net/ar/) |

Categories
----------------

| Category (en)  | Category (ar) | JawharaFM | # of articles (v1.0) |
| :------: | :-------------: | :---------: | :---------: |
| culture | ثقافة | [x] | 70 |
| diverse | متفرقات | [x] | 194 |
| economy | اقتصاد | [x] | 174 |
| internationalNews | دولية | [x] | 561 |
| localNews | وطنية | [x] | 3090 |
| politic | سياسة | [x] | 281 |
| society | مجتمع | [x] | 673 |
| sport | رياضة | [x] | 906 |
| technology |تكنولوجيا | [x] | 56 |

Files format
----------------
ANT Corpus files are formatted in XML using similar tags to the [TREC](http://trec.nist.gov/) and [CLEF](http://www.clef-initiative.eu/) standard test collections.

This a sample of an article from JawharaFM as a news web source in the "economy" (اقتصاد) category:
```xml
<DOC>
  <DOCNO>JA-economy-32-20170125</DOCNO>
  <URL>http://www.jawharafm.net/ar/article/ارتفاع-صادرات-تونس-من-التمور-/93/76664</URL>
  <SRC>Jawhara FM</SRC>
  <CAT>economy</CAT>
  <TITLE>ارتفاع صادرات تونس من التمور</TITLE>
  <TIME>2017-01-25T14:36:00+01:00</TIME>
  <AUTHOR></AUTHOR>
  <ABSTRACT>
قال المدير الجهوي للمجمع المهني المشترك للغلال، 
 إنه تم تصدير 36 ألف طن من التمور بعائدات مالية قدرها 180 مليون دينار،
 منذ بداية الموسم وإلى غاية 24 جانفي الحالي.
  </ABSTRACT>
  <TEXT>
قال المدير الجهوي للمجمع المهني المشترك للغلال، 
 إنه تم تصدير 36 ألف طن من التمور بعائدات مالية قدرها 180 مليون دينار،
 منذ بداية الموسم وإلى غاية 24 جانفي الحالي.
وأضاف في تصريح لوكالة الأنباء الرسمية "وات" أن هذه الكميات شهدت ارتفاعا
 بالمقارنة مع نفس الفترة من الموسم المنقضي بنسبة 24 بالمائة، حيث سجّل
 تصدير 122 ألف طن. جهويا، حقق صادرات التمور التونسية حققت أرقاما قياسية
 للموسم الحالي (2016-2017) حيث تمّ إلى غاية يوم أمس الثلاثاء على مستوى جهة
 توزر تصدير 7350 طنا بقيمة مالية بلغت 38 مليون دينار، بحسب ما أفاد به
 المدير الجهوي للمجمع المهني المشترك للغلال. وأضاف أن الصادرات الجهوية
 خلال الفترة ذاتها من الموسم الماضي لم تتجاوز 6 آلاف طن بقيمة 27 مليون دينار،
 مشيرا الى أنّ الكميات المصدّرة من الجهة حققت خلال الموسم الحالي تطورا بـ20 بالمائة.
  </TEXT>
</DOC>
```
#### About tags
- `<DOCNO>` sourceAcronym `-` category `-` incremental_id `-` pubDate `</DOCNO>`
- `<AUTHOR>` and `<ABSTRACT>` may don't have content in some articles.
- `<DOCNO>`, `<URL>`, `<SRC>`, `<CAT>`, `<TITLE>`, `<TIME>`, `<TEXT>` are mandatory.


## Citation Licence
>The files of ANT Corpus are subject to the following citation license:   
>By downloading ANT Corpus, you agree to cite at least one of our papers describing ANT Corpus and/or refer the project's main page in any kind of material you produce where ANT Corpus was used to conduct search or experimentation, whether be it a research paper, dissertation, article, poster, presentation, or documentation.   
>**By using this data, you have agreed to the citation licence**.

### Publications
:page_facing_up: A. Chouigui, O. Ben Khiroun, and B. Elayeb. **ANT Corpus : An Arabic News Text Collection for Textual Classification**. In proceedings of the 14th ACS/IEEE International Conference on Computer Systems and Applications ([AICCSA 2017](http://www.aiccsa.net/AICCSA2017/)), Hammamet, Tunisia, October 30 - November 3, 2017.

## Do you want to contribute to ANT Corpus project?
> If you want to report bugs, make suggestions for new categories, website sources and etc, your first point-of-call should by the [Issues page](https://github.com/antcorpus/antcorpus.data/issues) for the repository. If you have something to add, either to a preexisting issue, or as an entirely new issue, feel free to do so.
> ### Have any ideas?
> - If you have any ideas for features you'd like implemented, please share them with us.
> ### Can you code?
> - Please refer to the [RSSCrawlerArabicCorpus](https://github.com/antcorpus/RSSCrawlerArabicCorpus) project.
> - Reviewing and commenting on code; Pointing out ways to make it better; Refactoring, rewriting, and improving. These things are welcomed and appreciated.
> ### Can you spread the word?
> If you find the project interesting for the evolution of the Arabic language, feel free to write blog posts, mention it on social media (Facebook, Twitter), etc.


----------------------
> Project webpage: <http://antcorpus.github.io>  
> Copyright (C) 2017 All Rights Reserved.  
> [RIADI-ENSI](http://www.riadi.rnu.tn/), [University of Manouba](http://www.uma.rnu.tn) & [ENISo](eniso.rnu.tn), [University of Sousse](http://www.uc.rnu.tn).  

![Version](https://img.shields.io/badge/last_version-v1.0-green.svg)
![Status](https://img.shields.io/badge/status-beta-orange.svg)
![Licence](https://img.shields.io/badge/licence-Apache_2.0-blue.svg)

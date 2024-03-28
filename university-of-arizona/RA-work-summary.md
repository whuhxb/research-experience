# Work as Research Assistant, for a DARPA project, at Clulab, University of Arizona. Aug 19th, 2022 - July 22nd, 2023:

This works are evidences of great collaboration with Prof. Mihai Surdeanu and Dr. Enrique Noriega Atala. 
The main goals were to learn scala, Odin rules system.

1. I worked on developing on an small module existing software written in scala. I learnt to implement modules in scala.

2. I worked on a tasks involving text extraction from Covid papers using a well-established software pipeline implemented by experts. 

3. I annotated datasets for this task in 2.
   
5. It was nice project all good stuff must come to an end.

## My contributions based on my findings:

Here although most of the tasks were well directed, I had some interesting findings of my own, that I contributed and I wanted to share:

  a) I found out that lot of Out-of-vocabulary words existed. This was expected since Covid introduced several new terms and words. So I proposed to extract new vocabulary by appealing to neologisms. Linguistic analysis of neologism related to coronavirus (COVID-19) https://www.sciencedirect.com/science/article/pii/S2590291121000978  Oxford as well as Cambridge maintained neologisms for Covid. The apis gave both new words and word senses related to Covid.

  b) I also identified that in Covid papers, which came from different types of document structures, based on conferences/paper formats. The context and text organized was heavily dependent on structure and headings, which was even was very different from AI/NLP conference papers. So I referred to my works from my Independent study w.r.t Historical news paper texts and Named entity extractions, which is available at: <a href="https://github.com/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/README.md#historical-newspapers-data-studied-under-digital-humanities-hipe-identifying-historical-people-places-and-other-entities">Historical newspapers data studied under Digital Humanities: HIPE (Identifying Historical People, Places and other Entities)</a>.

  c) An interesting work on Abstract Meaning Representation extended to document-level structures. 
  The idea is similar to other known approaches in Historical or OCR scanned documents: 
  label the segments and related Regions of Interests (ROI) like a sentence-span, paragraph spans to keywords/events. 
  
  - <a href="https://arxiv.org/pdf/2205.00241.pdf">A Two-Stream AMR-enhanced Model for Document-level Event Argument Extraction<a>
  - <a href="https://aclanthology.org/C18-1313.pdf">AMR Beyond the Sentence: the Multi-sentence AMR corpus</a>

  d) We did not implement c) exactly, but after guided review, we had a different strategy as per supervision from Prof. Mihai Surdeanu. My aforementioned three ideas remain unexplored.

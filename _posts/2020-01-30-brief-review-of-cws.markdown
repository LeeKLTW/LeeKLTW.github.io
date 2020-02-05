---
layout: post
comments: true
title:  "Extension of BERT"
excerpt: "Review on some papers."
date:   2020-01-25 9:00:00
mathjax: false
---
Different from the English-like languages whose words are separated naturally, 
it is necessary to segment character sequence as word sequence in many East
Asian languages, such as Chinese. Chinese word segmentation(CWS) is the task of 
splitting Chinese text (a sequence of Chinese characters) into words. It's an 
important supporting task for other NLP tasks.

Word segmentation task is usually regarded as a sequence labeling problem.
(Xue, 2003; Peng et al., 2004). The goal of sequence labeling is to 
assign labels to all elements in a sequence, which can be handled with 
supervised learning algorithms such as Maximum Entropy (ME) (Berger et al., 1996)
 and Conditional Random Fields (CRF) (Lafferty et al., 2001). Widely used 
 sequence labeling models CRF (Lafferty et al., 2001) represent the contextual 
 information of the segment boundary as a proxy to  entire segment and achieve 
 segmentation by labeling input units (e.g. words or characters) with 
 "boundary tags".




---
title: Home
---

<style>
.content-card {
  background-color: #f8f9fa;
  border-radius: 8px;
  padding: 20px 30px;
  margin-top: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
.site-banner {
  margin-bottom: 30px;
  text-align: center;
}
.banner-image {
  max-width: 100%;
  height: auto;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
}

h1, h2, h3 {
  margin-top: 1em;
  margin-bottom: 0.5em;
}
a {
  color: #0366d6;
}
.content-card ul {
  padding-left: 20px;
}
/* Custom TOC styling */
.toc {
  background: none;
  border: none;
  box-shadow: none;
  padding: 0;
}
.toc ul {
  list-style-type: none;
  padding-left: 10px;
}
.toc ul li {
  margin-bottom: 10px;
  position: relative;
  margin-left: -25px;
}
.toc ul li::before {
  content: "→";
  position: absolute;
  left: -30px; 
  color: #0366d6;
}
.toc ul li a {
  text-decoration: none;
  color: #0366d6;
}
.toc ul li a:hover {
  text-decoration: underline;
}
</style>

<br><br>

<div class="site-banner">
  <img src="{{ '/images/aaai-fidu-banner.jpg' | relative_url }}" alt="Banner" class="banner-image">
</div>

# Financial Inclusion through AI-Powered Document Understanding

An official [AAAI 2025 Lab](https://aaai.org/conference/aaai/aaai-25/tutorial-and-lab-list/#LQ04)


<br>

<div class="content-card" markdown="1">

## Workshop Overview

Financial inclusion remains a critical global challenge, with complex financial documents often serving as a significant barrier to accessing and understanding financial services. While recent advances in Large Language Models (LLMs) have shown promising capabilities in document understanding, summarization, and financial education, implementing these solutions presents various challenges. These include handling diverse data formats, designing effective prompts, ensuring accuracy in simplified responses, and adapting explanations for different user backgrounds. Additionally, there’s a growing need for solutions that can democratize financial knowledge and empower individuals to make informed financial decisions, particularly among underserved populations.

This hands-on tutorial addresses these challenges by presenting a comprehensive framework for AI-driven financial document understanding. Participants will learn to develop solutions using Retrieval-Augmented Generation (RAG) and knowledge graphs, implemented via an open-source tech stack including Phidata, Weaviate, and Llama3.1. The tutorial is structured to provide both theoretical foundations and extensive practical implementation experience. Key topics include document summarization techniques, concept simplification strategies, and methods for creating personalized explanations tailored to users’ backgrounds. Through hands-on demonstrations, participants will build use cases for financial document comprehension, develop educational tools, and gain insights into creating human-interactable platforms for deploying these methods effectively. The session combines presentations with guided coding exercises and interactive building sessions, ensuring participants gain practical experience with implementing these solutions.

This tutorial is designed for a diverse audience, including financial institutions aiming to serve underserved populations, fintech professionals developing innovative products, policymakers focused on inclusion initiatives, and AI researchers working on document understanding. By bridging the gap between complex financial documents and user comprehension, participants will gain practical skills to enhance financial inclusion through AI-powered solutions. The tutorial emphasizes accessible, open-source solutions to ensure participants can continue developing and implementing these tools after the session. Participants should have basic Python programming knowledge and bring a laptop with internet connectivity; all necessary resources and code will be provided prior to the conference. Through this comprehensive training, attendees will be equipped to contribute to the broader goal of enhancing financial inclusion through innovative AI-powered solutions.

</div>

## Contents:
<div class="content-card" markdown="1">

<div class="toc" markdown="1">
{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>
</div>


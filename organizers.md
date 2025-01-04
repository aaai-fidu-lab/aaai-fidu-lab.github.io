---
title: Organizers
nav: true
---

<style>
.organizer-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}
.lead-organizer-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
  margin-bottom: 2em;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}
.core-organizer-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-bottom: 2em;
}
/* Add styles to center the last row when there's an incomplete number of items */
.core-organizer-grid::after {
  content: "";
  grid-column: span 2;
}
.organizer-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}
.lead-organizer-grid .organizer-photo {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 15px;
}
.core-organizer-grid .organizer-photo {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 10px;
}
.organizer-info {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.section-card {
  background-color: #f8f9fa;
  border-radius: 8px;
  padding: 20px 30px;
  margin-top: 40px;
  margin-bottom: 40px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
h1 {
  margin-bottom: 0.5em;
}
h2 {
  margin-top: 1em;
  margin-bottom: 0.5em;
}
a {
  color: #0366d6;
}
@media (max-width: 768px) {
  .lead-organizer-grid {
    grid-template-columns: 1fr;
  }
  .core-organizer-grid {
    grid-template-columns: 1fr;
  }
  .core-organizer-grid::after {
    content: none;
  }
}
.section-card + h1, 
.section-card + h2 {
  margin-top: 3em;
}
</style>

# Lead Organizers

<div class="section-card">
<div class="lead-organizer-grid">
  <div class="organizer-card">
    <img src="images/JP_OfficialPic.png" alt="Jayeeta Putatunda" class="organizer-photo">
    <div class="organizer-info">
      <strong>Jayeeta Putatunda</strong>
      <span>Lead Data Scientist, Director – AI CoE at Fitch Group, specialising in NLP and Gen AI. Her focus is on custom SLMs and advanced RAG pipelines. Jayeeta is also the NYC Chapter Lead for Women in AI and was named a 2024 Generative AI Leader by AIM.</span>      
    </div>
  </div>
  
  <div class="organizer-card">
    <img src="images/anant_headshot1.png" alt="Anant Gupta" class="organizer-photo">
    <div class="organizer-info">
      <strong>Anant Gupta</strong>
      <span>Senior AI Researcher in the Bloomberg AI group. He focuses on improving financial document search and understanding products using GenAI. Anant also leads the ML/NLP Guild at Bloomberg.</span>      
    </div>
  </div>
    
</div>
</div>

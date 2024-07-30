---
title: Organizers
nav: true
---

<style>
.organizer-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 20px;
}
.lead-organizer-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
.core-organizer-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
.organizer-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}
.organizer-photo {
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
@media (max-width: 768px) {
  .lead-organizer-grid, .core-organizer-grid {
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  }
}
/* Center the last row when there's an odd number of items */
.core-organizer-grid::after {
  content: "";
  grid-column: span 1;
}
.core-organizer-grid > *:last-child:nth-child(3n - 1) {
  grid-column-start: 2;
}
/* Add spacing between sections */
h1 {
  margin-top: 2em;
  margin-bottom: 1em;
  padding-bottom: 0.5em;
  border-bottom: 1px solid #eaecef;
}
.lead-organizer-grid, .core-organizer-grid {
  margin-bottom: 2em;
}
#additional-contributors, #contact-information, #acknowledgments {
  margin-top: 2em;
}
</style>

# Lead Organizers

<div class="lead-organizer-grid">
  <div class="organizer-card">
    <img src="images/avijit-ghosh.jpg" alt="Avijit Ghosh" class="organizer-photo">
    <div class="organizer-info">
      <strong>Avijit Ghosh</strong>
      <span>Applied Policy Researcher, Hugging Face</span>
      <a href="mailto:avijit@huggingface.co">avijit@huggingface.co</a>
    </div>
  </div>
  <div class="organizer-card">
    <img src="images/irene-solaiman.jpg" alt="Irene Solaiman" class="organizer-photo">
    <div class="organizer-info">
      <strong>Irene Solaiman</strong>
      <span>Head of Global Policy, Hugging Face</span>
      <a href="mailto:irene@huggingface.co">irene@huggingface.co</a>
    </div>
  </div>
  <div class="organizer-card">
    <img src="images/zeerak-talat.jpg" alt="Zeerak Talat" class="organizer-photo">
    <div class="organizer-info">
      <strong>Zeerak Talat</strong>
      <span>Research Fellow, MBZUAI</span>
      <a href="mailto:z@zeerak.org">z@zeerak.org</a>
    </div>
  </div>
</div>

# Core Organizers

<div class="core-organizer-grid">
  <div class="organizer-card">
    <img src="images/yacine-jernite.jpg" alt="Yacine Jernite" class="organizer-photo">
    <div class="organizer-info">
      <strong>Yacine Jernite</strong>
      <span>Machine Learning and Society Lead, Hugging Face</span>
      <a href="mailto:yacine@huggingface.co">yacine@huggingface.co</a>
    </div>
  </div>
  <div class="organizer-card">
    <img src="images/usman-gohar.jpg" alt="Usman Gohar" class="organizer-photo">
    <div class="organizer-info">
      <strong>Usman Gohar</strong>
      <span>Ph.D. student, Iowa State University</span>
      <a href="mailto:ugohar@iastate.edu">ugohar@iastate.edu</a>
    </div>
  </div>
  <div class="organizer-card">
    <img src="images/jennifer-mickel.jpg" alt="Jennifer Mickel" class="organizer-photo">
    <div class="organizer-info">
      <strong>Jennifer Mickel</strong>
      <span>Researcher in AI and algorithmic fairness</span>
      <a href="mailto:jamickel@utexas.edu">jamickel@utexas.edu</a>
    </div>
  </div>
  <div class="organizer-card">
    <img src="images/lucie-aimee-kaffee.jpg" alt="Lucie-Aimée Kaffee" class="organizer-photo">
    <div class="organizer-info">
      <strong>Lucie-Aimée Kaffee</strong>
      <span>Applied Policy Researcher, Hugging Face</span>
      <a href="mailto:lucie.kaffee@huggingface.co">lucie.kaffee@huggingface.co</a>
    </div>
  </div>
  <div class="organizer-card">
    <img src="images/alberto-lusoli.jpg" alt="Alberto Lusoli" class="organizer-photo">
    <div class="organizer-info">
      <strong>Alberto Lusoli</strong>
      <span>Digital Democracies Institute Deputy Director, Simon Fraser University</span>
      <a href="mailto:alberto.lusoli@gmail.com">alberto.lusoli@gmail.com</a>
    </div>
  </div>
  <div class="organizer-card">
    <img src="images/arjun-subramonian.jpg" alt="Arjun Subramonian" class="organizer-photo">
    <div class="organizer-info">
      <strong>Arjun Subramonian</strong>
      <span>Computer Science PhD candidate, UCLA</span>
      <a href="mailto:arjunsub@cs.ucla.edu">arjunsub@cs.ucla.edu</a>
    </div>
  </div>
  <div class="organizer-card">
    <img src="images/felix-friedrich.jpg" alt="Felix Friedrich" class="organizer-photo">
    <div class="organizer-info">
      <strong>Felix Friedrich</strong>
      <span>PhD student, TU Darmstadt & hessian.AI</span>
      <a href="mailto:friedrich@cs.tu-darmstadt.de">friedrich@cs.tu-darmstadt.de</a>
    </div>
  </div>
</div>

# Additional Contributors

- William Agnew (University of Washington)
- Lama Ahmad (OpenAI)
- Dylan Baker (DAIR)
- Canyu Chen (Illinois Institute of Technology)
- Hal Daumé III (University of Maryland)
- Jesse Dodge (Allen Institute for AI)
- Isabella Duan (University of Chicago)
- Ellie Evans (Independent)
- Sara Hooker (Cohere for AI)
- Ria Kalluri (Stanford University)
- Alina Leidinger (University of Amsterdam)
- Michelle Lin (Mila Quebec AI Institute)
- Xiuzhu Lin (Independent)
- Sasha Luccioni (Hugging Face)
- Margaret Mitchell (Hugging Face)
- Jessica Newman (UC Berkeley)
- Anaelia Ovalle (University of California, Los Angeles)
- Marie-Therese Png (Oxford University)
- Levent Sagun (Independent)
- Shubham Singh (University of Illinois Chicago)
- Andrew Strait (Ada Lovelace)
- Lukas Struppek (German Center for Artificial Intelligence, TU Darmstadt)

# Contact Information

For any queries regarding the workshop or submission process, please contact the lead organizers listed above.

# Acknowledgments

We gratefully acknowledge the support of all our organizers, additional contributors, and the NeurIPS community in making this workshop possible.

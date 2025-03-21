---
title: "The Board"
---

<style>
h1 {
  margin-bottom: 1.5rem;
  text-align: center;
  font-weight: normal;
  letter-spacing: 0.3px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 0px;
    padding-bottom: 20px;
    max-width: calc(3 * 350px); /* Max 3 columns */
}

.profile-card {
  background-color: white;
  border-radius: 0;
  overflow: hidden;
  max-width: 350px;
  border: 4px solid #41C5ED;
}

.profile-card:hover {
  box-shadow: 0 3px 6px rgba(0,0,0,0.12);
}

.profile-image-container {
  padding-top: 20px; /* Add space above the image */
  text-align: center; /* Center the image horizontally */
}

.profile-image {
  width: 180px; /* Square image */
  height: 200px;
  object-fit: cover;
  display: block;
  margin: 0 auto; /* Center the image */
  /* Make BW: https://www.w3schools.com/howto/howto_css_image_bw.asp */
  -webkit-filter: grayscale(100%); /* Safari 6.0 - 9.0 */
  filter: grayscale(100%);
}

.profile-details {
  padding: 1rem;
  font-size: 0.8rem;
}

.profile-name {
  font-size: 1.3rem;
  font-weight: bold;
  margin-bottom: 0.25rem;
  margin-top: 0.6rem; /* decrease space between name and portrait */
}

.profile-title {
  color: #3b3b3b;
  font-size: 0.8rem;
  font-weight: 700;
  text-transform: uppercase;
}

/* Modified profile-mail and profile-link to use icons */
.profile-mail, .profile-link {
  display: inline-block;
  margin-right: 6px;
  margin-top: 0.5rem;
  color: #666;
  transition: color 0.2s ease;
}

.profile-mail:hover, .profile-link:hover {
  color: #41C5ED;
}

.profile-mail svg, .profile-link svg {
  width: 20px;
  height: 20px;
}

.profile-bio {
  font-size: 0.85rem;
  line-height: 1.2;
  margin-top: 0.8rem;
}

/* Responsive Fixes */
@media (max-width: 1024px) {
  .container {
    max-width: 100%;
  }
}

@media (max-width: 768px) {
  .grid {
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  }
  
  .profile-card {
    max-width: 220px;
  }
  
  .profile-image {
    width: 180px;
    height: 180px;
  }
}

@media (max-width: 480px) {
  .grid {
    grid-template-columns: 1fr;
  }
  
  .profile-card {
    max-width: 100%;
  }
  
  .profile-image {
    width: 240px;
    height: 240px;
  }
}
</style>

The board of the Computational Humanities Research community consists of:
    <div class="grid">
      <!-- profile 1 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/Melvin.jpg" alt="Portrait of Melvin">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Melvin Wevers</h2>
          <p class="profile-title">President</p>
          <a href="mailto: melvin@computational-humanities-research.org" title="Email" class="profile-mail">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <rect x="2" y="4" width="20" height="16" rx="2" ry="2"></rect>
            <path d="M22 7l-10 7L2 7"></path>
          </svg>
          </a>
           <a href="http://www.melvinwevers.nl" target="_blank" rel="noopener noreferrer" title="Website" class="profile-link">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="10"></circle>
          <line x1="2" y1="12" x2="22" y2="12"></line>
          <path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"></path>
        </svg>
          </a>
          <p class="profile-bio">Computational Historian working at the University of Amsterdam. Interested in temporality, scaling, multimodality, and the role of computational modeling in historical research.</p>
        </div>
      </div>
      <!-- profile 2 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/Folgert.jpeg" alt="Portrait of Folgert">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Folgert Karsdorp</h2>
          <p class="profile-title">Vice-President</p>
                    <a href="mailto: folgert@computational-humanities-research.org" title="Email" class="profile-mail">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <rect x="2" y="4" width="20" height="16" rx="2" ry="2"></rect>
            <path d="M22 7l-10 7L2 7"></path>
          </svg>
          </a>
           <a href="https://www.karsdorp.io/" target="_blank" rel="noopener noreferrer" title="Website" class="profile-link">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="10"></circle>
          <line x1="2" y1="12" x2="22" y2="12"></line>
          <path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"></path>
        </svg>
          </a>
          <p class="profile-bio">Senior Researcher and head of the Oral Culture research group at the Meertens Institute, Amsterdam. He likes to use computational models from fields such as Machine Learning, Cultural Evolution, and Ecology to study cultural change and to quantify cultural diversity.</p> <!-- INSERT BIO -->
        </div>
      </div>
      <!-- profile 3 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/Alie.jpeg" alt="Portrait of Alie">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Alie Lassche</h2>
          <p class="profile-title">Social Media & Event Officer</p>
           <a href="mailto: alie@computational-humanities-research.org" title="Email" class="profile-mail">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <rect x="2" y="4" width="20" height="16" rx="2" ry="2"></rect>
            <path d="M22 7l-10 7L2 7"></path>
          </svg>
          </a>
           <a href="https://pure.au.dk/portal/en/persons/a.w.lassche%40cas.au.dk" target="_blank" rel="noopener noreferrer" title="Website" class="profile-link">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="10"></circle>
          <line x1="2" y1="12" x2="22" y2="12"></line>
          <path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"></path>
        </svg>
          </a>
          <p class="profile-bio">Postdoctoral researcher at Center for Humanities Computing, Aarhus University, with a PhD in history from Leiden University. Her research interests center around the use of computational methods to study how information travels in an early-modern society.</p>
        </div>
      </div>
      <!-- profile 4 -->
      <!-- profile 2 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/Barbara.jpg" alt="Portrait of Barbara">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Barbara McGillivray</h2>
          <p class="profile-title">Diversity and Inclusion Officer</p>
            <a href="mailto: barbara@computational-humanities-research.org" title="Email" class="profile-mail">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <rect x="2" y="4" width="20" height="16" rx="2" ry="2"></rect>
            <path d="M22 7l-10 7L2 7"></path>
          </svg>
          </a>
                <a href="https://www.kcl.ac.uk/people/barbara-mcgillivray" target="_blank" rel="noopener noreferrer" title="Website" class="profile-link">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="10"></circle>
          <line x1="2" y1="12" x2="22" y2="12"></line>
          <path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"></path>
        </svg>
      </a>
          <p class="profile-bio">Lecturer in Digital Humanities and Cultural Computation at King's College London, with a PhD in computational linguistics from the University of Pisa. Her research interests focus on computational models for language change and the analysis of historical texts.</p>
        </div>
      </div>
      <!-- profile 5 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/place_holder.png" alt="Portrait of Kristoffer">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Kristoffer Nielbo</h2>
          <p class="profile-title">Journal Liaison</p>
            <a href="mailto: kristoffer@computational-humanities-research.org" title="Email" class="profile-mail">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <rect x="2" y="4" width="20" height="16" rx="2" ry="2"></rect>
            <path d="M22 7l-10 7L2 7"></path>
          </svg>
          </a>
           <a href="https://pure.au.dk/portal/da/persons/kln%40cas.au.dk" target="_blank" rel="noopener noreferrer" title="Website" class="profile-link">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="10"></circle>
          <line x1="2" y1="12" x2="22" y2="12"></line>
          <path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"></path>
        </svg>
          </a>
          <p class="profile-bio"></p> <!-- INSERT BIO -->
        </div>
      </div>
            <!-- profile -->
        <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/Lucy.jpg" alt="Portrait of Lucy">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Lucy Li </h2>
          <p class="profile-title">Proceedings Officer</p>
            <a href="mailto: lucy@computational-humanities-research.org" title="Email" class="profile-mail"> 
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <rect x="2" y="4" width="20" height="16" rx="2" ry="2"></rect>
            <path d="M22 7l-10 7L2 7"></path>
          </svg>
          </a>
           <a href="https://lucy3.github.io/" target="_blank" rel="noopener noreferrer" title="Website" class="profile-link">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="10"></circle>
          <line x1="2" y1="12" x2="22" y2="12"></line>
          <path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"></path>
        </svg>
          </a>
          <p class="profile-bio">PhD student at the University of California Berkeley's School of Information. Her research focuses on natural language processing of social and cultural data.</p> 
        </div>
      </div>
            <!-- profile 7 NB !! MAIL:TO AND WEBSITE-->
        <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/Judith.jpg" alt="Portrait of Judith">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Judith Brottrager</h2>
          <p class="profile-title">Early Career Representative</p>
            <a href="mailto: judith@computational-humanities-research.org" title="Email" class="profile-mail"> 
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <rect x="2" y="4" width="20" height="16" rx="2" ry="2"></rect>
            <path d="M22 7l-10 7L2 7"></path>
          </svg>
          </a>
           <a href="https://www.linglit.tu-darmstadt.de/institutlinglit/mitarbeitende/brottrager/index.en.jsp" target="_blank" rel="noopener noreferrer" title="Website" class="profile-link">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="10"></circle>
          <line x1="2" y1="12" x2="22" y2="12"></line>
          <path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"></path>
        </svg>
          </a>
          <p class="profile-bio">Research assistant at the Technical University of Darmstadt, completing her PhD in computational literary studies. Her research focuses on canonisation processes, quantitative literary history, and comparative computational approaches to literature.</p>
        </div>
      </div>
      </div>
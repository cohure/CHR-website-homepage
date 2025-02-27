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
  border: 2px solid #41C5ED;
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
}

.profile-name {
  font-size: 1.3rem;
  font-weight: bold;
  margin-bottom: 0.25rem;
}

.profile-title {
  font-size: 0.9rem;
  color: #555;
  font-style: italic;
}

.profile-mail {
  font-size: 0.85rem;
  color: #666;
}
.profile-bio {
  font-size: 0.9rem;
  line-height: 1.2;
}

.profile-link {
  display: inline-block;
  font-size: 0.85rem;
  color: #1a1a1a;
  text-decoration: underline;
  text-underline-offset: 2px;
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

The board of the Computational Humanities Research community consists of the following members:
    <div class="grid">
      <!-- profile 1 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/place_holder.png" alt="Portrait of Melvin">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Melvin Wevers</h2>
          <p class="profile-title">President</p>
          <p class="profile-mail">melvin@computational-humanities-research.org</p>
          <p class="profile-bio">Computational Historian working at the University of Amsterdam. Interested in temporality, scaling, multimodality, and the role of computational modeling in historical research.</p>
          <a href="http://www.melvinwevers.nl/" class="profile-link">Read More</a>
        </div>
      </div>
      <!-- profile 2 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/place_holder.png" alt="Portrait of Melvin">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Folgert Karsdorp</h2>
          <p class="profile-title">Vice-President</p>
          <p class="profile-mail">folgert@computational-humanities-research.org</p>
          <p class="profile-bio">[insert bio]</p>
          <a href="[#profile/sarah](https://www.karsdorp.io/)" class="profile-link">Read more</a>
        </div>
      </div>
      <!-- profile 3 -->
      <!-- profile 2 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/place_holder.png" alt="Portrait of Melvin">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Allie Lassche</h2>
          <p class="profile-title">Social Media & Event Office</p>
          <p class="profile-mail">alie@computational-humanities-research.org</p>
          <p class="profile-bio">Postdoctoral researcher at Center for Humanities Computing, Aarhus University, with a PhD in history from Leiden University. Her research interests center around the use of computational methods to study how information travels in (peripheral areas of) an early-modern society.</p>
          <a href="https://pure.au.dk/portal/en/persons/a.w.lassche%40cas.au.dk" class="profile-link">Read More</a>
        </div>
      </div>
      <!-- profile 4 -->
      <!-- profile 2 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/Barbara.jpg" alt="Portrait of Melvin">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Barbara McGillivray</h2>
          <p class="profile-title">Diversity and Inclusion Officer</p>
          <p class="profile-mail">barbara@computational-humanities-research.org</p>
          <p class="profile-bio">Lecturer in Digital Humanities and Cultural Computation at King's College London, with a PhD in computational linguistics from the University of Pisa. Her research interests focus on computational models for language change and the analysis of historical texts.</p>
          <a href="#profile/sarah" class="profile-link">Read More</a>
        </div>
      </div>
      <!-- profile 5 -->
      <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/place_holder.png" alt="Portrait of Melvin">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Kristoffer Nielbo</h2>
          <p class="profile-title">Journal Liaison</p>
          <p class="profile-mail">kristoffer@computational-humanities-research.org</p>
          <p class="profile-bio">[insert bio]</p>
          <a href="https://pure.au.dk/portal/da/persons/kln%40cas.au.dk" class="profile-link">Read More</a>
        </div>
      </div>
            <!-- profile 6 -->
        <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/place_holder.png" alt="Portrait of Melvin">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Vacant</h2>
          <p class="profile-title">Proceedings Officer</p>
          <p class="profile-mail">vacant@computational-humanities-research.org</p>
          <p class="profile-bio">[insert bio]</p>
        </div>
      </div>
        <!-- profile 7 -->
        <div class="profile-card">
       <div class="profile-image-container">
        <img class="profile-image" src="/images/about/board/place_holder.png" alt="Portrait of Melvin">
        </div>
        <div class="profile-details">
          <h2 class="profile-name">Vacant</h2>
          <p class="profile-title">Early Career Representative</p>
          <p class="profile-mail">vacant@computational-humanities-research.org</p>
          <p class="profile-bio">[insert bio]</p>
        </div>
      </div>
      </div>
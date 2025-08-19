---
layout: home
title: ""
---

<!-- Page-scoped styles -->
<style>
  .home-wrap {
    display: flex;
    align-items: flex-start;
    gap: 2rem;
    flex-wrap: wrap;
  }
  .left-col {
    flex: 0 0 240px;
    text-align: center;
  }
  .profile-pic {
    width: 200px;
    border-radius: 30%;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    margin-bottom: 1rem;
  }
  .icon-row {
    display: flex;
    flex-direction: column;   /* stack vertically */
    align-items: center;
    gap: 0.5rem;
    margin-top: 0.5rem;
  }
  .icon-link {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    text-decoration: none;
  }
  .icon-svg {
    width: 18px;
    height: 18px;
    fill: currentColor;
  }
  .right-col {
    flex: 1 1 320px;
  }
  .cta-list {
    list-style: none;
    padding-left: 0;
    margin-top: 1rem;
  }
  .cta-list li {
    margin: 0.3rem 0;
  }
</style>

<<<<<<< HEAD
- 📄 See **[Publications]({{ '/publications/' | relative_url }})**
- 🖼️ See **[Presentations & Posters]({{ '/presentations/' | relative_url }})**
- 💻 GitHub: [Sid-Rafilson-1617](https://github.com/Sid-Rafilson-1617)  
- ✉️ Email: <sid.rafilson@nyu.edu>
=======

<div class="home-wrap">
    <!-- Left column: Photo + contact -->
    <div class="left-col">
        <img class="profile-pic" src="{{ '/assets/profile.jpg' | relative_url }}" alt="Sid Rafilson">
        <div class="icon-row">
            <!-- GitHub -->
            <a class="icon-link" href="https://github.com/Sid-Rafilson-1617" aria-label="GitHub">
                    <svg class="icon-svg" viewBox="0 0 16 16" aria-hidden="true">
                    <path d="M8 0C3.58 0 0 3.73 0 8.33c0 3.68 2.29 6.79 5.47 7.89.4.08.55-.18.55-.4 0-.2-.01-.86-.01-1.57-2 .38-2.53-.51-2.69-.98-.09-.24-.48-.98-.82-1.18-.28-.15-.68-.52-.01-.53.63-.01 1.08.59 1.23.83.72 1.23 1.87.88 2.33.67.07-.54.28-.88.5-1.08-1.78-.21-3.64-.92-3.64-4.08 0-.9.31-1.64.83-2.22-.08-.21-.36-1.07.08-2.22 0 0 .67-.22 2.2.85.64-.18 1.32-.27 2-.27s1.36.09 2 .27c1.53-1.07 2.2-.85 2.2-.85.44 1.15.16 2.01.08 2.22.52.58.83 1.31.83 2.22 0 3.17-1.87 3.87-3.65 4.08.29.26.54.77.54 1.55 0 1.12-.01 2.02-.01 2.3 0 .22.15.49.55.4A8.33 8.33 0 0 0 16 8.33C16 3.73 12.42 0 8 0z"/>
                    </svg>
                    <span>GitHub</span>
            </a>
            <!-- Email -->
            <a class="icon-link" href="mailto:sid.rafilson@nyu.edu" aria-label="Email">
                <svg class="icon-svg" viewBox="0 0 24 24" aria-hidden="true">
                <path d="M20 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2Zm0 4.236-8 5.333L4 8.236V6l8 5.333L20 6v2.236Z"/>
                </svg>
                <span>Email</span>
            </a>
            <!-- Google Scholar -->
            <a class="icon-link" href="https://scholar.google.com/citations?hl=en&user=bXmqFWsAAAAJ" aria-label="Google Scholar">
                <svg class="icon-svg" viewBox="0 0 24 24" aria-hidden="true">
                <path d="M12 3 1 9l11 6 9-4.91V17h2V9L12 3Zm0 13L5 12.2V17c0 2.21 3.13 4 7 4s7-1.79 7-4v-4.8L12 16Z"/>
                </svg>
                <span>Google Scholar</span>
            </a>
        </div>
    </div>
    <!-- Right column: Bio text -->
    <div style="flex: 1;">
        <p>
        I am a Ph.D. student in Neural Science at New York University. I earned a Bachelor of Science in Mathematics and Neuroscience from the University of Oregon. As an undergraduate, I trained with Matt Smear, studying place coding and related neural correlates of self-motion—such as sniffing and movement speed—in the hippocampus and olfactory bulb. My work combined analyses of single-unit spiking, population rate vectors, and local field potentials to examine neural dynamics across multiple levels.
        </p>
        <p>
        My current research focuses on identifying general principles of neural activity that are phylogenetically conserved and may underlie a wide range of functions in sensation, perception, motor control, cognition, and emotion. I am particularly interested in memory and spatial navigation, and in how the computations that support navigation in the physical world may be repurposed for other cognitive tasks. I am also interested in neuronal oscillations and their role in computation, with an emphasis on the bidirectional relationship between oscillatory rhythms and single-unit spiking.
        </p>
    </div>
</div>
>>>>>>> 990086d (updates)

---
layout: homepage
project_gif: /assets/img/projects/tactile-sensing.gif
---

# About Me

I'm a Master of Science student @ [General Robotics Lab](https://generalroboticslab.com/), advised by Prof. [Boyuan Chen](https://generalroboticslab.com/director).

# Research Interests
I'm interested in task-driven hardware and algorithm design to enable robust perception and adaptive physical interaction in real-world environments.

<!-- # Research Interests

- Still learning and exploring my research interests...

# Publications

*(Coming soon.)*  
I am currently working on research projects in [your general area].  
A full list of publications will be available here in the future. -->

# Research Projects

{% assign project_image = site.static_files | where: "path", page.project_gif | first %}
<article class="research-project">
  <div class="project-media">
    {% if project_image %}
    <img src="{{ page.project_gif | relative_url }}" alt="Demonstration of geometry-robust tri-axis tactile sensing" loading="lazy" decoding="async">
    {% else %}
    <div class="project-placeholder" role="img" aria-label="Project demonstration image placeholder">
      <span>Project demo</span>
    </div>
    {% endif %}
  </div>
  <div class="project-details">
    <h2 class="project-title">Geometry-Robust Tri-Axis Tactile Sensing with Improved Signal Decoupling</h2>
    <p>Short one-sentence description of the project.</p>
    <p class="project-links"><a href="https://github.com/junyanzhou">Code</a> <span aria-hidden="true">&middot;</span> <a href="/">More details</a></p>
  </div>
</article>

<!-- # Contact

The best way to reach me is by email:  
`junyan.zhou (at) example.com` -->

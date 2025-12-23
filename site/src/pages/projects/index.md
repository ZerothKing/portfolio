---
layout: ../../layouts/BaseLayout.astro
title: Projects
---

---
layout: ../../layouts/BaseLayout.astro
title: Projects
showProjects: true
---

# Projects

Here are a few selected projects and case studies — more detail available on each page.

<div class="projects-grid">
  <div>
    <ProjectCard title="Better Timestamp Management (BTM)" summary="Firm-wide standard for timestamp serialization, improved observability with Datadog/ELK and periodic Airflow jobs." tech={["Java","Spring","Airflow"]} link="/projects/btm" />
  </div>
  <div>
    <ProjectCard title="Lung Disease Detection" summary="Transfer learning for medical image analysis using TensorFlow and Flask for prototype." tech={["Python","TensorFlow","Flask"]} link="/projects/lung-disease-detection" />
  </div>
  <div>
    <ProjectCard title="NBA Prediction" summary="Feature engineering and model comparisons using scikit-learn for predictions." tech={["Python","scikit-learn","pandas"]} link="/projects/nba-prediction" />
  </div>
</div>

<!-- Provide the project cards back to layout slot for consistent placement -->
<slot name="projects">
  <div class="projects-grid">
    <div>
      <ProjectCard title="Better Timestamp Management (BTM)" summary="Firm-wide standard for timestamp serialization, improved observability with Datadog/ELK and periodic Airflow jobs." tech={["Java","Spring","Airflow"]} link="/projects/btm" />
    </div>
    <div>
      <ProjectCard title="Lung Disease Detection" summary="Transfer learning for medical image analysis using TensorFlow and Flask for prototype." tech={["Python","TensorFlow","Flask"]} link="/projects/lung-disease-detection" />
    </div>
    <div>
      <ProjectCard title="NBA Prediction" summary="Feature engineering and model comparisons using scikit-learn for predictions." tech={["Python","scikit-learn","pandas"]} link="/projects/nba-prediction" />
    </div>
  </div>
</slot>
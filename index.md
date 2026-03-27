---
layout: default
title: Demonstration Website
---

# Octi: LMS-integrated Collaborative Writing Analytics and Feedback

Octi is an LMS-integrated platform for collaborative writing analytics and feedback that serves both as a teaching tool and a research environment in higher education. Octi can be embedded into learning management systems via the Learning Tools Interoperability (LTI) standard and currently comprises two components:

- **OctiPad**: a collaborative editor with structured workspaces for real-time group writing.
- **OctiFeedback**: a component that generates scheduled, text-based feedback on collaborative processes.

Together, these components capture fine-grained traces of writing and editing activity and derive task-aligned indicators (e.g., activation of prior knowledge, coordination and organization, and individual and group contributions) within a privacy-by-design approach.

---

## System overview

Octi is designed to support both instructional use and research instrumentation. In the research setting, learners collaborate in structured workspaces (OctiPad), while scheduled process feedback (OctiFeedback) provides textual guidance aligned with the task and collaboration goals.

<section class="figure-grid" aria-label="System overview figure">
  <figure class="figure-card figure-wide">
    <img src="{{ '/assets/images/general/fig-01-system-overview.png' | relative_url }}" alt="Placeholder figure: Octi system overview" loading="lazy" />
    <figcaption>
      <strong>Figure 1.</strong> Conceptual overview of Octi, comprising OctiPad (structured collaborative writing) and OctiFeedback (scheduled feedback), embedded via LTI.
    </figcaption>
  </figure>
</section>

---

## OctiPad during the research

The following figures illustrate the collaborative editor in use, with structured workspaces that guide group activity and support real-time coordination. The screenshots are placeholders and will be replaced with research images.

<section id="figures" class="figure-grid" aria-label="OctiPad screenshots">
  <figure class="figure-card">
    <img src="{{ '/assets/images/octipad/octipad-workspace-areas.png' | relative_url }}" alt="Image of OctiPad workspace areas" loading="lazy" />
    <figcaption>
      <strong>Figure 2.</strong> OctiPad structured workspace layout.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/octipad/student-task.png' | relative_url }}" alt="image of OctiPad students' task overview" loading="lazy" />
    <figcaption>
      <strong>Figure 3.</strong> General idea and overview of the students' task.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholder/oct-workspace-03.png' | relative_url }}" alt="Image of the component within moodle" loading="lazy" />
    <figcaption>
      <strong>Figure 4.</strong> Appearance of the component within moodle.
    </figcaption>
  </figure>
</section>

### What the reader should notice

OctiPad integrates collaboration affordances with structure. The workspaces provide a shared frame for organizing content and coordinating contributions, while the system logs fine-grained editing and writing traces for subsequent analytics.

<section class="figure-grid" aria-label="OctiPad demonstration video">
  <figure class="figure-card figure-wide">
    <video controls controlsList="nodownload" width="100%" preload="metadata" poster="{{ '/assets/video/octipad-banner.svg' | relative_url }}">
      <source src="{{ '/assets/video/octipad-explained-de.mp4' | relative_url }}" type="video/mp4">
      <track kind="subtitles" src="{{ '/assets/video/octipad-explained-subtitles-de.vtt' | relative_url }}" srclang="de" label="Deutsch" default>
      Your browser does not support the video element.
    </video>
    <figcaption>
      <strong>Video 1.</strong> Walkthrough of OctiPad's core features (currently in German).
    </figcaption>
  </figure>
</section>

<div class="callout">
  <div class="callout-title">Access</div>
  <p class="callout-text">
    OctiPad can be accessed as a standalone demonstration instance.
    The same editor can also be embedded into learning management systems via LTI.
  </p>
  <p class="callout-actions">
    <a class="btn btn-primary" href="https://octipad.s.studiumdigitale.uni-frankfurt.de/" target="_blank" rel="noopener noreferrer">Open OctiPad (Standalone)</a>
    <a class="btn btn-secondary" href="#figures">Jump to Figures</a>
  </p>
</div>

---

## OctiFeedback: scheduled, text-based process feedback

OctiFeedback provides scheduled feedback aligned with collaborative processes. Indicators can be computed from interaction traces to represent, for example, activation of prior knowledge, coordination and organization, and individual and group contributions. The examples below illustrate how feedback messages are presented.

<section class="figure-grid" aria-label="OctiFeedback screenshots">
  <figure class="figure-card">
    <img src="{{ '/assets/images/octipad/feedback-indicators.png' | relative_url }}" alt="Feedback indicators explained" loading="lazy" />
    <figcaption>
      <strong>Figure 5.</strong> An overview of the current feedback indicators for analyzis.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholders/octifeedback-02.svg' | relative_url }}" alt="Placeholder screenshot: OctiFeedback message example (2)" loading="lazy" />
    <figcaption>
      <strong>Figure 6.</strong> Example feedback message highlighting individual and group contributions (placeholder).
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholders/octifeedback-03.svg' | relative_url }}" alt="Placeholder screenshot: OctiFeedback message example (3)" loading="lazy" />
    <figcaption>
      <strong>Figure 7.</strong> Example feedback message related to activation of prior knowledge (placeholder).
    </figcaption>
  </figure>
</section>

---

## Privacy-by-design and research use

Octi is developed under a privacy-by-design approach. Data capture and indicator computation are aligned with research questions and educational goals, while supporting responsible instrumentation of collaborative learning processes.

If you would like, this section can be extended with a short description of the study context (participants, task, duration) and a brief overview of the analytics pipeline.

---

## Paper, citation, and contact

**Paper (placeholder):** [Link to the paper (to be added)](#)

**Recommended citation (placeholder):**

> Author(s). (Year). *Title of the paper*. Venue/Journal. DOI/URL.

**BibTeX (placeholder):**

```bibtex
@inproceedings{octi_placeholder_2026,
  title   = {Title of the paper (placeholder)},
  author  = {Author, First and Author, Second},
  year    = {2026},
  booktitle = {Proceedings/Venue (placeholder)},
  url     = {https://example.org/paper-link-placeholder},
}
```

**Contact (placeholder):** Name, Institution — `name.surname@institution.example`

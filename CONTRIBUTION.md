# Contribution Guidelines

Thank you for your interest in contributing to the Longhorn Neurotech Synposium! This document outlines the recommended repository structure, guidelines for adding new content, and best practices for maintaining the project. This will ensure continuity and ease-of-use for future maintainers—ensuring that the project thrives long after its original creation.

---

## Table of Contents
- [Recommended Repository Structure](#recommended-repository-structure)
- [Adding New Content](#adding-new-content)
- [Best Practices](#best-practices)
- [How to Contribute](#how-to-contribute)

---  

## Recommended Repository Structure

We suggest the following structure to keep content well-organized and easily accessible:

```plaintext
Longhorn-Neurotech-Synposium/
├── README.md               # Main overview and navigation page for students
├── CONTRIBUTION.md         # Contribution guidelines and repository structure
├── LICENSE                 # License file (CC-BY-4.0 License)
├── archives/               # Archive pages for past semesters (TODO)
│   ├── january-2025.md
│   └── winter-2024.md
├── meeting_material/      # Folders for each meeting
│   ├── 20250207_Intro_To_Neuropsychopharmacological_Computational_Cognitive_Neuroscience_Part_3/
│   │   ├── lecture_slides.pdf
│   │   ├── journal_slides.pdf
│   │   ├── links.md
│   │   └── recording.mp4    # if applicable
│   ├── 20250214_How_To_Not_Drop_The_Headset/
│   │   ├── lecture_slides.pdf
│   │   ├── journal_slides.pdf
│   │   ├── links.md
│   │   └── recording.mp4
│   └── … (other  folders)
└── misc_resources/              # Supplementary resources + github repo (extra reading, data, extra slides)
    ├── papers/
    │   ├── paper1.pdf
    │   └── paper2.pdf
    ├── data/
    │   ├── dataset1
    ├── repo/
    │   ├── image.png
    │   └── image.png
    └── slides/
    ├── extra_slide1.pdf
    └── extra_slide2.pdf
```
---

## Adding New Content

When adding new materials or updating the repository:

1. **New Events:**
   - Create a new folder inside the `meeting_material/` directory following the naming convention: `YYYYMMDD_Topic_Name/`.
   - Inside the folder, include:
     - `lecture_slides.pdf` – Slide deck for the lecture portion.
     - `journal_slides.pdf` – Slide deck for the journal club portion.
     - `links.md` – Markdown file containing links to relevant papers and material for the lecture and journal club.
     - `recording.mp4` (or another appropriate format) – Recording of the session (if available).

2. **Archives:**
   - For past semesters, add summary pages in the `archives/` folder.
   - Each archive file should include session summaries, links to slides, recordings, and paper lists.

3. **Miscellaneous Resources:**
   - Supplementary materials that are not tied to a single event can be stored in the `misc_resources/` directory.
   - Organize by type (e.g., `papers/`, `slides/`).
   - Additionally contains material for the repository itself in the `repo/` directory.

---

## Best Practices

- **Consistency:**  
  Maintain consistent naming conventions and file organization. This is crucial as the project grows and new contributors join.

- **Documentation:**  
  Update this `CONTRIBUTION.md` as needed. Ensure that any changes in the repository structure or processes are clearly documented.

- **Communication:**  
  Encourage contributors to open issues or pull requests to discuss significant changes or improvements. This collaborative approach ensures the longevity and evolution of the Synposium.

- **Accessibility:**  
  Keep the repository accessible and user-friendly. Regularly review the structure and navigation based on feedback from students and contributors.

- **Future Transition:**  
  When new leadership takes over, consider scheduling a brief transition period where outgoing maintainers can offer guidance. Document any lessons learned to assist the next team.

---

## How to Contribute

- **Fork the Repository:**  
  Create your own fork and propose changes via a pull request.

- **Open Issues:**  
  If you have suggestions or find issues, please [open an issue](https://github.com/your-repo/issues) so that we can discuss them.

- **Review Guidelines:**  
  Before submitting a pull request, please review our repository structure and contribution guidelines.

Thank you for helping keep the Longhorn Neurotech Synposium an active, thriving resource for neurotechnology enthusiasts and scholars!

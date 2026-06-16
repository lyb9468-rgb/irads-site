You are editing my Astro + Tailwind research homepage repository.

Goal:
Update the People page using the provided member photos and corrected member metadata.

Assets:
Copy the following files from this package into the repository at exactly the same paths:
- public/images/people/lee-yeonsu.webp
- public/images/people/jo-minseong.webp
- public/images/people/yu-yeong-jeong.webp
- public/images/people/kim-seojin.webp
- public/images/people/duseung-yoon.webp

Current members to display in this exact order and spelling:
1. Yeon Su Lee / 이연수 — Postdoctoral Researcher
   Image: /images/people/lee-yeonsu.webp
   Keywords: in vivo validation, immune toxicity, translational safety
   Project: Supports translational validation and immune-relevant safety studies across advanced biopharmaceutical platforms.

2. Minseong Jo / 조민성 — Ph.D. Student
   Image: /images/people/jo-minseong.webp
   Keywords: housekeeping gene algorithm, humanized mouse, immune data interpretation
   Project: Develops data-driven interpretation strategies for PBMC-humanized mouse and immune safety assessment workflows.

3. Yu Yeong Jeong / 정유영 — Ph.D. Student
   Image: /images/people/yu-yeong-jeong.webp
   Keywords: immune toxicology, human-relevant models, cell-based safety assessment
   Project: Contributes to immune-relevant cell models and platform workflows for human safety assessment.

4. Seo-Jin Kim / 김서진 — M.S. Student
   Image: /images/people/kim-seojin.webp
   Keywords: 3D tissue models, immune-tissue interaction, cell-based assays
   Project: Contributes to human-relevant 3D tissue and immune-interface model development.

5. Hyeon-Jeong Noh / 노현정 — Ph.D. Student
   Image: none yet; use initials placeholder or neutral placeholder card
   Keywords: immune toxicology, 3D/MPS platforms
   Project: Project information to be updated.

6. Duseung Yoon / 윤두승 — M.S. Student
   Image: /images/people/duseung-yoon.webp
   Keywords: cell-based safety assessment, platform development, NK92 workflow
   Project: Contributes to cell-based assay workflows and immune cell platform development.

Alumni section:
Add a compact alumni section below current members. Do not use photos for alumni. Use name, previous role, and current affiliation only.

Suggested alumni entries:
- Mi-Lang Kyun / 견미랑 — Korea Disease Control and Prevention Agency
- Ju-Kang Kim / 김주강 — Texas A&M University
- Seo Yule Jeong / 정서율 — Ministry of Food and Drug Safety
- Inhye Kim / 김인혜 — Pharmicell
- Hyewon Jung / 정혜원 — Korea Research Institute of Bioscience and Biotechnology
- Ji-In Kwon / 권지인 — Korea Disease Control and Prevention Agency

Implementation tasks:
1. Inspect the repository structure and find the current people/team data file. Likely candidates:
   - src/data/team.ts
   - src/data/people.ts
   - src/pages/team.astro
   - src/pages/people.astro

2. If navigation uses “Team”, rename public-facing navigation text to “People”. Preserve the route if changing routes would break the site.
   Preferred top navigation:
   Home | Research | People | Publications | Updates | Connect

3. Render People page sections in this order:
   A. Principal Investigator
   B. Current Members
   C. Alumni

4. Current member card design:
   - Use a clean responsive grid layout.
   - For people with photos, show square or rounded portraits using object-cover.
   - For people without photos, show initials placeholder.
   - Show English name as primary and Korean name as secondary.
   - Show position and keywords.
   - Keep project description short.

5. Alumni design:
   - Compact list or grid.
   - No photo.
   - Emphasize current affiliation.

6. Add or preserve this People page intro:
   “Science is built by people, not platforms alone. Our team brings together tissue engineering, immune biology, toxicology, imaging, and translational safety perspectives.”

7. Run:
   npm install
   npm run build

8. Fix any build errors.

9. Commit with:
   Update People page member profiles

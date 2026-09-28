# Product Requirements Document: Personal Portfolio Website

## 1. Product Summary

Build a fast, professional personal website that presents Rania's experience, selected work, and contact information to prospective employers and collaborators. The site's primary positioning is for **GTM Strategy & Operations** and **Corporate Strategy** roles in the technology sector.

The core experience should let a recruiter or hiring manager understand Rania's professional story and evaluate relevant evidence within 60 seconds. The Kaseya territory-coverage project is the lead case study because it demonstrates GTM planning, executive decision support, and operational improvement.

## 2. Problem and Opportunity

Rania's experience spans technology, strategy, analytics, entrepreneurship, and education. Without a focused portfolio, a visitor may have to piece together that story from a resume, LinkedIn, and individual project artifacts. The site should make the connection between her work and target strategy roles explicit, while providing concise, credible evidence of impact.

## 3. Goals

- Position Rania clearly for GTM Strategy & Operations and Corporate Strategy opportunities in tech.
- Let target visitors understand her background and strongest evidence within 60 seconds.
- Present at least 3 strong projects with clear roles, methods, and outcomes.
- Make it easy to review or download the resume and get in touch.
- Deliver a responsive, accessible, fast-loading site suitable for sharing from a resume and LinkedIn.

## 4. Non-Goals

- Building a full blog or publishing platform for launch.
- Publishing confidential employer, customer, employee, territory, or revenue information.
- Reproducing the resume verbatim as the only portfolio content.
- Adding a backend or database unless a launch requirement later demonstrates the need.

## 5. Target Audiences

### Primary: Recruiters and hiring managers

People evaluating candidates for technology-sector GTM Strategy & Operations or Corporate Strategy roles. They need to quickly understand role fit, scope of contribution, analytical and operating strengths, and evidence of outcomes.

### Secondary: Founders and collaborators

People looking for strategic, analytical, or operational collaborators, including within Miami's technology and education communities.

### Additional: Professors, mentors, and professional network

People who may provide referrals, feedback, or introductions and need a concise overview of Rania's work and interests.

## 6. Positioning and Messaging

### Positioning statement

Rania is an early-career strategy and operations professional focused on helping technology organizations make better go-to-market decisions through planning, analysis, and execution.

### Messaging priorities

1. Lead with GTM planning, strategy, and operations, alongside corporate strategy.
2. Show evidence through work products and outcomes rather than a broad skills list alone.
3. Connect technology experience to strategic business decisions.
4. Present the Kaseya experience with clear scope and sanitized details.
5. Support the professional story with Rania's Miami roots and long-term involvement with Code/Art.

The final headline, tagline, and bio require content approval before launch.

## 7. Key User Needs

- As a recruiter, I want to recognize Rania's target role fit immediately so I can decide whether to review her experience.
- As a hiring manager, I want to see the problem, Rania's contribution, and the result for relevant projects so I can assess how she works.
- As a collaborator, I want to understand Rania's interests and reach her without friction.
- As a visitor on mobile, I want to read the content, open the resume, and follow contact links without layout or interaction issues.

## 8. Information Architecture

The initial release should be a single, cohesive website with the following top-level sections. These may be separate pages or sections on a single page; the final implementation should favor the simplest structure that keeps navigation clear and content easy to scan.

1. **Home**: Name, approved tagline, short introduction, photo, featured project links, and primary actions to view work and contact Rania.
2. **Projects**: Selected case studies, ordered by relevance to target roles.
3. **Experience**: Roles at OutRival AI, Kaseya, Liberty City Ventures, Lab22c, and Code/Art, with 2-3 outcome-oriented bullets per role where content is available.
4. **About**: Miami roots; progression through Code/Art from student to TA, instructor, and board member; professional interests; and selected personal details.
5. **Resume**: Embedded or in-page PDF preview where practical, plus a clear download link.
6. **Contact**: Email, LinkedIn, GitHub, and optionally a simple contact form.

## 9. Functional Requirements

### P0: Required for launch

- The home view must identify Rania and communicate her focus on GTM Strategy & Operations and Corporate Strategy in tech.
- The home view must provide direct paths to the projects, resume, and contact information.
- The Projects section must contain at least 3 substantive project write-ups. Each write-up must state the context or problem, Rania's role, the work performed, relevant tools or skills, and outcomes or learnings that can be disclosed.
- A Kaseya case study must describe the territory-coverage problem, Rania's work covering all open territories, an executive dashboard consolidating information, and improved SOPs. It may report that 28 territories were covered in August, subject to confirmation of what that number measures and whether it can be attributed to the work. Do not imply revenue recovered or prevented unless a substantiated, approved figure is available.
- Kaseya content must be sanitized and approved for public release; it must not reveal confidential company, customer, employee, or territory-level details.
- Visitors must be able to access a current resume and contact Rania using at least email and LinkedIn links.
- All primary navigation, project links, resume links, and contact links must work on desktop and mobile.
- The site must provide a useful page title, meta description, and social sharing metadata.

### P1: Important after core content is complete

- Include project links, demos, screenshots, or other artifacts when they are available and approved for public sharing.
- Include a contact form if it can be implemented without adding unnecessary operational or privacy burden; otherwise use a mailto link.
- Add testimonials only when a quote, attribution, and permission to publish are secured.
- Add a skills section for Python, SQL, analytics, AI/LLM tooling, and strategy only after the list is reviewed for accuracy and role relevance.
- Add short-form writing only if Rania has launch-ready posts and a clear ongoing publishing goal.

## 10. Project Content Requirements

Each project case study should use a consistent, scannable structure:

- **Title and context**: What organization or setting the work came from, using only disclosable information.
- **Problem**: The business need or decision the work addressed.
- **Role**: What Rania owned or contributed, distinguishing individual work from team outcomes.
- **Approach**: Analysis, planning, tools, and collaboration involved.
- **Deliverable**: What was produced, such as a dashboard, analysis, operating process, or product.
- **Outcome**: Verified impact, clearly labeled timeframe and attribution; use qualitative learning when numeric impact cannot be shared.
- **Evidence**: Link, demo, screenshot, or sanitized visual when available and permitted.

### Initial candidate projects

- **Kaseya**: GTM workforce and territory coverage planning; open territory coverage; executive dashboard; SOP improvement.
- **OutRival AI**: AI voice and SMS agent systems.
- **Other work**: Select class or personal projects, including a mobile app or data analytics work, and Code/Art teaching or program contributions as relevant to the target role and available evidence.

Final project selection and ordering depend on content quality, role relevance, and disclosure approval.

## 11. Experience Content Requirements

- Include the roles at OutRival AI, Kaseya, Liberty City Ventures, Lab22c, and Code/Art when dates and descriptions are confirmed.
- Use 2-3 concise bullets per role where enough verified content exists.
- Prioritize outcomes, decisions supported, scope, and contribution over lists of routine duties.
- Do not invent dates, metrics, titles, or responsibilities. Omit or mark details for confirmation until verified.

## 12. UX and Visual Requirements

- Use a clean, professional visual system with generous whitespace, one primary accent color, and one or two type families.
- Prioritize a clear content hierarchy and fast scanning over decorative presentation.
- Make the primary actions, project summaries, and contact details easy to find.
- Provide responsive layouts for common mobile, tablet, and desktop viewports.
- Use descriptive link text, keyboard-accessible navigation, visible focus states, sufficient contrast, and meaningful alternative text for informative images.
- Avoid autoplay media and interactions that block access to essential content.

## 13. Non-Functional Requirements

- **Performance**: Aim for a load time under 3 seconds on a typical mobile connection. Optimize images, fonts, and embedded media; avoid unnecessary client-side dependencies.
- **Accessibility**: Target WCAG 2.2 AA practices for semantic structure, keyboard navigation, contrast, form labels, and text alternatives.
- **Reliability**: Site pages and core links must load without runtime errors; provide a sensible fallback if an embedded resume cannot render.
- **Privacy**: Collect no personal data by default. If a contact form is used, disclose what is collected, route submissions securely, and minimize retention.
- **Security**: Do not expose credentials, private documents, confidential employer data, or personally identifying details beyond those Rania approves for publication.
- **SEO and sharing**: Provide descriptive metadata, canonical public URLs, and social preview metadata once the domain is known.

## 14. Success Metrics

### Launch criteria

- Published at a custom domain or an approved public URL.
- At least 3 approved, substantive project case studies.
- Resume and contact links work.
- Responsive checks pass on mobile and desktop.
- Main content loads in under 3 seconds under the agreed test conditions.
- Site is linked from Rania's resume and LinkedIn.

### Product success indicators

- A target visitor can identify the role focus and find a relevant project within 60 seconds in a lightweight usability check.
- Visitors can reach the resume and contact action from the home view without confusion.
- Optional analytics, if adopted, can track project views, resume downloads, and contact-link clicks without collecting unnecessary personal data.

## 15. Scope and Delivery Plan

The original proposal targets a four-week delivery:

- **Week 1: Content**: Confirm bio, photo, resume, role details, project narratives, public metrics, and disclosure approvals.
- **Week 2: Core experience**: Finalize visual direction and build the home and projects experience.
- **Week 3: Complete and test**: Add experience, about, resume, and contact content; test responsive layouts, accessibility basics, links, and performance.
- **Week 4: Launch**: Publish, configure the custom domain, perform final checks, and add the site to the resume and LinkedIn.

Schedule is contingent on timely access to approved content, assets, and domain setup.

## 16. Dependencies and Risks

- **Content readiness**: Bio, photo, current resume, dates, project evidence, and contact links must be supplied and reviewed.
- **Confidentiality**: Kaseya and other employer work must be sanitized and approved. Public claims and visuals may require employer review.
- **Metric attribution**: The reported figure of 28 territories covered in August needs definition and attribution before it is presented as a result of Rania's work.
- **Platform choice**: The proposal considers Framer/Webflow, Next.js/Vercel, and GitHub Pages. The current repository is a GitHub Pages repository, so GitHub Pages is the working assumption for launch unless the implementation needs justify a change.
- **Custom domain**: Domain choice, purchase, DNS access, and configuration are required for the custom-domain launch criterion.
- **Resume accessibility**: A PDF embed may not be supported or usable in every browser; a direct download must remain available.

## 17. Open Decisions and Content To Confirm

These items are recorded as follow-up work, not blockers to this PRD:

- Final tagline, short bio, and exact role-title wording.
- Whether the 28 territories were previously open and what the figure represents; whether it is attributable to the project and approved for publication.
- Verified outcomes and metrics for Kaseya beyond the reported territory figure and improved SOPs.
- Specific tools and methods used to build the executive dashboard and improve SOPs.
- Final selection of at least 3 projects, plus links, screenshots, demos, and publication permissions.
- Role titles, employers, dates, and approved outcome bullets for the experience timeline.
- Photo, resume PDF, email, LinkedIn, GitHub, and custom domain.
- Single-page versus multi-page implementation; working default is the simplest structure that supports clear navigation and sharing.
- Whether launch analytics or a contact form is needed; neither is required for the initial release.

## 18. Definition of Done

The initial release is done when the site is public; clearly positions Rania for GTM Strategy & Operations and Corporate Strategy in tech; includes at least 3 approved case studies, the Kaseya work, experience, about, resume, and contact content; meets responsive, accessibility, and performance requirements; contains no unapproved confidential information; and passes the launch criteria in Section 14.
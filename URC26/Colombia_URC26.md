# Colombia - URC26

**বৈধতার নোট:** এই reportটি 2026-11-23 তারিখে public homepage, public profile এবং live browser evidence-এর ভিত্তিতে লেখা। Instagram profile ও MiliMars site publicভাবে check করা হয়েছে। একটি page-এর public interface বা mobile behavior checked না হলে সেটা অনুমান নয়; report-এ যাচাই সীমাবদ্ধতা বলা হয়েছে।

## সারসংক্ষেপ

| Team | University | public website type | যাচাই অবস্থা | সতর্কতাসহ রেটিং |
|---|---|---|---|---:|
| MiliMars | Universidad Militar Nueva Granada | Dedicated website | Desktop live page এবং competition page inspect করা গেছে | 7.8/10 |
| CERES Rover Team | Universidad de los Andes | Instagram-only public presence | Public Instagram profile inspect করা গেছে | 6.8/10 |

**Ranking:**

1. MiliMars - 7.8/10
2. CERES Rover Team - 6.8/10

---

## ১. MiliMars - Universidad Militar Nueva Granada

- ওয়েবসাইট: [https://milimars.vercel.app/](https://milimars.vercel.app/)
- চেক করা public pages:
  - [Home](https://milimars.vercel.app/)
  - [Competition](https://milimars.vercel.app/competencia.html)
- যাচাই: 2026-11-23 তারিখে live desktop page এবং competition page public text inspect করা হয়েছে

### চূড়ান্ত রেটিং: 7.8/10

| মূল্যায়ন ক্ষেত্র | স্কোর | যাচাইভিত্তিক মন্তব্য |
|---|---:|---|
| ডিজাইন ও visual identity | 8.5/10 | Dark technical theme, strong hero, orange accent এবং rover 3D visual distinctive। |
| বিষয়বস্তুর depth | 8.0/10 | Mission, five technical areas, progress, competition schedule ও sponsorship information রয়েছে। |
| information hierarchy | 8.0/10 | Hero → mission profile → rover systems → leaders → progress → competition → sponsors-এর flow clear। |
| Navigation ও usability | 8.0/10 | Desktop navigation project, rover, areas, team, progress ও competition routes clear। |
| Mobile experience | 7.0/10 | Mobile-specific screenshot/device test করা হয়নি; layout responsive হতে পারে, কিন্তু verify করা হয়নি। |
| বিশ্বাসযোগ্যতা ও trust | 7.5/10 | University affiliation, contact email, real project photos এবং sponsor needs public; verified competition result absent। |
| Technical presentation | 8.0/10 | Mechanical, software/control, electronics, arm, safety এবং science areas clear। |
| 3D/product experience | 8.5/10 | Live rover/arm/module selector এবং 3D viewer strong differentiator। |
| competition communication | 7.5/10 | URC 2026 timeline and missions are detailed, though some countdown/content values appear stale. |
| accessibility and content quality | 7.0/10 | Clear headings and labels exist; photo leader names and several placeholding values need correction. |
| verification certainty | 7.5/10 | Live public interface, project photos and competition page direct evidence; team result/acceptance status not confirmed. |

### শুধুমাত্র verified public information

#### Homepage

- Page title: **MILIMARS | Proyecto Rover**
- Team identifies as University Rover Challenge project at Universidad Militar Nueva Granada.
- Mission text explicitly says mechanical, electronics, software, communications and science are integrated.
- Homepage shows:
  - 2026 URC
  - 4 missions
  - 5 technical areas
- Technical areas:
  - Diseño mecánico
  - Software y control
  - Electrónica
  - Brazo robótico
  - Seguridad y pruebas
  - Ciencia e instrumentación
- Public website has a rover 3D viewer with Rover, Brazo and Módulo selectors.
- Leader roles are visible, including professor leader, life module, IT, arm and mobility roles.
- Progress phases are Integración del equipo, Prototipado and Validación.
- Public partner/sponsor section lists materials, electronics, sensors/comms/power and logistics needs.
- Public contact email: `contacto@milimars.com`

#### Competition page

- Page describes URC mission areas:
  - búsqueda de vida microbiana
  - manipulación de equipos
  - entrega de objetos
  - navegación autónoma
- Page gives MDRS Hanksville, Utah as the competition location.
- Public page contains a 2026 URC calendar:
  - 29 October 2025: registration
  - 3 December 2025: PDR
  - 27 February 2026: SAR
  - 24 April 2026: communications
  - 15 May 2026: science plan
  - 20 May 2026: final expenses
  - 27-30 May 2026: field competition
- Page labels these as URC 2026 milestone items, but the live countdown currently appears with expired dates.

### শক্তি

- Dedicated site is much stronger than a social-page-only presentation.
- 3D rover viewer gives the site a distinct, memorable engineering identity.
- Navigation is organized around visitor needs: Project, Rover, Areas, Team, Progress and Competition.
- Real project/test photos are used rather than generic-only stock imagery.
- Technical areas are separated clearly and explain each subsystem in plain language.
- Sponsorship asks are specific: materials, electronics, sensors, communications, power and logistics.
- Competition page explains URC science, delivery, servicing and autonomous navigation missions.
- University identity and public email are visible.

### উন্নয়নের সুযোগ

- Hero “Rover 2025” and 2026 URC messaging create a mixed timeline.
- The home page displays counters whose values are already 0 in public text, e.g. URC 0, missions 0 and areas 0. The visible 2026/4/5 model creates inconsistency.
- Some competition page counters show `0+` teams, `0+` years and `0+` countries. Those values are not meaningful and reduce credibility.
- Several leader roles use generic labels such as “Profesor líder CEO” rather than verified personal names.
- Some leader/profile and gallery images may use generic placeholders or captions that need verification.
- The countdown and site states do not clearly distinguish historical 2026 planning from current completed/updated status.
- 3D viewer may not load in every browser or slow connection; fallback text and still images are important.
- Mobile, keyboard navigation and WebGL fallback behavior were not fully tested.

### Priority improvements

1. 2025/2026 naming clean করুন: current rover model এবং competition season clearly separate করুন।
2. `0+` এবং zero counters remove বা meaningful public data দিয়ে replace করুন।
3. Countdown, expired dates ও current 2026 status update করুন; 2026 competition outcome প্রমাণিত না হলে অপ্রমাণিত claim করবেন না।
4. Verified leader names, roles and photos public করবেন।
5. 3D model loading timeout, fallback 2D image এবং no-WebGL message যোগ করুন।
6. Home/competition pages থেকে final 2026 result বা current season status-এ একটি clearly labeled link দিন।
7. Mobile 390 px ও 320 px viewport-এ 3D panel, leader carousel, timeline এবং sponsor section test করুন।

### verified competition caveat

MiliMars page 2026 mission schedule detail দিয়েছে। তবে page থেকে team-এর PDR/SAR acceptance, field placement বা final 2026 result independently verified নয়। এই report সে claimটা নয়।

### সামগ্রিক verdict

MiliMars visually ambitious এবং 3D, technical system এবং competition context-এর জন্য MiliMars একটি strong dedicated website. Highest-scoring issue হলো content freshness and evidence. Generic leader labels, `0+` counters এবং stale countdown-এর আগে 10/10-এর কাছাকাছি বলে ধরা ঠিক নয়।

---

## ২. CERES Rover Team - Universidad de los Andes

- ওয়েবসাইট type: Instagram public profile
- Public URL: [https://www.instagram.com/ceres.robotics](https://www.instagram.com/ceres.robotics)
- 2026-11-23 ফল: Public profile, identity, followers count, highlights এবং recent post thumbnails visible

### চূড়ান্ত রেটিং: 6.8/10

| মূল্যায়ন ক্ষেত্র | স্কোর | যাচাইভিত্তিক মন্তব্য |
|---|---:|---|
| ডিজাইন ও visual identity | 6.5/10 | Instagram-native identity, good profile art, but no team-specific website system. |
| বিষয়বস্তুর depth | 6.0/10 | Profile says team mission; rover/subsystem detail is mainly in posts/highlights. |
| information hierarchy | 6.5/10 | Bio → highlights → posts structure familiar, but historical information fragmented. |
| navigation ও usability | 7.0/10 | Instagram profile and tabs are easy for active social users. |
| Mobile experience | 8.0/10 | Instagram is mobile-native and profile content is accessible from mobile. |
| বিশ্বাসযোগ্যতা ও trust | 7.5/10 | Universidad de los Andes affiliation and public team profile make institutional connection clear. |
| technical disclosure | 5.5/10 | Public profile reveals URC 2025 highlight and process posts, but no consolidated specification page. |
| recruitment & contact clarity | 6.0/10 | Convocatorias highlight exists; specific current application details require visiting posts. |
| competition evidence | 7.0/10 | URC 2025 highlight exists publicly, but detailed result was not extracted as text in this pass. |
| evidence completeness | 7.0/10 | Public profile data complete enough for presence, not complete enough for a full team dossier. |

### শুধুমাত্র verified public information

- Public bio: **CERES Robotics**
- Public profile says: **Driven by passion. Guided by stars.**
- Full public identity mentions: **Ceres Robotics Team**
- University affiliation in profile: **Universidad de los Andes**
- Public profile showed 574 followers and 53 following.
- Public highlights include:
  - Proceso
  - Convocatorias
  - URC 2025
- Public profile includes recent posts/reels and university/account cross-links, but detailed captions and outcomes were not fully extracted.

### Strengths

- Clear team name and Universidad de los Andes identity.
- 574-follower public audience indicates an active institutional/social reach.
- Highlights make recruitment, process and URC 2025 communication more organized.
- Instagram-native media is suitable for showing rover builds and events.
- Public profile is easy to share and follow.

### উন্নয়নের সুযোগ

- Social profile cannot provide the structured information of a dedicated team page.
- Technical subsystems, 2026 rover status and sponsor list are not centralized.
- Bio is visually attractive but should include direct official website or email.
- Detailed URC 2025 result, 2026 registration/acceptance status and team timeline need a permanent archive.
- Recruitment highlight is visible, but current application and eligibility state need explicit post/page content.
- Public follower/count is dynamic and may change; report should not treat it as permanent ranking data.

### Priority improvements

1. A lightweight official website বা landing page তৈরি করুন।
2. Instagram bio-তে official website/email এবং recruitment link রাখুন।
3. URC 2025/2026 highlights-এর শেষে verified result/report and document link দিন।
4. One permanent Team/Subsystem page: Mechanical, Electrical, Software, Science and Rover.
5. Sponsor tier এবং contact route website/Link-in-bio-তে centralized করুন।

### verified limitations

এই pass-এর public profile page থেকে full post captions or URC 2025 result text confirmed হয়নি। তাই `URC 2025 highlight exists` এটাই লেখা হয়েছে, team result claim করা হয়নি।

### সামগ্রিক verdict

CERES public identity clear এবং social engagement presence আছে। তবে complete team dossier হিসেবে website absent. Dedicated page না থাকায় technical credibility and long-term public trust fragmented হয়ে Instagram-এর উপর নির্ভর করছে।

---

## Colombia team list

- [CERES Rover Team - Universidad de los Andes](https://www.instagram.com/ceres.robotics?igsh=MXNlMm45Z2JjM2ozbQ==)
- [MiliMars - Universidad Militar Nueva Granada](https://milimars.vercel.app/)

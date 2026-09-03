# 💼 Commercial Experience

---

## 🏢 ( ### company name ### (nda) ) 
**Frontend Developer (React / TypeScript)**

### 📌 Project
Cash & Valuables Vault Operations System
A large-scale SPA for *** combining four workspaces in one application:

**Operator** — storeroom / cash desk / cabin: shifts, processes, search, tables, visual floor plan

**NSI** — currencies, denominations, accounts, documents, operation types, org structure, equipment

**Admin** — users, roles, permissions, audit, system monitoring

**Reports** — parameterized document generation (PDF / Office)

### 🚀 Key Contributions
- Built full Feature-Sliced slices for documents, operation types/groups, chart of accounts, currencies, denominations, org units, clients, and machines

- Implemented Zod API contracts, React Query hooks, and React Hook Form CRUD with table filters and pagination

- Wired cascading selects and domain-specific validation across large reference catalogs

- Developed dynamic report forms driven by backend parameter definitions

- Implemented cascaded dependsOn validation (disable / filter dependent selects)

- Added export format selection and query-parameter normalization for PDF / DOCX / XLSX generation

- Built user, role, and permission management with fine-grained RBAC

- Implemented route-level permission guards on TanStack Router

- Integrated cookie-based session and permission checks across workplaces

- Built the Kubernetes pods workspace: CPU/RAM cards, tables, charts, and polling

- Formatted live infrastructure metrics and time-range filters for operators

- Delivered storeroom table flows and tab/breadcrumb navigation between warehouse contexts

- Extended the shared Mantine UI kit (base + controlled form wrappers, tables, layout)

- Implemented URL-driven filters (nuqs) and modal close via browser Back

### 🎯 Focus Areas
Enterprise SPA · Master data at scale · RBAC · Ops dashboards
Product logic where a UI mistake can affect cash accounting and who may run vault operations

### 🛠 Tech Stack
https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white
https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white
https://img.shields.io/badge/Feature_Sliced-0A1E3F?style=for-the-badge&logo=feature-sliced&logoColor=white
https://img.shields.io/badge/Mantine-339AF0?style=for-the-badge&logo=mantine&logoColor=white
https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white
https://img.shields.io/badge/TanStack_Router-FFB443?style=for-the-badge&logo=reactrouter&logoColor=white
https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white
https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white
https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white
https://img.shields.io/badge/nuqs-6C47FF?style=for-the-badge&logo=nuqs&logoColor=white
https://img.shields.io/badge/Zustand-764ABC?style=for-the-badge&logo=zustand&logoColor=white
https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge&logo=recharts&logoColor=white
https://img.shields.io/badge/Konva-0D83CD?style=for-the-badge&logo=konva&logoColor=white
https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white
https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white

---

---

## 🏢 ( ### company name ### (nda) ) 
**Frontend Developer (Ext JS / OpenLayers)**  

---

### 📌 Project
**Technical Inventory CAD System**  
A desktop-like SPA for technical inventory of real estate, enabling interactive drafting of floor plans and layout plans directly in the browser.

---

### 🚀 Key Contributions

**CAD Canvas & Geometry**  
- Built a full-featured CAD editor using OpenLayers and ol-ext
- Implemented primitives: lines, arcs, rectangles, circles, polygons, walls, openings, stairs, columns, and equipment
- Integrated snapping to vertices, edges, and orthogonals
- Applied computational geometry (JSTS) for intersections, union/difference, and contour validation
- Automated room detection by inner point, with cut/split/unite operations

**Editing Tools**  
- Developed vertex editing, proportional and non-proportional rotate/scale
- Implemented multi-select, labels, and leaders
- Added undo functionality and keyboard-driven draw/edit workflows

**Rooms & Explication**  
- Built room tree with area calculations and purpose classification
- Integrated import of room lists from external property registry

**Layout & Print**  
- Created paper sheet management (format, scale, orientation)
- Implemented raster georeferencing using Helmert transformation
- Generated multi-page PDF exports with jsPDF

**Data Exchange**  
- Integrated DWG parsing via backend
- Enabled geometry import/export between plans and external registry

---

### 🎯 Focus Areas

> Web CAD · Computational Geometry · GIS · Desktop-like SPA  
> Precision mapping where accuracy matters for property records

---

### 🛠 Tech Stack

![Ext JS](https://img.shields.io/badge/Ext_JS-6.5-8B4513?style=for-the-badge&logo=sencha&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![OpenLayers](https://img.shields.io/badge/OpenLayers_4-1F6B75?style=for-the-badge&logo=openlayers&logoColor=white)
![JSTS](https://img.shields.io/badge/JSTS-00A86B?style=for-the-badge&logo=location-based&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)

---

---

## 🏢 ( ### company name ### (nda) ) 
**Frontend Developer (React / TypeScript)**  

---

### 📌 Project
**Industrial Fleet Dispatch & Teleoperation System**  
A large-scale SPA for open-pit mining operations, supporting three workspaces in one application:
- **Admin** — users, roles, pit sites, reference data, machines, audit
- **Dispatcher** — operational map, zones, routes, diagnostics, trip statistics
- **Operator** — live map, telemetry, onboard commands (driver / teleoperator / autonomy)

---

### 🚀 Key Contributions

**GIS & Mapping**  
- Built interactive maps with Leaflet, Geoman, and Turf.js
- Implemented pit sites, zones/sub-zones, geometry validation, and machine/route layers

**Routing & Trajectories**  
- Developed base and calculated trajectories with ready assignments
- Integrated route sending to vehicles

**Real-Time Data**  
- Configured WebSocket connections for machine positions, states, obstacles, and notifications
- Implemented reliable reconnect logic

**Operator Console**  
- Built emergency stop, engine control, and remote control interfaces
- Integrated lidar/radar recording and local steering client connection

**Diagnostics**  
- Created dump-truck and loader panels
- Implemented maintenance flows, trip monitoring, and road-quality analytics

**Admin Panel**  
- Developed user/role management with fine-grained RBAC
- Built NSI directories (machine types/models/series, components)
- Implemented settings and audit logging

---

### 🎯 Focus Areas

> Complex interfaces · Maps · Realtime · Industrial IoT  
> Product logic where a UI mistake can affect how equipment operates

---

### 🛠 Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![RTK Query](https://img.shields.io/badge/RTK_Query-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000?style=for-the-badge&logo=three.js&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

---

## 🏢 ( ### company name ### (nda) ) 
**Frontend Developer (Next.js)**  

---

### 📌 Projects
Marketing websites, landing pages, and e-learning platforms.

---

### 🚀 Key Contributions

- **Pixel-perfect layouts** — built responsive, cross-browser landing pages and storefronts from Figma/PSD designs
- **Business logic & API** — implemented frontend logic with seamless backend API integration
- **Payment integration** — processed transactions and generated custom email templates for customers
- **Interactive graphics** — worked with SVG for scalable, interactive visual elements
- **Complex animations** — created scripted animations up to 15–20 seconds using CSS and JavaScript

---

### 🛠 Tech Stack

![Next.js](https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)

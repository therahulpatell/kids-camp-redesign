# Kids Camp — Where Curiosity Comes to Play 🌟

Welcome to the official repository of the **Kids Camp Play School** website redesign! 

This is a modern, responsive, and highly interactive landing page designed for Kids Camp Play School, Dombivli. Established in 2000, Kids Camp has spent over 25 years nurturing young minds through a child-first, play-based learning philosophy.

## 🚀 Live Demo
The page is deployed on GitHub Pages and can be accessed at:
👉 **[https://therahulpatell.github.io/kids-camp-redesign/](https://therahulpatell.github.io/kids-camp-redesign/)**

---

## 🎨 Design & Aesthetic
The website redesign is crafted to feel premium, playful, and alive:
- **Curated Color Palette**: Custom HSL color design featuring warm backgrounds (`#FFFDF5`), child-friendly primary purple (`#8B5CF6`), playful pink (`#F472B6`), sunflower yellow (`#FBBF24`), and mint green (`#34D399`).
- **Typography**: Sleek, modern font pairings using **Outfit** for headings and **Plus Jakarta Sans** for body copy (loaded dynamically via Google Fonts).
- **Interactive Micro-animations**:
  - Whimsical floating blobs and rotating icons.
  - Interactive confetti trigger upon initial load.
  - Smooth-scrolling navigation.
  - CSS-based scroll reveal effects.
  - Beautiful hover states and image zoom effects.

---

## ✨ Features
- **Hero Area**: Beautiful, eye-catching introduction with dynamic badge, title, call-to-actions, and an interactive floating image collage.
- **Why Kids Camp**: Interactive stats counting over 2,000 happy learners and a grid of core philosophies (Trust, Child-First, Play-Based, Safe space).
- **Founder's Corner**: Introducing **Mrs. Namrata Anil Patel** (ECCE, Child Psychology, Certified Parenting Coach, NLP practitioner) and her 25-year vision.
- **Learning Adventures (Programs)**: Explore key offerings spanning Play Group, Nursery, Junior KG, Senior KG, Day Care, and After-School Activity Club.
- **A Day at Kids Camp**: A beautiful visual timeline from 8:00 AM "Morning Welcome" to 1:00 PM "Goodbye Smiles".
- **Magic Spaces**: High-quality Unsplash image galleries highlighting Classrooms, Adventure Play areas, Creative rooms, and Safety systems.
- **Parent Love**: Multi-column testimonial cards showcasing reviews and recommendations from happy parents.
- **Admissions Form**: A clean, modern form allowing parents to easily request a school tour or inquire about admissions.
- **Contact & Map**: Location information, school hours, contact cards, social links, and an embedded Google Map.

---

## 🛠️ Technology Stack
- **Structure**: Semantic HTML5.
- **Styling**: Vanilla CSS3 (Custom Properties / CSS Variables, Flexbox, CSS Grid, custom `@keyframes` animations).
- **Interactions**: Vanilla JavaScript (Scroll observer for reveal animations, mobile menu toggle, interactive confetti).
- **Assets**: Dynamic images loaded from Unsplash.

---

## 💻 Local Setup & Development
Since the project is built entirely on vanilla web technologies, there is no build step or package installation required!

### Method 1: Open Directly
Simply double-click the `index.html` file in your file explorer to open it in any modern web browser.

### Method 2: Local Server (Recommended)
Running a local server ensures all assets and paths resolve perfectly.
1. Make sure you have [Node.js](https://nodejs.org/) installed.
2. In your terminal, navigate to this project folder:
   ```bash
   cd "Kids Camp Redesign"
   ```
3. Run a simple server using `npx`:
   ```bash
   npx serve .
   ```
4. Open the local address (usually `http://localhost:3000`) in your browser.

---

## 🌐 Deployment to GitHub Pages
To deploy this project to your GitHub Pages:

1. **Commit and Push to GitHub**:
   Ensure all changes are added, committed, and pushed to your remote repository:
   ```bash
   # Rename the default branch to main (if not already done)
   git branch -M main
   
   # Add files to staging
   git add .
   
   # Commit changes
   git commit -m "Initial commit: website redesign with index.html and README"
   
   # Push to remote main branch
   git push -u origin main
   ```

2. **Configure GitHub Pages Settings**:
   - Go to your repository on GitHub: `https://github.com/therahulpatell/kids-camp-redesign`
   - Click on the **Settings** tab.
   - On the left sidebar, click on **Pages** (under the "Code and automation" section).
   - Under **Build and deployment**:
     - **Source**: Select `Deploy from a branch`.
     - **Branch**: Choose `main` (or the branch you pushed to) and set the folder to `/ (root)`.
   - Click **Save**.

3. **Enjoy your site!**:
   GitHub will trigger an automated deployment action. After 1-2 minutes, your site will be live at the URL shown at the top of the Pages settings page!

#  Personal Portfolio Website

##  Project Title & Description

**Project Title:** Personal Portfolio Website

**Description:**
A clean, responsive personal portfolio designed to showcase my skills, projects, and professional story as a Data Scientist and Machine Learning Engineer. The site is built to attract potential employers, collaborators, and students by presenting work samples, technical capabilities, and contact information in a polished, accessible format.

**Who it's for:**
- Employers and hiring managers
- Technical collaborators and open-source contributors
- Students and mentees seeking learning resources

**Why it matters:**
- Acts as a professional brand hub
- Demonstrates practical experience and technical depth
- Provides an accessible point of contact and project portfolio

---

##  Tech Stack

**Frontend**
- React
- Tailwind CSS
- Framer Motion (optional, for subtle animations)
- shadcn/ui (component primitives)
- lucide-react (icons)

**Backend (optional)**
- FastAPI (only if you need dynamic content / contact forms / server-side data)

**Build & Deployment**
- Git / GitHub
- Vercel or Netlify for hosting

**Testing & Tooling**
- Jest + React Testing Library (unit/integration)
- ESLint + Prettier (linting & formatting)
- TypeScript (optional, recommended)

---

## 🧩 Project Structure (suggested)
```

/
├─ public/
├─ src/
│  ├─ components/
│  ├─ pages/
│  ├─ styles/
│  └─ utils/
├─ tests/
├─ package.json
└─ README.md

````

---

## 🧠 AI Integration Strategy

This project uses AI tools to accelerate development while preserving code quality and context-awareness.

### 1. Code generation
- **Scaffold features**: Use an AI IDE assistant (e.g., Copilot, Cursor, or ChatGPT-based agent) to scaffold page layouts, common components (Navbar, Footer, ProjectCard), and CRUD flows for any dynamic data.
- **CLI agents**: Use prompts with your CLI agent to bootstrap new pages or components using templates (component name, props, and example data). Example prompt: `Create a responsive ProjectCard component in React + Tailwind that accepts title, description, tags, image, and link.`
- **Boilerplate**: Generate boilerplate for routing, meta tags (SEO), and accessible forms.

### 2. Testing
- **Unit tests**: Use AI to generate test cases for components (Jest + React Testing Library). Example prompt: `Write unit tests for ProjectCard to verify rendering of title, tags, and link behavior.`
- **Integration tests**: Generate integration tests for flows like contact form submission or navigation between pages.
- **Test prompts**: Keep a canonical set of test prompts so the AI can regenerate/extend tests as components evolve.

### 3. Documentation
- **Docstrings & inline comments**: Use AI to generate or expand docstrings for complex utilities and components. Example prompt: `Add concise docstrings to this util function explaining inputs, outputs, and edge cases.`
- **README & changelog**: Use AI to draft and update the README when features change. Keep a changelog skeleton where the AI appends release notes from commit diffs.
- **Commit messages**: Generate descriptive commit messages from staged changes via AI to keep history readable.

### 4. Context-aware techniques
- **Provide file trees / diffs**: When asking the AI to modify code, include the file tree or diffs so it produces accurate, context-aware changes.
- **API specs**: Feed the AI your API OpenAPI / Swagger spec when it needs to write fetch hooks or data models.
- **Prompt engineering**: Maintain `llm.txt` or rules files with common prompts, component patterns, and conventions for consistent AI outputs across the project.
- **Use limited context windows**: When refactoring large codebases, provide only the minimal relevant files and diffs to avoid hallucinations.

---

## ⚙️ Example AI Prompts (copy-ready)

**Scaffold a page:**
```bash
"Create a responsive `Projects` page in React using Tailwind. It should display a list of ProjectCard components with title, short description (max 18 words), tags, and a link. Include accessible headings and keyboard navigation."
````

**Write tests:**

```bash
"Write Jest + React Testing Library tests for ProjectCard to assert it renders title, tags, and that the link opens in a new tab with the correct href."
```

**Add docstrings:**

```bash
"Add a concise docstring for this function: `calculateEngagement(metrics)` describing parameters, return value, and an example usage."
```

---

## 🚀 Getting Started (dev)

1. Clone the repo

```bash
git clone <repo-url>
cd personal-portfolio
```

2. Install dependencies

```bash
pnpm install # or npm install / yarn install
```

3. Run dev server

```bash
pnpm dev # or npm run dev
```

---

## 🧪 Testing

* Run unit tests:

```bash
pnpm test
```

* Run lint and format checks:

```bash
pnpm lint
pnpm format
```

---

## 💡 Best Practices & Notes

* Keep components small and well-documented.
* Use AI-generated code as a starting point — always review for business logic correctness and edge cases.
* Maintain an `llm.txt` or rules file with preferred prompt templates and project conventions.
* For production-sensitive code, require code review and CI checks before merging.

---

## 📄 License

Licence by MIT.





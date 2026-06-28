# NoteWise AI 🧠🚀

NoteWise AI is an intelligent, full-stack personal knowledge base and modular study platform designed to streamline note-taking, information organization, and active recall. By leveraging automated data extraction features, NoteWise AI transforms traditional static notes into dynamic, categorized learning modules.

---

## 🚀 Key Features

*   **Dynamic Analytics Dashboard:** Instantly monitor your study habits and knowledge base capacity with high-level statistics tracking total Notes, Starred entries, generated Flashcards, and custom Tags.
*   **Automated Flashcard Generation:** Accelerates active recall preparation by systematically parsing note content to generate contextual, interactive flashcard decks.
*   **Intelligent Tagging Engine:** Includes an automated "Auto-tag" helper tool that evaluates note themes and dynamically suggests relevant organizational tags.
*   **Modular Study Decks:** Group notes, summaries, and revision decks together under distinct academic blocks to structure exam preparation.
*   **Rich Text Workspace:** A clean, optimized interface for creating, editing, and managing persistent study documentation.

---

## 🛠️ Architecture & Tech Stack

### Frontend Architecture
*   **Framework:** React with TypeScript (structured type safety for scalable application components).
*   **Styling Engine:** Tailwind CSS for a fully responsive, utility-first layout optimized for split-screen coding and web views.
*   **UI Components:** Modular, accessible components including dynamic accordion lists, modal dialog sheets, status badges, and custom sidebars.

### Backend & Environment
*   **Runtime Environment:** Node.js
*   **Server Framework:** Express
*   **Deployment Configuration:** Designed for native cloud sandboxing via the Replit Dev Environment.

---

## 📦 File & Directory Overview

```text
├── src/
│   ├── components/       # Reusable UI components (Accordion, Dialog, Badges, Buttons)
│   ├── context/          # Application state management hooks
│   ├── App.tsx           # Primary application entry point and root layout
│   └── main.tsx          # Client-side DOM injection layer
├── package.json          # Dependency configuration and build scripts
├── tsconfig.json         # TypeScript compiler configurations
└── tailwind.config.js    # Utility utility-class style mapping layout

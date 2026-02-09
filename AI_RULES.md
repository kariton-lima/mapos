# AI Development Rules and Tech Stack

This document outlines the core technologies and development conventions for this application. All AI-driven development must adhere to these rules to maintain consistency and quality.

## Tech Stack Overview

*   **Framework:** React
*   **Language:** TypeScript
*   **Routing:** React Router (All routes are defined in \`src/App.tsx\`)
*   **Styling:** Tailwind CSS (Extensive use of utility classes is mandatory)
*   **UI Components:** shadcn/ui (Prebuilt components are available and preferred)
*   **Icons:** \`lucide-react\`
*   **Component Structure:** Pages reside in \`src/pages/\` and reusable components in \`src/components/\`
*   **Source Code:** All application source code is located within the \`src/\` directory.

## Library Usage Rules

| Purpose | Library/Tool | Rule |
| :--- | :--- | :--- |
| **UI Components** | shadcn/ui & Radix UI | Use for all standard UI elements (Buttons, Forms, Dialogs, etc.). **Do not edit** the source files of these prebuilt components; create new components for customization. |
| **Styling** | Tailwind CSS | Must be used for all styling. Prioritize utility classes over custom CSS. |
| **Routing** | React Router | Use for all client-side navigation. Routes must be centralized in \`src/App.tsx\`. |
| **Icons** | \`lucide-react\` | Use for all icons in the application. |
| **Source Code** | TypeScript/React | All new code must be written in TypeScript and follow React best practices (e.g., small, focused components). |

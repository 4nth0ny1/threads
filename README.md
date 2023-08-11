# Threads Tutorial Readme

$ npx create-next-app@latest ./
√ Would you like to use TypeScript? ... Yes
√ Would you like to use ESLint? ... No
√ Would you like to use Tailwind CSS? ... Yes
√ Would you like to use `src/` directory? ... No
√ Would you like to use App Router? (recommended) ... Yes
√ Would you like to customize the default import alias? ... No
Creating a new Next.js app in C:\Users\Anthony\Desktop\code\mern\threads.

## Dependencies

npm install @clerk/nextjs @uploadthing/react mongoose svix uploadthing

## Shadcn Installation

$ npx shadcn-ui@latest init
√ Would you like to use TypeScript (recommended)? ... yes
√ Which style would you like to use? » Default
√ Which color would you like to use as base color? » Slate
√ Where is your global CSS file? ... app/globals.css
√ Would you like to use CSS variables for colors? ... no
√ Where is your tailwind.config.js located? ... tailwind.config.js
√ Configure the import alias for components: ... @/components
√ Configure the import alias for utils: ... @/lib/utils
√ Are you using React Server Components? ... yes
√ Write configuration to components.json. Proceed? ... yes

npx shadcn-ui@latest add form

The installation created a duplicate components file. I moved all the components from the folder I created into the one shadcn created and it functions normally now.

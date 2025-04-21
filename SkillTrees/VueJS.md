## 🔮 Vue.js Skill Tree (2025 – Composition API, Ecosystem, Full Stack)

---

### 🧩 1. **Core Vue (Composition + Options API)**

| Area            | Dettagli                                                                    |
| --------------- | --------------------------------------------------------------------------- |
| Vue Basics      | ✅✅✅ (template, interpolation, directives come `v-if`, `v-for`, `v-bind`) |
| Reattività base | ✅✅✅ (`ref()`, `reactive()`, `computed()`, `watch()`)                     |
| Componenti      | ✅✅✅ (props, emits, slot, `defineComponent`)                              |
| Lifecycle Hooks | ✅✅✅ (`onMounted`, `onUpdated`, `onUnmounted`)                            |
| Options API     | ✅✅ (legacy: `data`, `methods`, `watch`, `computed`)                       |
| Composition API | ✅✅✅ (`setup()`, `provide/inject`, composables riusabili)                 |

---

### 🧠 2. **Vue Router (v4)**

| Area                      | Dettagli                                       |
| ------------------------- | ---------------------------------------------- |
| Routing Dinamico          | ✅✅✅ (`/users/:id`, `useRoute`, `useRouter`) |
| Navigazione Programmatica | ✅✅ (router.push, router.replace)             |
| Nested Routes             | ✅✅✅ (`<router-view>`, layout multipli)      |
| Lazy Loading              | ✅✅ (dynamic `import()` in route meta)        |
| Navigation Guards         | ✅✅✅ (`beforeEnter`, `beforeEach`, auth)     |

---

### 🧰 3. **State Management (Pinia – Vuex è deprecato)**

| Area              | Dettagli                                    |
| ----------------- | ------------------------------------------- |
| Store Setup       | ✅✅✅ (`defineStore`, `useCounterStore()`) |
| Reactive State    | ✅✅✅ (mutazioni dirette, no `commit`)     |
| Computed + Action | ✅✅✅ (`getters`, `actions`, async logic)  |
| Persistenza       | ✅✅ (`pinia-plugin-persistedstate`)        |
| Store Modulari    | ✅✅ (più store per dominio funzionale)     |

---

### ⚙️ 4. **Tooling & Build (Vite, ESLint, Prettier)**

| Area              | Dettagli                                               |
| ----------------- | ------------------------------------------------------ |
| Vite + Vue Plugin | ✅✅✅ (HMR, build rapido, auto-import di composables) |
| ESLint + Prettier | ✅✅✅ (standardizzazione codice)                      |
| Auto Import       | ✅✅ (`unplugin-auto-import`, `components`)            |
| Path Alias (`@`)  | ✅✅✅ (`vite.config.ts`, tsconfig `paths`)            |

---

### 🎨 5. **UI Frameworks & Animazioni**

| Area           | Dettagli                                                               |
| -------------- | ---------------------------------------------------------------------- |
| Vuetify 3      | ✅✅✅ (Material Design, Dark mode, Layout system)                     |
| Tailwind CSS   | ✅✅✅ (design utility-first, classi dinamiche)                        |
| Animazioni Vue | ✅✅✅ (`<transition>`, `transition-group`, `v-motion`, Framer Motion) |

---

### 🧪 6. **Testing**

| Area                  | Dettagli                               |
| --------------------- | -------------------------------------- |
| Unit Testing          | ✅✅✅ (Vitest + Vue Test Utils)       |
| Snapshot Testing      | ✅✅ (salvataggio e confronto visuale) |
| E2E Testing           | ✅✅ (Cypress / Playwright)            |
| Mocking + Test Stores | ✅✅ (`vi.fn()`, `mockStore`)          |

---

### 💻 7. **TypeScript + Vue**

| Area                               | Dettagli                                                   |
| ---------------------------------- | ---------------------------------------------------------- |
| Setup() Tipizzato                  | ✅✅✅ (`defineComponent<Props>()`, `defineStore<Type>()`) |
| SFC con `<script setup lang="ts">` | ✅✅✅ (composables, props, emits tipizzati)               |
| Type Inference + Generics          | ✅✅ (dati derivati e helpers)                             |
| Global Types                       | ✅✅ (`env.d.ts`, `vue-shim.d.ts`)                         |

---

### 🧬 8. **Composables (Code Reuse)**

| Area                  | Dettagli                                                             |
| --------------------- | -------------------------------------------------------------------- |
| Creazione composables | ✅✅✅ (`useFetch`, `useTimer`, `useDebounce`)                       |
| Moduli riusabili      | ✅✅ (condividere logica tra componenti)                             |
| VueUse                | ✅✅✅ (libreria di composables: `useDark`, `useLocalStorage`, ecc.) |

---

### 🛰️ 9. **API Integration & Full Stack**

| Area                        | Dettagli                                             |
| --------------------------- | ---------------------------------------------------- |
| Fetch API / Axios           | ✅✅✅ (`axios`, `useFetch`, `await`)                |
| GraphQL                     | ✅✅ (Apollo Client, `useQuery`, `useMutation`)      |
| Nuxt 3                      | ✅✅✅ (Vue full-stack: SSR, API routes, middleware) |
| Firebase / Supabase         | ✅✅ (auth, storage, realtime DB)                    |
| Serverless (Netlify/Vercel) | ✅✅ (deploy frontend + API lambda)                  |

---

### 🔐 10. **Sicurezza & Performance**

| Area               | Dettagli                                 |
| ------------------ | ---------------------------------------- |
| Input Sanitization | ✅✅ (`v-model`, `sanitize-html`)        |
| Debounce Input     | ✅✅ (`lodash.debounce`, `watchEffect`)  |
| Code Splitting     | ✅✅✅ (dynamic `import()`, lazy routes) |
| Perf Monitor       | ✅ (Vue Devtools, `why-did-you-render`)  |

---

### 📚 Risorse Consigliate

- 📘 **Vue Mastery** / **Vue School** – corsi ufficiali e aggiornati
- 📙 _Vue.js: Up & Running_ – Callum Macrae
- 📺 **Academind**, **The Net Ninja**, **VueJS Developers** su YouTube
- 🔧 [VueUse](https://vueuse.org) – collezione di composables utilissimi
- 🚀 [Nuxt 3 Docs](https://nuxt.com/docs) – per fullstack con Vue

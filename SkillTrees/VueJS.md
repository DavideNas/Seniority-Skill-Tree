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

## 🎓 Risorse & Libri x studiare:

### _Gratuite_

- **YouTube Videos**:

  1. **[Vue.js 3 Crash Course – Traversy Media](https://www.youtube.com/watch?v=qZXt1Aom3Cs)**  
     Corso completo e conciso su Vue 3. Perfetto per chi parte da zero e vuole capire la Composition API.

  2. **[Vue JS Full Course 2023 – freeCodeCamp](https://www.youtube.com/watch?v=YrxBCBibVo0)**  
     Oltre 10 ore di corso completo: componenti, routing, Vuex, Composition API e altro. Estremamente formativo.

  3. **[Vue Mastery – Intro to Vue 3](https://www.youtube.com/watch?v=ZqgiuPt5QZo)**  
     Panoramica gratuita della nuova Composition API e del sistema di reactive binding in Vue 3.

- **YouTube Channels**:

  1. [The Net Ninja – Vue.js Series](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gXdVXVJBmHpSI7zCEcjLUX)  
     Canale famoso per i suoi corsi ben spiegati. Ha sia serie Vue 2 che Vue 3.

  2. [Academind](https://www.youtube.com/c/Academind)  
     Ottimo per spiegazioni dettagliate e visuali. Cerca "Vue 3" nel loro canale.

  3. [Vue Mastery](https://www.youtube.com/c/VueMastery)  
     Partner ufficiale del team di Vue.js. Offre video tecnici, anche avanzati.

- **Articoli & Documentazione**:

  - 📘 **[Documentazione ufficiale Vue 3](https://vuejs.org/)**  
    Esempi chiari, guida passo-passo, best practice. Il miglior punto di partenza.

  - 📘 **[Vue 3 Composition API vs Options API](https://vuejs.org/guide/introduction.html#composition-api-vs-options-api)**  
    Ottima guida per capire le differenze tra i due modi di scrivere componenti.

  - 📘 **[Vue Router Docs](https://router.vuejs.org/)**  
    Documentazione ufficiale del sistema di routing per Vue.

  - 📘 **[Pinia (Vuex Replacement) Docs](https://pinia.vuejs.org/)**  
    Documentazione per il nuovo state management system che sostituisce Vuex.

---

### _A Pagamento_

- **Libri**:

  - 📙 _Fullstack Vue: The Complete Guide to Vue.js_  
    Copre Vue 2, ma è ancora valido per i concetti base (molti dei quali sono compatibili). Ideale per capire le fondamenta.

  - 📘 _The Vue.js 3 Cookbook_ – Heitor Ramon Ribeiro  
    Oltre 80 esempi pratici e soluzioni a problemi comuni in Vue 3. Molto utile per sviluppatori già avviati.

  - 📕 _Vue.js Up and Running_ – Callum Macrae (O’Reilly)  
    Ottimo per avere una panoramica veloce del framework, anche se leggermente datato.

- **Corsi consigliati dalla community**:

  1. **[Vue Mastery (vue mastery.com)](https://www.vuemastery.com/)**  
     Corso ufficiale Vue.js. Alta qualità, copre dalla base a concetti avanzati. Alcuni contenuti gratuiti, il resto a pagamento.

  2. **[Vue.js: The Complete Guide (incl. Router & Composition API) – Udemy](https://www.udemy.com/course/vuejs-2-the-complete-guide/)**  
     Di Maximilian Schwarzmüller. Copre sia Vue 2 che Vue 3 (Composition API, Vuex, Pinia, routing, forms, ecc.). È probabilmente **il miglior corso** online.

  3. **[Frontend Masters – Vue 3 courses](https://frontendmasters.com/learn/vue/)**  
     Ottimo per approfondimenti professionali su Vue.js. Materiale aggiornato, docenti di alto livello.

---

### _Extra: Tools & Ecosistema_

- **Pinia** – nuovo standard per il global state in Vue 3. Più semplice di Vuex.  
  👉 [https://pinia.vuejs.org](https://pinia.vuejs.org)

- **Vue Router** – routing ufficiale per Vue 3.  
  👉 [https://router.vuejs.org](https://router.vuejs.org)

- **Vite** – modernissimo dev server/bundler pensato per Vue.  
  👉 [https://vitejs.dev](https://vitejs.dev)

- **Vue DevTools (Chrome/Firefox)** – debugging in tempo reale delle app Vue.  
  👉 [https://devtools.vuejs.org](https://devtools.vuejs.org)

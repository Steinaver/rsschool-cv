# Vlad Hodlievskyi

## My Contact Info:

- [Telegram](https://t.me/pmhhhhhh)
- [GitHub](https://github.com/Steinaver)
- [Discord](https://discordapp.com/users/atrna_)

---

## About

Motivated frontend developer with a strong theoretical background and extensive hands-on practice in modern web technologies, including React and TypeScript.  
Passionate about writing clean, efficient, and scalable code. Focused on performance, code quality, and UI consistency.  
Experienced in building personal and training projects, solving a wide range of real-world problems, and continuously improving development skills through deep exploration of frontend tools and best practices.

---

## Skills

### Core Technologies

- HTML5, CSS3, SCSS, BEM, Responsive Design, Cross-browser Compatibility
- JavaScript (ES6+) — advanced understanding of core principles and performance optimization

### Frameworks & Libraries

- React (functional components, hooks, context)
- TypeScript (in-depth usage with React)
- React Router, Redux, Redux Toolkit, RTK Query, React Query
- Jest, Testing Library, Playwright / Cypress, Visual Regression Testing
- Framer Motion, CSS/JS animations

### Tooling & DevOps

- Webpack, Vite, Babel
- ESLint, Prettier, Stylelint
- Git, GitHub, GitHub Actions
- i18next, Error Boundaries, Sentry

### Performance & Optimization

- Bundle size analysis, lazy loading, code splitting
- Efficient re-renders, memoization strategies, profiling React apps
- Lighthouse audits, Core Web Vitals improvements

### Other

- Writing reusable components and scalable design systems
- Working with design tools and pixel-perfect implementation
- Debugging and handling edge cases in real-world production apps

---

## Code Example

```
function chooseBestSum(maxDistance, townsToVisit, distances) {
    let bestSum = 0;
    
    function findCombination(townsLeft, start = 0, currentSum = 0) {
        if (townsLeft === 0) {
            if (currentSum <= maxDistance && currentSum > bestSum) bestSum = currentSum;
            return;
        }
        for (let i = start; i < distances.length; i++) {
            if (currentSum + distances[i] > maxDistance) continue;
            findCombination(townsLeft - 1, i + 1, currentSum + distances[i]);
        }
    }
    
    findCombination(townsToVisit);
    return bestSum > 0 ? bestSum : null;
}
```

---

## Languages

- **Russian** — Native
- **Ukrainian** — Fluent
- **English** — Intermediate (reading technical documentation, writing, and verbal communication)
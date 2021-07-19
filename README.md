# Daily Practice

I just readed [Reflections from 52 weeks 52 proyects](https://speakerdeck.com/jeffersonlam/reflections-from-52-weeks-52-projects).

```javascript
import SoftwareEngineer from "./index";

const me = new SoftwareEngineer({
  name: "Eliaz Bobadilla",
  age: 14,
  currentOS: "Arch Linux",
  languages: ["Python", "Javascript", "Golang", "Ruby"],
  tools: {
    javascript: ["React", "Express", "Webpack", "pm2"],
    python: ["Flask", "Django"],
    ruby: ["Rails"],
    general: ["Docker"],
    editors: ["Neovim", "WebStorm"],
  },
  askMeAbout: [
    "Cryptocurrency",
    "Anime",
    "Linux",
    "Manga",
    "Web Development",
    "Backend",
  ],
  currentFocus: "React Web Apps",
  funFact: "Javascript is the best Programming Language",
  challenge: " I am doing the #InfiniteDaysOfCode challenge.",
});

console.log(me);
```

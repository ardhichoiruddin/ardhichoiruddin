```javascript
import SoftwareDeveloper from 'ardhi';
import { Languages, Frameworks } from 'ardhi/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Ardhi';
  title    = 'Fullstack Developer';
  location = 'Yogyakarta, Indonesia';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'TypeScript', ...Languages];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
  frameworks = ['Fastify', 'Svelte', 'React Js', 'Next Js', ...Frameworks];
}

```

![](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ardhichoiruddin&theme=default)

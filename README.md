

```javascript
import SoftwareDeveloper from 'munafio';
import { Languages, Frameworks } from 'munafio/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Munaf Aqeel Mahdi';
  title    = 'Senior Software Developer';
  location = 'Babil, IQ';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'TypeScript', 'PHP', ...Languages];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
  frameworks = ['Vue', 'React', 'Next.js', 'Laravel', 'Nest.js', ...Frameworks];
}

```

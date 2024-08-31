

```javascript
import SoftwareDeveloper from 'munafio';
import { Languages, Frameworks, Cms } from 'huuha/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Nguyen Huu Ha';
  title    = 'Senior Software Developer';
  location = 'Thu Duc, Ho Chi Minh, Viet Nam';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'TypeScript', 'PHP', 'Python', ...Languages];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
  frameworks = ['Vue', 'React', 'Next.js', 'Laravel', 'React Native', ...Frameworks];
  cms        = ['Wordpress', 'Magento', 'Opencart', ...Cms];
}

```

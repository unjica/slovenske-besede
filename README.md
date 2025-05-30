# Slovenske Besede

A collection of Slovenian words and phrases.

## Description

This repository contains a comprehensive list of Slovenian words in multiple formats:
- `slovenske_besede.txt` - Plain text file with one word per line
- `slovenske_besede.js` - JavaScript array of words
- `slovenske_besede.ts` - TypeScript version with type definitions and utility functions

## Usage

### Plain Text
The words are stored in a simple text file format, with one word per line. You can use this file as a reference or integrate it into your applications.

### JavaScript
```javascript
import { slovenskeBesede } from './slovenske_besede.js';
// Use the array of words
console.log(slovenskeBesede[0]); // First word
```

### TypeScript
```typescript
import { slovenskeBesede, slovenskeBesedeUtils } from './slovenske_besede';

// Use the array of words
console.log(slovenskeBesede[0]); // First word

// Use utility functions
const exists = slovenskeBesedeUtils.exists('beseda');
const wordsWithPrefix = slovenskeBesedeUtils.findByPrefix('bes');
const randomWord = slovenskeBesedeUtils.getRandomWord();
```

## License

This project is licensed under the MIT License. 
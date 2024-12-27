# My React Button Library

A modern, customizable button component for React applications.

## Creation

#### package.json

```json
{
  "name": "aladin-p13-react-library", // Replace with your "unique" library name
  "version": "0.1.0", // Replace with your library version, "increment each time you modify the library"
  "type": "module",
  "main": "dist/index.js",
  "module": "dist/index.js",
  "files": [
    "dist"
  ],
  "publishConfig": {
    "access": "public"
  },
  "scripts": {
    ...
  },
  "peerDependencies": {
    "react": ">=16.8.0",
    "react-dom": ">=16.8.0"
  },
  "devDependencies": {
    ...
  }
}
```

#### Publishing

```bash
npm login
npm run build
npm publish
```

## Installation

```bash
npm install aladin-p13-react-library
```

## Usage

```jsx
import { Button } from 'aladin-p13-react-library';

function App() {
  return (
    <Button 
      variant="primary" // 'primary' | 'secondary' | 'outline'
      size="medium" // 'small' | 'medium' | 'large'
      onClick={() => console.log('Button clicked!')}
    >
      Click me!
    </Button>
  );
}
```

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| variant | 'primary' \| 'secondary' \| 'outline' | 'primary' | The style variant of the button |
| size | 'small' \| 'medium' \| 'large' | 'medium' | The size of the button |
| disabled | boolean | false | Whether the button is disabled |
| onClick | function | - | Click handler |
| className | string | - | Additional CSS classes |

## License

MIT

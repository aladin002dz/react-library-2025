# My React Button Library

A modern, customizable button component for React applications.

## Creation

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

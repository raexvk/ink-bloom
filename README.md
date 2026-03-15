# Ink Bloom

Animated digit component with an ink-in-water dissolve effect. Digits bloom in with blur and scale, creating an organic morphing transition between values.

[Live Demo →](https://vbuilds.vercel.app/components/ink-bloom)

## Usage

```tsx
import { InkBloom } from "./ink-bloom";

function MyComponent() {
  const [digit, setDigit] = useState(0);
  return <InkBloom value={digit} size={64} />;
}
```

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `value` | `number` | `0` | Digit to display (0–9) |
| `size` | `number` | `64` | Width in pixels. Height is 1.5× width. |

## Built With

- React
- Framer Motion
- TypeScript

## License

MIT

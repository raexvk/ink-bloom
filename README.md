# @raex-ui/ink-bloom

An ink-in-water dissolve effect where digits bloom in with blur and scale, creating an organic morphing transition between values.

![ink-bloom](https://raex-ui.vercel.app/components/ink-bloom)

## Install

```bash
npm install @raex-ui/ink-bloom
```

## Usage

```tsx
import { InkBloom } from "@raex-ui/ink-bloom";

function MyComponent() {
  const [digit, setDigit] = useState(0);
  return <InkBloom value={digit} size={64} />;
}
```

## Props

| Prop | Type | Description |
|------|------|-------------|
| `value` | `number` | Digit to display (0–9) |
| `size` | `number` | Width in pixels. Height is automatically 1.5× width. |

## Peer Dependencies

- `react` >=18
- `react-dom` >=18
- `framer-motion` >=10

No Tailwind CSS required.

## License

MIT

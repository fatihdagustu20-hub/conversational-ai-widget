# FatihAI Conversational AI Widget

AI Chat Widget for Your Website - Add AI chat to your website in minutes.

## Features

- ✅ Embed in 2 minutes with one script tag
- ✅ Claude-powered responses
- ✅ Customizable widget (colors, position)
- ✅ Lead capture built-in
- ✅ 24/7 automated support
- ✅ Multilingual support

## Installation

Add this single line to your HTML:

```html
<script src="https://fatihai.app/widget.js" data-key="YOUR_API_KEY"></script>
```

That's it! The widget will appear in the bottom-right corner.

## Customization

```html
<script
  src="https://fatihai.app/widget.js"
  data-key="YOUR_API_KEY"
  data-color="#6366f1"
  data-position="bottom-right"
  data-greeting="Hi! How can I help?"
></script>
```

### Options

| Option | Default | Description |
|--------|---------|-------------|
| data-key | required | Your API key |
| data-color | #6366f1 | Widget color |
| data-position | bottom-right | Widget position |
| data-greeting | Hello! | Initial message |

## React/Next.js

```jsx
import { useEffect } from 'react';

export default function ChatWidget() {
  useEffect(() => {
    const script = document.createElement('script');
    script.src = 'https://fatihai.app/widget.js';
    script.setAttribute('data-key', process.env.NEXT_PUBLIC_FATIHAI_KEY);
    document.body.appendChild(script);

    return () => script.remove();
  }, []);

  return null;
}
```

## Pricing

**$299/mo** - Unlimited conversations, all features included.

## Links

- 🌐 [Get Started](https://fatihai.app/register)
- 📧 [Support](mailto:support@fatihai.app)

---

Made with ❤️ by [FatihAI](https://fatihai.app) | Updated: 2026-02-04

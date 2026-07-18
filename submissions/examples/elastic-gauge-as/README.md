# Elastic Gauge

A reusable **Elastic Gauge** component built for **EaseMotion CSS**. It combines a neon-inspired circular gauge with a subtle elastic pulse animation, making it suitable for dashboards, analytics panels, and monitoring interfaces.

---

## Features

- 🌈 Neon glow effect
- 📊 Circular progress gauge
- ✨ Elastic pulse animation
- 🎨 Customizable using CSS variables
- 📱 Responsive layout
- 🚫 No JavaScript required

---

## Files

```
elastic-gauge-as/
├── demo.html
├── style.css
└── README.md
```

---

## Usage

```html
<div
class="ease-gauge"
style="
--gauge-value:72%;
--gauge-color:#22d3ee;
">

<div class="ease-gauge-ring"></div>

<div class="ease-gauge-content">

<div class="ease-gauge-value">
72%
</div>

<div class="ease-gauge-label">
CPU Usage
</div>

</div>

</div>
```

---

## Customization

The gauge can be customized using CSS variables:

```css
--gauge-value:72%;
--gauge-color:#22d3ee;
```

---

## Accessibility

- Uses semantic text labels
- Responsive sizing
- Decorative animation does not affect readability

---

## Why it fits EaseMotion CSS

The Elastic Gauge follows EaseMotion CSS's animation-first philosophy by combining reusable class names with subtle motion and customizable styling using pure CSS.

---

## Author

Created as a GSSoC'26 contribution for **EaseMotion CSS**.
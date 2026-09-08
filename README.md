# 💡 Light Painter — Long-Exposure Light Art Studio

Light Painter generates luminous, long-exposure light art trails with organic neon decay.

## 🎨 Rendering Mechanics
- **Dual Buffer Accumulation**: Foreground drawing buffer continuously composites onto a semi-transparent trailing background buffer ($Alpha = 0.04$).
- **Glow Filter Kernels**: Multiple composite operation layers (`lighter` and `source-over`) emulate optical camera sensor bloom.
- **Dynamic Chromatic Shifts**: Trajectory velocity determines HSL hue rotation and brush radius.

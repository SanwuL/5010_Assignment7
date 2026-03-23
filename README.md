# 5010_Assignment7

🔗 p5 Sketch: [[My LINK HERE](https://editor.p5js.org/SanwuL/sketches/TfuBUaMuA)]

## Description

This project builds on a previous particle interaction sketch where red and white agents respond differently to a movable control point. White particles are attracted while red particles are repelled, and this relationship can be inverted through user input. My aesthetic goal was to transform this simple rule-based system into something that feels more like a dynamic energy field rather than a set of discrete points. By applying a glow-based post-processing shader, the particles begin to visually blend into one another, creating a softer and more atmospheric impression. The control point, in particular, becomes less of a precise cursor and more like a source of influence, affecting the surrounding space in a more immersive way.

Technically, I was interested in exploring how post-processing shaders reinterpret an existing image rather than generating new geometry. The shader samples neighboring pixels and redistributes brightness to produce a glow effect, effectively expanding areas of high intensity. This adds a sense of depth, motion continuity, and visual cohesion to the system. However, the shader also reduces clarity: individual particles become less sharply defined, and the original structure of the system is slightly obscured. This trade-off highlights an important aspect of shader design—while post-processing can enhance atmosphere and visual interest, it can also alter readability and the perceived precision of the underlying system.

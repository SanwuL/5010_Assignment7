# 5010_Assignment7

🔗 p5 Sketch: [[My LINK HERE](https://editor.p5js.org/SanwuL/sketches/TfuBUaMuA)]

## Description

This project is based on a particle interaction system generated with randomness. Red and white points are distributed across the screen, each behaving differently in response to a control point. When the user clicks, a blue point appears and follows the mouse, attracting white particles while repelling red ones. Clicking again reverses the behavior, turning the control point yellow so that it attracts red particles and repels white ones. The system creates shifting clusters, boundaries, and motion patterns as particles continuously respond to the moving point.

My aesthetic intention was to move beyond treating these elements as simple points and instead make them feel like part of a larger environment. By applying a glow-based post-processing shader, the particles appear to emit light, resembling stars rather than discrete graphical elements. This transforms the scene into something closer to a cosmic or night-sky space, where motion feels more fluid and continuous. Technically, the shader samples surrounding pixels and redistributes brightness to create a soft glow effect. While this enhances atmosphere and visual cohesion, it also reduces the sharpness of individual particles, making the system slightly less precise but more immersive overall.

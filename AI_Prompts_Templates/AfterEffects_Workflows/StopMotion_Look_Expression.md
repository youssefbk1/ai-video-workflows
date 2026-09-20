# Stop-Motion Aesthetic Expression for After Effects

When compositing AI-generated video or flat 2D vector designs, applying this expression to the `Time Remap` or `Position` property helps simulate the tactile, imperfect feel of traditional claymation or papercraft animation.

## Posterize Time & Wiggle (Apply to Position)

```javascript
// Simulates a 12fps stop-motion look with slight physical camera imperfections
posterizeTime(12);
freq = 2; // Frequency of the shake
amp = 3;  // Amplitude in pixels
wiggle(freq, amp);

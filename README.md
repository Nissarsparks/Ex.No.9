# Ex.No.9 – Exploration of Prompting Techniques for Video Generation

## Title

**Exploration of Prompting Techniques for AI Video Generation**

### Tool Used

**PixVerse AI Video Generator**

### Topic of Video

**A sports car racing on a high-speed track**

---

## Aim

The aim of this experiment is to study how different prompting methods affect an AI-generated racing video. The experiment focuses on the appearance of the car, racing movement, track environment, lighting, camera angle, speed and overall visual consistency. Different prompts are used in PixVerse and their outputs are compared.

---

## Tool Used – PixVerse

PixVerse is an AI video generation platform that can create short video clips from text descriptions. It provides different visual styles and motion controls that can be used to guide the generated scene.

### Main Features Used

| Feature           | Details                          |
| ----------------- | -------------------------------- |
| Tool              | PixVerse                         |
| Generation Method | Text-to-Video                    |
| Video Duration    | Approximately 5 seconds          |
| Visual Style      | Cinematic / Realistic            |
| Motion Control    | Low to High                      |
| Main Task         | Sports Car Racing                |
| Prompt Type       | Text Prompt with Negative Prompt |

PixVerse was selected because it can generate short action scenes and allows the prompt to describe both the visual appearance and movement of the subject.

---

# Subject Selected

The selected scene is a **high-performance sports car racing around a professional racing circuit**.

The video was planned to include:

* A clearly visible sports car
* A racing track with curves
* High-speed movement
* Motion blur
* Track barriers and surroundings
* Dramatic lighting
* Dynamic camera movement

A racing scene is suitable for this experiment because it contains continuous motion and allows different camera directions, speeds and environmental details to be tested.

---

# Basic Elements of a Video Prompt

A good racing-video prompt can contain several important elements.

| Element         | Purpose                        | Example                             |
| --------------- | ------------------------------ | ----------------------------------- |
| Vehicle         | Defines the main subject       | Red sports car                      |
| Action          | Describes movement             | Accelerating through a corner       |
| Environment     | Describes the location         | Professional racing circuit         |
| Speed           | Controls the feeling of motion | High-speed racing                   |
| Lighting        | Sets the visual atmosphere     | Sunset lighting                     |
| Camera          | Controls viewpoint             | Low-angle tracking shot             |
| Effects         | Adds realism                   | Motion blur and tire smoke          |
| Negative Prompt | Reduces unwanted defects       | Blurry, distorted car, extra wheels |

Adding relevant details gives the video model clearer instructions about the intended scene.

---

# Prompting Techniques Tested

Four prompts were created. Each prompt adds more control than the previous one.

---

## Technique 1 – Basic Prompt

### Prompt

```text
A sports car racing on a track.
```

### Settings

* **Style:** Default
* **Motion:** Medium
* **Negative Prompt:** None

### Observation

The generated video showed a car moving on a track, but the scene was fairly simple. The racing environment had limited detail and the speed of the car was not very convincing. The camera movement was also basic.
### video


https://github.com/user-attachments/assets/9c87dd7b-0828-4bb9-8e7e-217ba9899355



### Assessment

| Parameter         |    Score | Observation                |
| ----------------- | -------: | -------------------------- |
| Car Appearance    |      2/5 | Simple vehicle details     |
| Racing Motion     |      2/5 | Movement was basic         |
| Track Environment |      2/5 | Limited background details |
| Lighting          |      1/5 | No specific lighting       |
| Scene Consistency |      2/5 | Understandable but simple  |
| **Total**         | **9/25** |                            |

---

# Technique 2 – Descriptive Prompt

### Prompt

```text
A modern sports car racing at high speed around a professional race track.
The car accelerates through a sharp corner while track barriers and
grandstands are visible in the background. The camera follows the car
from the side.
```

### Negative Prompt

```text
blurry, distorted, low quality
```

### Settings

* **Style:** Default
* **Motion:** Medium

### Observation

The additional details produced a more recognizable racing scene. The track, barriers and background became more visible. The car appeared to move faster and the side-following camera created a better sense of action.
###video



https://github.com/user-attachments/assets/864589dd-afda-4d37-8ae4-0aa5c571ff9d


### Assessment

| Parameter         |     Score | Observation                |
| ----------------- | --------: | -------------------------- |
| Car Appearance    |       3/5 | More defined vehicle       |
| Racing Motion     |       3/5 | Better sense of speed      |
| Track Environment |       3/5 | Track and barriers visible |
| Lighting          |       2/5 | Still fairly neutral       |
| Scene Consistency |       3/5 | More organized scene       |
| **Total**         | **14/25** |                            |

---

# Technique 3 – Style-Based Prompt

### Prompt

```text
Cinematic racing video of a sleek high-performance sports car with a
metallic body speeding around a professional circuit. The car takes a
sharp corner at high speed while the tires grip the asphalt. Track
barriers, racing curbs and grandstands appear in the background.
Dramatic evening lighting, realistic reflections, strong motion blur,
dynamic camera movement and an intense racing atmosphere.
```

### Negative Prompt

```text
blurry, distorted car, deformed wheels, low quality, pixelated
```

### Settings

* **Style:** Cinematic / Realistic
* **Motion:** High

### Observation

The style-based prompt produced a more realistic racing environment. The car had better surface reflections and the track contained more visual detail. Motion blur helped communicate speed and the cinematic lighting improved the overall appearance.

###video


https://github.com/user-attachments/assets/396c2427-4169-47c0-bef5-ae3ee26f860a



### Assessment

| Parameter         |     Score | Observation               |
| ----------------- | --------: | ------------------------- |
| Car Appearance    |       4/5 | Detailed and realistic    |
| Racing Motion     |       4/5 | Stronger speed effect     |
| Track Environment |       4/5 | Detailed racing circuit   |
| Lighting          |       4/5 | Dramatic evening lighting |
| Scene Consistency |       4/5 | Good visual continuity    |
| **Total**         | **20/25** |                           |

---

# Technique 4 – Detailed Cinematic Racing Prompt

## Final Prompt

```text
Create a realistic cinematic racing scene featuring a powerful
high-performance sports car with a metallic body racing on a professional
circuit. The car accelerates rapidly along a straight section and then
enters a sharp right-hand corner at high speed. The tires remain firmly
connected to the asphalt while subtle tire smoke appears during the turn.

Use a low camera angle close to the track and follow the car with a fast
tracking movement. Begin with a side view and smoothly move toward a
rear three-quarter view as the car exits the corner. Add realistic wheel
rotation, reflections on the car body, motion blur and slight road dust.

The circuit should contain red-and-white curbs, safety barriers,
grandstands and distant track lights. Use dramatic sunset lighting with
warm highlights and long shadows. Keep the car design, wheels, track and
lighting consistent throughout the clip. The mood should be exciting,
fast and cinematic with realistic physics and smooth continuous motion.
```

## Negative Prompt

```text
blurry, distorted car, deformed wheels, extra wheels, floating vehicle,
warped body, unrealistic motion, jerky camera, duplicate cars, pixelated,
low quality, text, watermark
```

### Settings

* **Style:** Cinematic / Realistic
* **Motion:** High
* **Duration:** 5 seconds

### Observation

This prompt produced the most detailed racing scene in the experiment. The additional information about acceleration, cornering, camera movement, lighting and track design helped create a stronger sense of speed.

The car remained more consistent while moving through the scene. Minor distortions could still occur around the wheels during fast movement.

### Assessment

| Parameter         |     Score | Observation                |
| ----------------- | --------: | -------------------------- |
| Car Appearance    |       5/5 | Detailed and realistic     |
| Racing Motion     |       5/5 | Strong high-speed movement |
| Track Environment |       5/5 | Rich racing environment    |
| Lighting          |       5/5 | Cinematic sunset lighting  |
| Scene Consistency |       4/5 | Minor wheel distortion     |
| **Total**         | **24/25** |                            |

---

# Final Video Details

| Property       | Result                           |
| -------------- | -------------------------------- |
| Tool           | PixVerse                         |
| Duration       | 5 seconds                        |
| Visual Style   | Cinematic / Realistic            |
| Main Subject   | High-performance sports car      |
| Environment    | Professional racing circuit      |
| Camera         | Low-angle tracking shot          |
| Motion Setting | High                             |
| Prompt Used    | Detailed cinematic racing prompt |

---

# Frame Analysis

The generated racing clip was observed at different points to understand how the vehicle movement developed.

| Time | Scene Observation                                               |
| ---- | --------------------------------------------------------------- |
| 0:00 | Car enters the frame on the racing track                        |
| 0:01 | Car accelerates along the straight section                      |
| 0:02 | Vehicle approaches the corner at high speed                     |
| 0:03 | Car turns through the corner with visible motion blur           |
| 0:04 | Camera follows the car as it exits the turn                     |
| 0:05 | Car moves away while the camera completes the tracking movement |

The main difficulty was maintaining perfect wheel and vehicle geometry during fast movement.

---

# Comparison of the Four Prompts

| Criteria          |    Basic | Descriptive | Style-Based | Cinematic |
| ----------------- | -------: | ----------: | ----------: | --------: |
| Car Detail        |      2/5 |         3/5 |         4/5 |       5/5 |
| Motion Quality    |      2/5 |         3/5 |         4/5 |       5/5 |
| Track Environment |      2/5 |         3/5 |         4/5 |       5/5 |
| Lighting          |      1/5 |         2/5 |         4/5 |       5/5 |
| Scene Consistency |      2/5 |         3/5 |         4/5 |       4/5 |
| **Total**         | **9/25** |   **14/25** |   **20/25** | **24/25** |

The comparison indicates that additional prompt details provided more control over the vehicle, environment, movement and camera behavior.

---

# Results and Discussion

### 1. Vehicle Description

The basic prompt only mentioned a sports car. Adding information about its appearance and performance resulted in a more recognizable vehicle.

### 2. Racing Action

Describing acceleration, cornering and high-speed movement helped create a stronger racing effect than simply saying that the car was "racing."

### 3. Track Environment

Adding curbs, barriers, grandstands and track lights made the scene look more like a professional racing circuit.

### 4. Lighting

The use of sunset lighting created stronger reflections and shadows on the car and track.

### 5. Camera Movement

A low-angle tracking shot made the video feel more dynamic and helped communicate the speed of the vehicle.

### 6. Negative Prompts

Negative prompts were used to reduce common AI video problems such as distorted wheels, duplicate cars, warped body shapes and blurry frames.

---

# Limitations Observed

Some limitations remained even with the detailed prompt.

| Problem                | Observation                                                  |
| ---------------------- | ------------------------------------------------------------ |
| Wheel Geometry         | Wheels may become distorted during rapid movement            |
| Exact Speed            | The precise speed of the car cannot be directly specified    |
| Physics                | Tire grip and smoke may not always look physically accurate  |
| Background Consistency | Track objects can change slightly between frames             |
| Camera Control         | Exact camera timing is difficult to control using text alone |

These limitations show that detailed prompting improves the result but does not guarantee completely realistic racing physics.

---

# Important Prompting Lessons

The experiment provided the following lessons:

1. **Describe the vehicle clearly.**
2. **Explain the exact racing action.**
3. **Mention the type of track and important surroundings.**
4. **Use lighting descriptions to improve realism.**
5. **Specify the camera position and movement.**
6. **Use motion-related terms such as acceleration and tracking shot.**
7. **Use negative prompts to reduce vehicle and wheel distortions.**
8. **Use appropriate motion intensity for fast-moving scenes.**

---

# Conclusion

This experiment showed that the structure and detail of a prompt can significantly affect an AI-generated racing video.

The basic prompt produced a simple car movement, while the descriptive and style-based prompts added more detail to the vehicle, track and atmosphere.

The detailed cinematic prompt provided greater control because it described the car, racing action, track, lighting, camera movement and unwanted visual errors.

The experiment therefore demonstrates that effective AI video prompting requires clear instructions about both the **appearance of the scene and the movement taking place within it**.

---

# References

1. PixVerse AI Video Generator – https://pixverse.ai/
2. Prompt Engineering Guide – https://www.promptingguide.ai/
3. OpenAI Sora – https://openai.com/sora/
4. Runway – https://runwayml.com/

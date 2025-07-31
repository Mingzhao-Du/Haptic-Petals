### Labs

During this week’s development session, our group completed and presented the elevator pitch for Haptic Petals, an interactive installation that explores the convergence of emotional rhythm, digital ecology, and embodied interaction. By integrating gesture and sound, the project generates the fragmentation and reformation of a digital flower, framing user movement not merely as input, but as an affective presence within a sensory feedback loop. The work positions media as both an expressive medium and a reflective space through which to examine human–nature entanglement in technologically mediated environments.

In parallel, we began integrating Leap Motion into the system and conducted preliminary tests on its impact on the model’s visual behavior. We observed that after introducing gesture recognition, the digital flower’s particle-based transformations lost some of their fluidity and coherence compared to earlier, music-driven iterations. Our initial analysis indicates that these changes may result from altered parameter update frequencies introduced by Leap Motion, which interfered with the system’s real-time visual responsiveness.

Moving forward, we plan to recalibrate these parameters to restore seamless interaction between gesture input and visual output. This will allow us to maintain the flower’s ambient vitality and ensure that both gestural and environmental inputs continue to support our core concept of digital life forms that respond with emotional and ecological sensitivity.

---

### Reading & Reflections

While reading Eryk Sawicki’s article “Storytelling in Games as Compared to Film”, I was particularly struck by the idea that interaction itself constitutes narrative. Unlike traditional linear storytelling in film or literature, where narrative is shaped entirely by the author, Sawicki argues that storytelling in games is dynamically generated through players’ decisions, actions, and engagement. This challenges the conventional notion of stories as “told,” instead positioning them as “experienced,” continuously unfolding through perception, interaction, and embodied response.

This perspective has deeply informed my approach to my final project, “The Archive That Never Existed: An Immersive Exhibition of AIGC-Generated Fictional Memories.” In this project, I attempt to transform AI-generated fictional memory images into interactive 3D environments. Rather than passively viewing these images, audiences actively participate in memory-making by moving through space, triggering sound cues, and engaging with responsive environmental elements. This action-based immersion directly embodies Sawicki’s notion that action is narrative.

---

### Peer Support

This week, we finalised the core framework and major functionalities of the project. With the foundational structure in place, our focus has shifted toward refining and optimising the existing content. My teammate and I discussed the next steps in detail and outlined the upcoming tasks, which include fine-tuning system parameters and experimenting with additional visual effects. These enhancements are intended to strengthen the project’s expressive potential and immersive quality. We aim to complete this phase of development by the end of next week in preparation for the final presentation.

---

### Project Development

We also began testing Leap Motion’s gesture recognition capabilities to evaluate its integration with our interactive system. Prior to this, we completed several key technical preparations. As shown below, we successfully processed six distinct flower models, each derived from 3D scans of real flowers.

Rather than digitally modeling the forms from scratch, we adopted a scanning-based approach to preserve the natural complexity and organic textures of actual floral structures. The scanned models were then refined and cleaned using MeshLab, where we optimized mesh topology and performed format conversions to ensure compatibility with TouchDesigner’s real-time rendering environment. These steps laid a solid technical foundation for the subsequent development of gesture-driven interaction and visual responsiveness.

<img width="2559" height="1525" alt="e1bcf72b80107e4db164a900422d577d" src="https://github.com/user-attachments/assets/c733c67b-4c1c-45b4-a0e0-d7760e6da45f" />


## 3D Scene Development and Navigation

When I set out to design my 3D scene, I aimed to craft an environment that was both inviting and technically illustrative. I decided on a cozy café setting featuring a wooden table, coffee cups, a vase of flowers, and a hanging lamp. These objects were chosen for their ability to showcase diverse shapes, materials, and lighting effects. The table provided a sturdy geometric form, the coffee cups introduced smaller, more detailed objects, the vase of flowers added an organic touch, and the hanging lamp served as both overhead interest and a light source. Together, these elements created an engaging scene while enabling me to experiment with multiple primitive shapes and textures.

### Design Approach and Process

From a programming standpoint, I adopted a modular and iterative design process. To optimize performance and ensure shorter rendering times, I used low-polygon versions of each object. Basic primitives—cylinders for table legs and vase bodies, boxes for table tops, and spheres for flower buds—were employed to maintain a manageable polygon count. I introduced textures such as wood grain for the table and porcelain for the cups, which added surface variety without complicating geometry.

For lighting, I implemented the Phong lighting model, focusing on ambient, diffuse, and specular components to enhance realism. This lighting setup allowed the scene to visually differentiate materials like wood and metal based on how they reflect light. For example, the table’s wood grain texture absorbs more diffuse light, while the hanging lamp reflects specular highlights.

### Navigation and Camera Controls

To ensure an intuitive user experience, I designed a free-fly camera system driven by keyboard and mouse inputs. Users can move forward, backward, left, and right with the W, S, A, and D keys, and adjust vertical movement with Q and E. This familiar first-person navigation scheme makes the controls intuitive for users.

Mouse movements control camera orientation, with horizontal motion adjusting the yaw angle (left or right) and vertical motion adjusting the pitch angle (up or down). The scroll wheel adjusts the camera’s movement speed, allowing precise examination of details or broader surveys of the scene. Additionally, toggling between perspective and orthographic projections (with P and O keys) demonstrates the mathematical differences in rendering spatial relationships.

### Modularity and Custom Functions

A modular approach was central to my development. I created separate classes for different responsibilities:
- **SceneManager**: Handles loading and drawing objects. Functions like `RenderTableTop()`, `RenderCoffeeCup()`, and `RenderVase()` encapsulate object-specific transformations, materials, and textures.
- **ViewManager**: Manages camera behavior, user inputs, and projection toggling. Functions like `ProcessKeyboardEvents()` and `PrepareSceneView()` ensure logical organization of tasks.

This modularity ensured code readability, simplified debugging, and facilitated future expansions or collaborations.

## How Do I Approach Designing Software?

I approach software design by focusing on user needs, modularity, and scalability. By breaking down complex problems into smaller components, I ensure that each part is independently functional and easily maintainable. I rely on visual prototypes and diagrams to clarify ideas and guide development.

### What New Design Skills Did This Project Help Me Craft?

This project honed my ability to:
- Implement realistic lighting using the Phong model.
- Design modular systems for rendering and navigation.
- Balance performance optimization with visual fidelity.
- Create reusable material definitions to simplify rendering pipelines.

### What Design Process Did I Follow?

My design process included:
1. **Requirement Analysis**: Understanding the need for a visually appealing yet optimized 3D scene.
2. **Prototyping**: Building basic shapes and lighting setups to test core functionality.
3. **Iteration**: Refining textures, lighting, and camera controls through repeated testing.
4. **Validation**: Ensuring the scene met performance and usability benchmarks.

### How Could My Design Tactics Be Applied in Future Work?

The tactics of modularity, iterative improvement, and focusing on user interaction are applicable to any software project. These strategies ensure adaptability, maintain high-quality standards, and provide a user-centric approach to development.

## How Do I Approach Developing Programs?

I focus on structured development with iterative testing. Starting with a strong foundation of core functionality, I gradually build complexity while maintaining code clarity and organization. Debugging and user feedback are integral to my development cycle.

### What New Development Strategies Did I Use?

This project introduced me to:
- Advanced lighting techniques (ambient, diffuse, specular).
- Real-time shader programming for dynamic visual effects.
- Incremental scene rendering with low-polygon optimizations.
- Debugging through visual feedback and modular testing.

### How Did Iteration Factor Into Development?

Iteration was a critical part of my development process. Each stage of the project—lighting, materials, camera controls—was refined based on testing and feedback. This approach ensured a polished final product.

### How Has My Approach to Developing Code Evolved?

Throughout the milestones, I’ve evolved to prioritize clarity, scalability, and reusability. Writing modular code has become a cornerstone of my methodology, enabling me to adapt to changes and collaborate more effectively.

## How Can Computer Science Help Me Reach My Goals?

Computer science equips me with tools to solve complex problems and create innovative solutions. It empowers me to automate processes, visualize data, and develop interactive applications that have real-world impact.

### How Do Computational Graphics and Visualizations Provide New Knowledge and Skills for My Educational Pathway?

They enhance my understanding of mathematical transformations, real-time rendering, and performance optimization. These skills are essential for advanced studies in areas like virtual reality, game development, and scientific visualization.

### How Do Computational Graphics and Visualizations Provide New Knowledge and Skills for My Professional Pathway?

They prepare me for industries that demand expertise in 3D modeling, rendering, and interactivity. Whether creating immersive simulations or developing user-friendly interfaces, these skills are invaluable in delivering cutting-edge solutions.

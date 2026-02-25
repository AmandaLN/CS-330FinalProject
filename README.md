# CS-330FinalProject
Creation of a 3D scene based on a 2D image.

<img width="1042" height="779" alt="Screenshot 2026-02-21 144650" src="https://github.com/user-attachments/assets/5708b00a-7795-43f6-ba9e-ab6712f2dff2" />

<img width="910" height="680" alt="Screenshot 2026-02-21 144711" src="https://github.com/user-attachments/assets/d538ae27-98ef-4bd9-b4b5-8c53793ae728" />

<img width="1031" height="818" alt="image" src="https://github.com/user-attachments/assets/b7e16f4e-a25d-4c8e-8429-873aa1cbb788" />


How do I approach designing software?
  Decomposition: Breaking a complex visual scene into its fundamental geometric primitives (cubes, cylinders, planes). Abstraction: Using classes or functions to handle repetitive tasks, such as mesh generation or texture loading, so the main logic remains clean. User-Centricity: Designing the "Camera" and input systems so the user can interact with the software intuitively.

What new design skills has your work on the project helped you to craft?
  Some new design skills I acquired were learning and working with OpenGL and 3D graphics. Specific skills include: 
Spatial Reasoning: Learning to position, rotate, and scale objects within a coordinate system ($x, y, z$).
Visual Optimization: Understanding how to use Lighting (Ambient, Diffuse, Specular) and Texturing to create realism without overloading the GPU.

What design process did you follow for your project work?
  The design process I followed was a multi-step iterative process:
Reference Analysis: I started with a 2D image and identified the "anchor" objects and light sources.
Primitive Modeling: I mapped each real-world object to a geometric shape (e.g., a table as a flattened cube).
Coordinate Mapping: I manually calculated the vertices and indices needed to define these shapes in 3D space.
Aesthetic Layering: Once the "grey-box" models were placed, I applied textures and adjusted the virtual camera to match the original perspective.

How could tactics from your design approach be applied in future work?
  The tactics of decomposition and reference analysis are universal in software engineering. In future projects I can use modularizing complex systems and visualizations. This allows the break down of a large project into smaller manageable peices and using a reference image.  

How do I approach developing programs?
  The "Build and Run" Cycle: I write small segments of code—such as a single shape's vertices—and immediately compile/run to verify the output. This makes debugging much easier than writing 500 lines at once.
Documentation and Comments: I use comments to map out the logic of the graphics pipeline, which helps in maintaining the code and keeping track of coordinate transformations.

What new development strategies did you use while working on your 3D scene?
  This project introduced me to several specialized stragegies. They include:
GPU-Side Logic: I learned to move heavy calculations into Vertex and Fragment Shaders using GLSL, which is a significant shift from standard CPU-only programming.
Memory Management (VBOs/VAOs): I implemented strategies to package data into Vertex Buffer Objects and Vertex Array Objects to communicate efficiently with the hardware.
Debugging via Visual Feedback: Unlike standard console apps where you check print statements, I learned to debug by observing the screen (e.g., "if the object is black, the normals or light calculations are likely wrong").

How did iteration factor into your development?
  I used the "grey box" interation to help me render simple shapes for spatial layout. Then the iteration of texture and lighting. This made it easy to debug and read code. 

How can computer science help me in reaching my goals?
  Computer science will help me reach my goals by being a toolkit for problem solving. For example, this has helped me think logically, bridge the gap for non technical persons, and handle data more efficiently. 

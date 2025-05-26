This project uses Generative AI with Stable Diffusion + ControlNet to generate realistic and styled interior designs from room images and text prompts. It enables users (designers, homeowners, architects) to visualize interior design variations easily and instantly.

Project Overview
Interior design often requires expensive software, expert skills, and a lot of imagination. This tool simplifies the process by allowing users to:

Upload a photo of a room

Enter a design prompt (e.g., "Modern luxury living room")

Automatically generate a new interior design that retains the structure but applies the new style

Powered by ControlNet, this model ensures that the room's structure is preserved while applying the visual style described by the user.

🧠 How It Works
Upload Room Image: A photo of any interior space (e.g., bedroom, living room).

Edge Detection: The image is processed using Canny edge detection to extract the structure.

Text Prompt: A natural language prompt guides the new design.

Stable Diffusion + ControlNet: Generates a new, styled version of the room image using both the edge map and prompt.

Interactive UI: Built with Gradio for ease of use.

Example Use Case
Original Room ➝ Canny Edge Detection ➝ Prompt: "Modern Scandinavian Living Room" ➝ AI-Generated Interior Design

🔧 Tech Stack
Tool/Library	Purpose
Stable Diffusion	Base generative model
ControlNet	Controls image structure via edge detection
OpenCV	Canny edge detection
Gradio	Interactive web UI
PyTorch	Deep learning framework
Diffusers	Model hub and inference tools (HuggingFace)

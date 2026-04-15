<!-- ===================== HEADER ===================== -->
<h1 align="center">🎲 Roll-a-Ball Game (Unity)</h1>

<p align="center">
  <b>Unity Game Development Project</b><br/>
  Basic Physics • Player Control • Camera Follow
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Unity-3D-black?logo=unity">
  <img src="https://img.shields.io/badge/C%23-Scripting-blue?logo=csharp">
  <img src="https://img.shields.io/badge/Game-Arcade-green">
</p>

<hr/>

<hr/>

<!-- ===================== INTRO ===================== -->
<h2>📖 Introduction</h2>

<p>
This is a simple <b>Roll-a-Ball game</b> built using Unity.  
The player controls a rolling ball to collect rotating objects in the scene.
</p>

<p>
This project demonstrates fundamental Unity concepts:
</p>

<ul>
  <li>Physics-based movement (Rigidbody)</li>
  <li>Keyboard input handling</li>
  <li>Camera follow system</li>
  <li>Object rotation</li>
  <li>Collision detection</li>
</ul>

<hr/>

<!-- ===================== FEATURES ===================== -->
<h2>🎮 Features</h2>

<div style="background-color:#f6f8fa; padding:12px; border-radius:8px; margin-bottom:10px;">
✔ Smooth ball movement using physics
</div>

<div style="background-color:#f6f8fa; padding:12px; border-radius:8px; margin-bottom:10px;">
✔ Camera follows player
</div>

<div style="background-color:#f6f8fa; padding:12px; border-radius:8px; margin-bottom:10px;">
✔ Rotating collectible objects
</div>

<div style="background-color:#f6f8fa; padding:12px; border-radius:8px; margin-bottom:10px;">
✔ Basic collision detection
</div>

<div style="background-color:#f6f8fa; padding:12px; border-radius:8px; margin-bottom:10px;">
✔ Simple and clean gameplay
</div>

<hr/>

<!-- ===================== GAMEPLAY ===================== -->
<h2>🕹️ Gameplay</h2>

<table>
<tr><th>Action</th><th>Control</th></tr>
<tr><td>Move Ball</td><td>Arrow Keys / WASD</td></tr>
<tr><td>Objective</td><td>Collect all rotating objects</td></tr>
</table>

<hr/>

<!-- ===================== PROJECT STRUCTURE ===================== -->
<h2>📂 Project Structure</h2>

<pre>
Assets/
│
├── Custom Font/
├── Input/
├── Materials/
├── Prefabs/
├── Scenes/
├── Scripts/
│   ├── CameraController.cs
│   ├── PlayerController.cs
│   ├── Rotator.cs
│   └── SimHandMove.cs
│
├── Templates/
└── TextMesh Pro/
</pre>

<hr/>

<!-- ===================== IMPLEMENTATION ===================== -->
<h2>⚙️ Implementation Details</h2>

<h3>🎯 Player Controller</h3>
<ul>
  <li>Uses <b>Rigidbody</b> for realistic physics movement</li>
  <li>Applies force based on user input</li>
</ul>

<h3>🎥 Camera System</h3>
<ul>
  <li>Follows the player smoothly</li>
  <li>Keeps a fixed offset from the player</li>
</ul>

<h3>🔄 Rotating Objects</h3>
<ul>
  <li>Objects rotate continuously using script</li>
  <li>Improves visual feedback</li>
</ul>

<h3>🎮 Input Handling</h3>
<ul>
  <li>Supports keyboard input (WASD / Arrow keys)</li>
</ul>

<h3>💥 Collision Detection</h3>
<ul>
  <li>Detects player collisions with collectibles</li>
  <li>Triggers object removal</li>
</ul>

<hr/>

<!-- ===================== BUILD ===================== -->
<h2>🛠️ Build Instructions</h2>

<ol>
  <li>Open the project in Unity</li>
  <li>Go to <b>File → Build Settings</b></li>
  <li>Select target platform (PC recommended)</li>
  <li>Click <b>Add Current Scene</b></li>
  <li>Click <b>Build</b></li>
</ol>

<p>
After building, run the generated <b>.exe</b> file to play the game.
</p>

<hr/>

<!-- ===================== REQUIREMENTS ===================== -->
<h2>📋 Requirements</h2>

<ul>
  <li>Unity (recommended: 2020+)</li>
  <li>Basic C# knowledge</li>
</ul>

<hr/>

<!-- ===================== AUTHOR ===================== -->
<h2>👨‍💻 Author</h2>

<p>
<b>Name:</b> Phat <br/>
<b>Project:</b> Roll-a-Ball Unity Game  
</p>

<hr/>

<!-- ===================== FOOTER ===================== -->
<p align="center">
  ⭐ If you like this project, give it a star on GitHub!
</p>

<!-- ===================== HEADER ===================== -->
<h1 align="center">🎲 Roll-a-Ball Game (Unity)</h1>

<p align="center">
  <b>Unity Game Development Project</b><br/>
  Basic Physics & Player Control
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Unity-3D-black?logo=unity">
  <img src="https://img.shields.io/badge/C%23-Scripting-blue?logo=csharp">
  <img src="https://img.shields.io/badge/Game-Type%20Arcade-green">
</p>

<!-- ===================== INTRO ===================== -->
<h2>📖 Introduction</h2>

<p>
This project is a simple <b>Roll-a-Ball game</b> developed using Unity.  
The objective of the game is to control a rolling ball, collect objects, and complete the level.
</p>

<p>
This project demonstrates fundamental concepts in Unity such as:
</p>

<ul>
  <li>Physics-based movement</li>
  <li>Player input handling</li>
  <li>Camera follow system</li>
  <li>Object rotation</li>
  <li>Collision detection</li>
</ul>

<hr/>

<!-- ===================== FEATURES ===================== -->
<h2>🎮 Features</h2>

<style>
.feature-box {
  background-color: #f6f8fa;
  padding: 12px;
  border-radius: 8px;
  margin-bottom: 10px;
}
</style>
- ✔ Smooth ball movement using physics
- ✔ Camera follows player
- ✔ Rotating collectible objects
- ✔ Basic collision detection
- ✔ Simple and clean gameplay
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

<h3>1. Player Controller</h3>
<ul>
  <li>Controls ball movement using <b>Rigidbody physics</b></li>
  <li>Applies force based on player input</li>
</ul>

<h3>2. Camera System</h3>
<ul>
  <li>Camera follows the player smoothly</li>
  <li>Maintains relative position to the ball</li>
</ul>

<h3>3. Rotating Objects</h3>
<ul>
  <li>Objects rotate continuously using script</li>
  <li>Creates dynamic visual effect</li>
</ul>

<h3>4. Input System</h3>
<ul>
  <li>Handles keyboard input (WASD / Arrow Keys)</li>
</ul>

<h3>5. Collision Detection</h3>
<ul>
  <li>Detects when player touches collectible objects</li>
  <li>Triggers game logic (e.g., destroy object)</li>
</ul>

<hr/>

<!-- ===================== BUILD ===================== -->
<h2>🛠️ Build Instructions</h2>

<ol>
  <li>Open project in Unity</li>
  <li>Go to <b>File → Build Settings</b></li>
  <li>Select platform (PC recommended)</li>
  <li>Click <b>Add Current Scene</b></li>
  <li>Click <b>Build</b></li>
</ol>

<p>
Run the generated executable file to play the game.
</p>

<hr/>

<!-- ===================== REQUIREMENTS ===================== -->
<h2>📋 Requirements</h2>

<ul>
  <li>Unity (recommended version: 2020+)</li>
  <li>Basic knowledge of C#</li>
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
  ⭐ If you like this project, give it a star!
</p>

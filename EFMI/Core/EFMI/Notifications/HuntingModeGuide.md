Debugging:
To enable ini errors output, see XXMI Launcher > Settings > EFMI > Mute Warnings
To enable built-in debugger, remove ';' before 'include = Core/Debugger/Debugger.ini' in d3dx.ini 
[SHIFT]+[F12]: Toggle Debugger (refer to Core/Debugger/Debugger.ini)

Hunting Mode Hotkeys (NumPad):
[0]: Toggle Hunting Mode (make sure to Enable Hunting in XXMI Launcher > Settings > EFMI)
[+]: Reset hunting (reduces number of buffers/shaders to cycle)
[F11]: Create Frame Dump
Hint: Lower resolution to lower framedump size

Buffer Hunting (NumPad):
Cycle VB (Vertex Buffers): Prev: [/], Next: [*], Copy Hash: [-]
Cycle IB (Index Buffers): Prev: [7], Next: [8], Copy Hash: [9]

Shader Hunting (NumPad):
Cycle VS (Vertex Shaders): Prev: [4], Next: [5], Copy Hash: [6]
Cycle PS (Pixel Shaders): Prev: [1], Next: [2], Copy Hash: [3]
Cycle CS (Compute Shaders): Prev: [.]+[1], Next: [.]+[2], Copy Hash: [.]+[3]
Note: Shader dumping is disabled by default, see XXMI Launcher > Settings > EFMI > Dump Shaders

Refer to XXMI Launcher > Settings > EFMI and d3dx.ini for more details

Press CTRL+F12 to hide this message
# UnityGGPO

An interop DLL of the ggpo library that works with Unity 3D, and a port of VectorWar to Untity.

Build:
- run build_windows.cmd to build the solution.
- build and run the INSTALL project to copy the built DLL into the Unity Plugin folder.

Two ways to use:
- Direct access to the GGPO library using the GGPO class requires unsafe calls and IntPtr function pointers.
- Use the GGPO.Session helper class to have safe access using Unity's native collections library and delegates.

VectorWar
- Run the VectorWar.scene.
- Left UI panel is your player index and the connection list.
- Click Start Session

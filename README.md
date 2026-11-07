# Hi, I'm Grzegorz (AndrzejKebab) 👋

**Unity / C# developer working with DOTS: ECS, Burst, Jobs and Netcode for Entities.**
Most of what I build is voxel tech: world generation, chunk pipelines, rendering, and the editor tools around them.

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/@AndrzejKebab)

---

## 🔨 Currently working on

**VoxelGame** *(private, in development)*. A voxel game on Unity DOTS with **server-authoritative multiplayer** (Netcode for Entities, dedicated-server builds).
- **World generation** with a geology layer: continent and plate lattices, geologic provinces, climate-driven biomes, erosion and continent movement simulation
- **Data-driven content packs** in JSON (blocks, block states and shapes, features, items), built for modding
- **Burst-compiled hot paths and zero-GC steady state** as design targets, with a separate Common / Client / Server assembly split

**FastNoiseGraph** *(private)*. A node-based editor for FastNoise2 noise trees, built on Unity Graph Toolkit. It exports graphs to the JSON the VoxelGame terrain loader reads.

**UniForge** *(private)*. My collections and utility package: native collections (octree, quadtree, `BlobHashMap`, heaps), span and LINQ-style extensions, and math helpers on `Unity.Mathematics`.

---

## 🧩 Public projects

| Project | What it is |
|---|---|
| **[AutoBuildTool](https://github.com/AndrzejKebab/AutoBuildTool)** | Unity editor tool for one-click client and server builds: `BuildProfile` discovery, semantic version bumping, build retention, and post-build folder/file trees |
| **[Minecraft-like Game](https://github.com/AndrzejKebab/Minecraft-like-Game)** | Earlier voxel project comparing System.Threading, Jobs + Burst and ECS. Later moved to GPU-driven chunk rendering and priority-queued chunk builds |
| **[Unity-JobScheduler](https://github.com/AndrzejKebab/Unity-JobScheduler)** | Coordinates Unity Jobs and their completion, with UniTask integration |
| **[UnityVoxelMeshGPU](https://github.com/AndrzejKebab/UnityVoxelMeshGPU)** | Fork: compute-shader voxel meshing, comparing `DrawProceduralIndirect` against `RenderPrimitivesIndirect` and `RenderPrimitivesIndirectIndexed` |
| **[Enhanced Procedural Terrain Generation](https://github.com/AndrzejKebab/Enhanced-Procedural-Terrain-Generation)** | Noise-based terrain module with parallel generation |

<details>
<summary>Older projects</summary>

- **[Baldur-Gates-4](https://github.com/AndrzejKebab/Baldur-Gates-4)**: party control, Command Pattern actions, save/load
- **[Group Project / Tech Demo](https://github.com/AndrzejKebab/Group-Project-Tech-Demo)**: game jam, team lead and main programmer
- **[Shooter](https://github.com/AndrzejKebab/Shooter)**: projectile and hit-detection system with target filtering

</details>

---

## 🧰 Tech stack

**Languages & engine**<br>
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![HLSL](https://img.shields.io/badge/HLSL-5E5E5E?style=for-the-badge)

**Unity tech**<br>
![ECS](https://img.shields.io/badge/ECS%20%2F%20DOTS-lightgrey?style=for-the-badge)
![Burst](https://img.shields.io/badge/Burst-lightgrey?style=for-the-badge)
![Jobs](https://img.shields.io/badge/Jobs-lightgrey?style=for-the-badge)
![Netcode](https://img.shields.io/badge/Netcode%20for%20Entities-lightgrey?style=for-the-badge)
![URP](https://img.shields.io/badge/URP-lightgrey?style=for-the-badge)
![Graph Toolkit](https://img.shields.io/badge/Graph%20Toolkit-lightgrey?style=for-the-badge)

**Libraries**<br>
![FastNoise2](https://img.shields.io/badge/FastNoise2-lightgrey?style=for-the-badge)
![UniTask](https://img.shields.io/badge/UniTask-lightgrey?style=for-the-badge)
![ZLogger](https://img.shields.io/badge/ZLogger-lightgrey?style=for-the-badge)
![Addressables](https://img.shields.io/badge/Addressables-lightgrey?style=for-the-badge)

**Tools**<br>
![Rider](https://img.shields.io/badge/Rider-000000?style=for-the-badge&logo=rider&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white)

---

## 🚀 Want to help?

If you like where a project is going and want to contribute (code, tests or docs), open an issue describing what you'd improve and I'll reply.

*Thanks for stopping by. I'm always iterating.*

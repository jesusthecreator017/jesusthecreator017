# Jesus Gonzalez
**Computer Science @ UCF (Fall 2027) | Graphics Programmer**

I write real-time renderers, mostly in Rust and C, and I'm happiest when a technique has to fit hard constraints: a compute budget, a frame time, or a handheld from 2011. Lately that means foliage. My grass renderer generates every blade on the GPU each frame, and I ported it to the Nintendo 3DS, where the GPU has no compute shaders at all.

Outside graphics, I've built embedded firmware, real-time backends, and optimization tools, and I work on the SunPass tolling platform as a Software Engineer Intern at Florida's Turnpike Enterprise.

---

## Graphics Programming

| Project | Stack | Description |
|---------|-------|-------------|
| [grass-test](https://github.com/jesusthecreator017/grass-test) | Rust, wgpu, WGSL | Real-time procedural grass after Sucker Punch's *Ghost of Tsushima* GDC talk. A compute shader generates, frustum-culls, and LODs every blade per frame, and indirect draws render them with no vertex buffers. Shadow mapping, 4x MSAA, glTF skeletal animation, and a live editor with shader hot reload. |
| [grass-test-3ds](https://github.com/jesusthecreator017/grass-test-3ds) | C, citro3d, PICA200 assembly | The same meadow on real Nintendo 3DS hardware. Blades hash from grid cells at startup, the CPU bends them for wind and a player pusher, and a hand-written PICA200 vertex shader does transform and fog. 4,774 blades at 30 FPS on an original 3DS. |
| [Volante](https://github.com/jesusthecreator017/Volante) | Rust, wgpu, WebAssembly, Embassy, PyTorch | Badminton analytics platform: ESP32-S3 sensor firmware streaming IMU data at 500 Hz over BLE, a 10-stroke classifier, and a PPO reinforcement-learning arena with matches rendered in 3D by a wgpu engine compiled to WebAssembly. |

---

## Other Projects

| Project | Stack | Description |
|---------|-------|-------------|
| [TermText](https://github.com/jesusthecreator017/TermText) | Go, PostgreSQL, WebSockets, Docker | Terminal-native real-time chat with a Bubble Tea TUI, end-to-end encrypted DMs, full-text search, and Prometheus metrics, deployed to Fly.io. |
| [DronePath](https://github.com/jesusthecreator017/knighthacks2025) | Python, Google OR-Tools, Shapely, Plotly | Multi-drone route planner for power line inspection. **3rd of 188 teams** in the NextEra Energy challenge at Knight Hacks 2025. |

---

## Highlights
- **Knight Hacks 2025, NextEra Energy Challenge:** 3rd place of 188 teams (DronePath)
- **ShellHacks Finalist:** accessibility-focused Chrome extension
- **Knight Hacks:** Software Engineer on Forge, the club's open-source TypeScript monorepo

---

## Tech Stack

**Graphics:** wgpu, WGSL, compute shaders, GPU-driven rendering, shadow mapping, glTF, citro3d, PICA200 assembly

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![WGPU](https://img.shields.io/badge/WGPU-5A3FC0?style=flat&logo=webgpu&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat&logo=webassembly&logoColor=white)
![Nintendo 3DS](https://img.shields.io/badge/Nintendo%203DS-D12228?style=flat&logo=nintendo3ds&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Connect
**Email:** Jesus.R.Gonzalez107@gmail.com
**LinkedIn:** [linkedin.com/in/jesusg107](https://linkedin.com/in/jesusg107)
**Portfolio:** [my-portfolio-sigma-tan-63.vercel.app](https://my-portfolio-sigma-tan-63.vercel.app/)

## Codeberg
For my 100% artisinal projects visit me on [codeberg.org/jesusthecreator](https://codeberg.org/jesusthecreator)

# KiCad 项目模板库（Project Template for KiCad）

本仓库收录了一套标准化的 KiCad 项目模板结构，适用于多人协作、统一文档结构、提升工程可维护性等场景。  
已适配 macOS 与 Windows 平台，可直接用于 KiCad 9 及以上版本。

---

### 📁 模板结构说明

```plaintext
├── Lib/                       # 封装库目录
│   ├── lib_sym/              # 原理图库（.lib/.kicad_sym）
│   ├── lib_fp/               # 封装库（.pretty）
│   └── lib_3d/               # 3D模型文件（.step/.wrl）
├── Project/                  # 项目文件（.kicad_pro/.kicad_sch/.kicad_pcb 等）
├── Outputs/                  # 输出文件目录
│   ├── BOM/                  # 物料清单文件
│   ├── PDF/                  # 原理图/PCB PDF 导出
├── Fabrication/              # 生产文件（Gerber/DXF/Drill 等）
│   ├── Gerber/
│   ├── Drill/
│   ├── DXF/
│   ├── Stackup/
│   └── FabNotes/
├── Notes/                    # 说明文档/图像资料
│   └── Images/
└── README.md                 # 项目说明文档

## 

### 特别声明：

该模板的基于 Nguyen Vincent (https://github.com/nguyen-v/KiCAD_Templates) 的模板进行修改，他在YouTube频道已进行详细的模板介绍，我只是根据个人的使用场景对目录架构进行优化，并分享个人使用思路，请支持原作者。
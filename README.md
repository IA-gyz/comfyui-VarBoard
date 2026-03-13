# 🎛️ ComfyUI Variables Board V 0.9

**Variables Board** is a floating control center for your [ComfyUI](https://github.com/comfyanonymous/ComfyUI) workflows. It allows you to centralize every parameter—from seeds and integers to samplers and strings—into a sleek, customizable overlay that stays accessible as you navigate your workspace.
![pic1](assets/varBoard02.png)
**** README IS A WORK IN PROGRESS ****

What you need to know:


## 🛠️ Installation

REQUIREMENTS : A working ComfyUI... That's all


1. Navigate to your ComfyUI `custom_nodes` directory:
   ```bash
   cd ComfyUI/custom_nodes/
   ```
2. Clone this repository:
   ```bash
   git clone https://github.com/IA-gyz/comfyui-VarBoard.git
   ```
   Or download and extract the zip to your ComfyUI `custom_nodes` directory
   
4. Restart ComfyUI and refresh your browser.

---

## 🚀 How to Use

![setup](https://github.com/user-attachments/assets/7b268b87-8e8b-4d81-a187-f2a9e0bb2414)

### 1. Place the Anchor
Search for `Variables Board: Panel` in the node menu, or search for VB (VarBoard works too). This node acts as the "canvas anchor" for your variables board. You only need one per workflow.

### 2. Add Variables
There are two ways to add variables to your board:
- **Batch Mode**: Click the `＋ Add` button in the board header to open the dialog.
- **Manual Mode**: Add individual nodes like `VB_Int`, `VB_Float`, or `VB_Seed` and they will automatically appear on the board.

### 3. Connect to Nodes
Connect the outputs of your VB nodes to the inputs of your target nodes (e.g., connect a `VB_Seed` output to the `seed` input of a KSampler).

### 4. Customize
Click the `⚙` icon on the board header to open the **Panel Settings** flyout for various tweaking options.
---

## 📐 Design Philosophy

Variables Board was designed to solve "canvas fatigue." Instead of hunting for nodes across a massive graph, you bring the controls to you. It respects the ComfyUI aesthetic while injecting a somewhat "Pro-tool" feel.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for feature requests.

*Created with ❤️ for the ComfyUI Community.*

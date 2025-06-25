# 🍩 3D Printed Donut
Blender to Creality K1C (3D Printing)

This project documents my first 3D printing project: a stylised donut modeled in Blender, prepared using the 3D Print Toolbox add-on, sliced with Creality Print, and printed on a Creality K1C using Hyper PLA filament.

---

## 🧰 Tools & Setup

- **Modeling Software:** Blender 4.2.3 LTS
- **3D Printer:** Creality K1C
- **Filament:** Hyper PLA, 1.75mm
- **Slicer Software:** Creality Print v5.x
- **Export Formats:** `.stl` and `.gcode`
- **Supports Enabled:** Yes (touching build plate)
- **Print Settings:**  
  - Layer height: 0.2 mm  
  - Infill: 15% (Grid pattern)  
  - Top/Bottom layers: 5/3  
  - Brim: enabled (for bed adhesion)  
  - Estimated print time: ~53 minutes  

---

## 🧩 Blender Setup

The donut model is composed of two meshes:
- **Base:** Torus shape sculpted and smoothed
- **Icing:** Sculpted top surface with minor overhangs

Steps taken:
1. Applied all transforms (`Ctrl+A`)
2. Enabled the 3D Print Toolbox
3. Ran **Check All** for non-manifold, intersect faces, and thin walls
4. Used **Make Manifold** to resolve minor mesh issues
5. Exported `.stl` with:
   - ✅ Apply Modifiers
   - ✅ Selection Only
   - ✅ Scene Scale

---

## 🖨️ Printing Workflow

1. Imported `.stl` into Creality Print
2. Scaled and positioned on print bed
3. Enabled **supports** touching buildplate
4. Used 15% infill with Grid pattern
5. Sliced to `.gcode` and saved to USB
6. Printed on the Creality K1C with standard nozzle
7. Print completed successfully on the first try 🎉

---

## 📸 Screenshots

| Blender Preview | Slicer Import | Print Preview | Final Print |
|-----------------|---------------|----------------|--------------|
|![Screenshot 2025-06-26 at 01 08 02](https://github.com/user-attachments/assets/64b81350-cf62-4b15-9467-1346c913f0f7) |![![Screenshot 2025-06-26 at 01 10 00](https://github.com/user-attachments/assets/9a37b7c7-d792-4cd3-8e67-c20dc4bca90e) | ![Screenshot 2025-06-26 at 01 10 28](https://github.com/user-attachments/assets/b003911c-08a3-4848-984a-a3d80b7f1f45)| ![Donut_3D_Print](https://github.com/user-attachments/assets/c1f012cb-446e-4c4d-87ca-a02a5e55bedd)|



---

## 💡 Lessons Learned

- Always run mesh validation (3D Print Toolbox saved me!)
- Applying all transforms (`Ctrl + A`) in Blender is **critical**
- Exporting modifiers is important — leave **Apply Modifiers** on
- Green support in slicer preview doesn’t always mean “needed”
- PLA doesn’t need glue on a clean PEI bed but a brim helps

---

## 🔁 Next Steps

- Split the icing and base into two STL files for multi-material printing
- Add food-style texture paint for realism
- Try painting the PLA model or printing in multiple colours using Creality CFS

---

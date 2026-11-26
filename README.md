# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.

## AIM

To sketch the given drawing with dimensions using fusion 360 tool.

## REQUIREMENTS

  1. Autodesk fusion 360
  2. Windows 10
  3. 16 GB of RAM (integrated graphics recommend 2 GB or more)
  4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
  
## PROCEDURE
1. Launch Software: Open Autodesk Fusion 360 on the computer and create a new design file.
2. Set Units: Verify that the document units are set to millimetres (mm) in the browser tree.
3. Start Sketch: Click Create Sketch and select the horizontal XY Plane as the sketching plane.
4.
5. <img width="547" height="307" alt="Screenshot 2026-10-12 105818" src="https://github.com/user-attachments/assets/56cfa3c3-8917-4153-892c-ed5da8a58808" />

6. 
7. Create Base Circle: Draw a central construction circle at the origin (0,0) to define the pitch circle for the internal splines.
8. Draw Internal Spline Teeth: Draw a small circle on the perimeter of the central pitch circle to represent one internal spline lobe.
9. Pattern Internal Splines: Use the Circular Pattern tool to replicate the spline circle around the center point (6 instances) to form the 6-lobe splined bore.
10. Trim Inner Profile: Use the Trim tool to remove overlapping inner segments so that the central splined hole forms a single clo
11.
12. <img width="488" height="360" alt="Screenshot 2026-10-08 210945" src="https://github.com/user-attachments/assets/fff64144-d8cd-4ee3-8d33-a51190cf6922" />
sed loop.
13. Create Top Mounting Lug: Draw two concentric circles directly above the origin along the vertical axis to form the outer boss and inner through-hole of the top lug.
14. Create Lower Mounting Lugs: Draw three sets of smaller concentric circles positioned below the center (left, bottom-center, and bottom-right) according to the required radial distances and angles.
15. Connect Outer Profile with Tangent Arcs: Use the 3-Point Arc or Tangent Arc tool to draw smooth, inward-curving arcs connecting the outer circles of the top lug and the lower lugs
16.
17. .<img width="537" height="562" alt="Screenshot 2026-10-15 105121" src="https://github.com/user-attachments/assets/58c19642-65d1-4487-aa6c-fc9d49bd905f" />

18. Apply Tangent Constraints: Apply the Tangent constraint between every connecting arc and its adjacent outer lug circles to ensure smooth, continuous transitions.
19. Trim Excess Geometry: Use the Trim tool to clean up any intersecting construction lines or overlapping circle segments along the outer boundary.
20. Verify Closed Profile: Confirm that the entire main body—excluding the central splined bore and the four outer mounting holes—highlights as a single closed sketch profile, then click Finish Sketch
21.
22. .<img width="471" height="217" alt="Screenshot 2026-10-22 110805" src="https://github.com/user-attachments/assets/11707819-49fa-4d4c-acdc-a1d820ecc510" />

23. Extrude Main Body: Select the Extrude tool, choose the closed main body profile, and extrude it upward to the required uniform thickness.
24. Verify Holes: Ensure that the central splined bore and the four outer mounting holes remain completely cut through the extruded solid body.
25. Inspect Edges & Surfaces: Rotate the model using the ViewCube to verify that all curved walls are smooth and tangential.
26. Apply Appearance (Optional): Open the Appearance menu (A) and assign a dark metallic or anodized steel finish to match the visual representation.
27. Final Verification & Save: Inspect the model in Top, Front, Right, and Isometric views to confirm geometric accuracy, then save the file in the native .f3d forma


## SKETCHS
![image](https://user-images.githubusercontent.com/113594316/198208087-87ed794e-5f1c-4583-82e0-f29699dfc305.png)

## OUTPUT
<img width="805" height="602" alt="Screenshot 2026-10-05 100949" src="https://github.com/user-attachments/assets/a9c83bc6-5340-461e-a9fa-f05a30b8dacb" />

<img width="1012" height="708" alt="Screenshot 2026-10-05 101014" src="https://github.com/user-attachments/assets/b74f86ec-f463-445a-991b-32c469481278" />

## RESULT
Thus the given sketch is drawn and drafted using fusion 360 tool.

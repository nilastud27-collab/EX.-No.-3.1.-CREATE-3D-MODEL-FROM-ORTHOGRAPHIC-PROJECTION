# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE: 02.11.2026

## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

## Step 1: Initial Setup 
1. Open Autodesk Fusion 360 and start a new design (File > 
New Design). 
2. In the Browser tree on the left, expand Document Settings 
and verify that the active units are set to Millimeters (mm).

## Step 2: Sketch the U-Shaped Fork Profile (Top View) 
1. Select Create Sketch and choose the XY Plane (Top plane). 
2. Use the Line tool (L) to draw the outer U-shaped boundary of 
the fork: 
○ Draw a vertical back edge of 40 mm ( 11 + 18 + 11𝑚𝑚)
○ From both ends, draw horizontal lines extending 52 mm to the left. 
○ From each left tip, draw inward vertical lines of 11 mm. 
○ From those endpoints, draw inward horizontal lines of 41 mm (52 − 11𝑚𝑚) to the right. 
○ Connect the two inner endpoints with a vertical line of 18 
mm to close the U-shape. 
3. Click Finish Sketch

<img width="597" height="381" alt="Screenshot 2026-11-19 234549" src="https://github.com/user-attachments/assets/b61f8c0e-b122-41f4-9e88-d7d2ba956757" />

## Step 3: Extrude the Fork Body 
1. Select the Extrude tool (E). 
2. Click the closed U-shaped profile. 
3. Set the Direction to Symmetric and Measurement to Whole 
Length. 
4. Enter a height of 32 mm and click OK.

<img width="571" height="442" alt="Screenshot 2026-11-19 234555" src="https://github.com/user-attachments/assets/3dcd28e8-1277-4911-904a-7b6d51a26e60" />

## Step 4: Cut the Through Hole 
1. Select Create Sketch and click on the outer flat side face of 
one of the fork arms. 
2. Select the Circle tool (C), hover over the outer semicircular 
edge to snap to its center point, and draw a circle of diameter 
16 mm (Ø16). 
3. Click Finish Sketch. 
4. Select Extrude (E), select the 16 mm circle profile, set 
Operation to Cut, set Extent Type to All (cutting through 
both fork arms), and click OK.

<img width="595" height="355" alt="Screenshot 2026-11-19 234601" src="https://github.com/user-attachments/assets/6af7931d-3f37-4076-91ea-d2ad24ea8c25" />
<img width="616" height="445" alt="Screenshot 2026-11-19 234611" src="https://github.com/user-attachments/assets/64cd6c6c-6082-4394-9b5c-29c7e138bdc0" />

## Step 5: Round the Fork Ends (Front View) 
1. Select the Fillet tool (F). 
2. Select all 4 vertical/horizontal outer edges at the left tips of 
the two fork arms (top-left and bottom-left edges of both 
prongs). 
3. Enter a radius of 16 mm (R16) to form the full semicircular 
ends and click OK. 
(Alternatively, you can select Create Sketch on the outer side 
face of a prong, draw the R16 arc, and Extrude > Cut the 
corners).

<img width="606" height="415" alt="Screenshot 2026-11-19 234618" src="https://github.com/user-attachments/assets/78b38494-83ab-4776-a4c1-67a741cc3ff0" />

## Step 6: Create the Cylindrical Shaft (Right View) 
1. Select Create Sketch and click on the back vertical face  of the fork block. 40𝑚𝑚 × 32𝑚𝑚
2. Draw a Circle (C) of diameter 18 mm (Ø18) at the exact 
center of the face ( 20𝑚𝑚 from the side edges and  16𝑚𝑚from the top/bottom edges). 
3. Click Finish Sketch. 
4. Select Extrude (E), select the 18 mm circle, set Operation to 
Join, enter a distance of 32 mm outward, and click OK.

<img width="572" height="463" alt="Screenshot 2026-11-19 234622" src="https://github.com/user-attachments/assets/dcbbb9eb-ce09-41c5-b195-ac2c16ac8d87" />
<img width="605" height="403" alt="Screenshot 2026-11-19 234627" src="https://github.com/user-attachments/assets/549f3698-eb85-481e-8618-23a093e4fa35" />

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198551872-276f8b80-bea8-4d4a-b2e8-bfdcd1e9d3cc.png)

## OUTPUT:
<img width="807" height="607" alt="Screenshot 2026-11-02 120412" src="https://github.com/user-attachments/assets/f5f625a3-92b7-47ed-9ac1-ac570375a5da" />
<img width="1017" height="717" alt="Screenshot 2026-11-02 120431" src="https://github.com/user-attachments/assets/c19eff73-b388-4be4-befb-9bb988555297" />

## RESULT:
Thus, 3D model is created from orthographic projection.
ILANILA VINNARASI.K.V
26017175
02.11.2026

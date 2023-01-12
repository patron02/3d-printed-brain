# 3d-printed-brain
On April 28, 2022 I got a T1 and T2 MRI scan done of my brain. I decided later that year to 3D print my brain. 

I used this instructable https://www.instructables.com/3D-print-your-own-brain/ and my own knowledge to develop a 3D model which I would later print. 

I used multiple applications to get the desired 3D model. I used MRIcroGL to convert my dicom MRI files to a compressed and zipped nifti file. 
<img width="740" alt="image" src="https://user-images.githubusercontent.com/69320369/212181672-6b4d1391-097f-47ad-a1f3-37ceb03557d9.png">

I then used freesurfer to generate a scan of my brain and uploaded it into meshlab where I edited and converted it into a useable STL. 
<img width="959" alt="image" src="https://user-images.githubusercontent.com/69320369/212182040-7b66059f-6e5d-4ca5-93af-ef3f1c3fcb18.png">

After I had roughly cleaned up the STL I used Autodesk Fusion360 and Blender to clean the mesh and remove all skull parts and extra pieces that freesurfer had accidentally scanned as part of my brain. 

Once the final mesh had been rendered I uploaded it to PrusaSlicer to prepare it for 3D printing.

48 hours of printing later it was finished in real size and weighed about 2.5 pounds which is roughly the weight of my brain. 

# 3d-printed-brain
On April 28, 2022 I got a T1 and T2 MRI scan done of my brain. I decided later that year to 3D print my brain. 

I used this instructable https://www.instructables.com/3D-print-your-own-brain/ and my own knowledge to develop a 3D model which I would later print. 

I used multiple applications to get the desired 3D model. MRIcroGL was used to convert my dicom MRI files to a compressed and zipped nifti file. 
<img width="740" alt="image" src="https://user-images.githubusercontent.com/69320369/212181672-6b4d1391-097f-47ad-a1f3-37ceb03557d9.png">

I then used a Oracle VM VirtualBox and Freesurfer to generate a scan of my brain and uploaded it into meshlab where I edited and converted it into a useable STL. I modified some of the program so that freesurfer would scan and build the cerebellum along with the brain.
<img width="959" alt="image" src="https://user-images.githubusercontent.com/69320369/212182040-7b66059f-6e5d-4ca5-93af-ef3f1c3fcb18.png">

Some of the files in my MRI scan were blurry and not very good quality so the brain ridges were not as clearly defined as I had hoped for. After I had roughly cleaned up the STL, I used Autodesk Fusion360 and Blender to clean the mesh and remove all skull parts and extra pieces that Freesurfer had accidentally scanned as part of my brain. 
![image](https://user-images.githubusercontent.com/69320369/212183036-8111c188-522b-4b99-8493-cff9ecb54623.png)

Once the final mesh had been rendered I uploaded it to PrusaSlicer to prepare it for 3D printing.
![image](https://user-images.githubusercontent.com/69320369/212183233-7118bfe2-c5d6-45cd-9b8c-0d0a9d5a5609.png)

48 hours of printing later it was finished in real size and weighed about 2.5 pounds which is roughly the weight of my brain. 

<img height="300" alt="image" src="https://user-images.githubusercontent.com/69320369/212183849-341a9210-0b84-41c3-9ae9-6484d2441e1f.jpg"> <img height="300" alt="image" src="https://user-images.githubusercontent.com/69320369/212183856-ca35c59b-8d99-4146-aade-842c8ad7eb1a.jpg"> <img height="300" alt="image" src="https://user-images.githubusercontent.com/69320369/212183864-4cbb252b-611e-4cf8-bd7b-0f596820228b.jpg"> <img height="300" alt="image" src="https://user-images.githubusercontent.com/69320369/212183871-12270e6d-1d24-4ab0-8b89-4243d8cfc4ca.jpg">

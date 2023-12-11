### Open Source Code for Train Wheel's Axle Estimation and Profile Correction

This open-source code provides two distinct approaches, each tailored to a specific dataset:

1. **Profiles with Side Contours:**
   - **Method:** Direct calculation of the axis direction.
   - **Procedure:** Directly compute the axis direction from side contours, construct a matching point set based on the axis direction, ultimately obtaining a point on the axis.

2. **Profiles without Side Contours:**
   - **Method:** Iterative optimization.
   - **Procedure:** Input an initial value for the axis direction, typically using a vector formed by two endpoints of the general cross-sectional profile. Iteratively optimize between constructing a matching point set and the axis direction until the axis stabilizes, resulting in an accurate axis.

### Profile Correction and Data
- **Profile Correction:**
  - Leveraging the solved axis, a correction is applied to the general cross-sectional profile, yielding an accurate normal cross-sectional profile.

- **Code and Data:**
  - All relevant code and datasets are included in the compressed file named `3DRe.7z`.

### Project Updates
This project will be continuously updated, aiming to contribute to advancements in high-precision train measurements.

## Repository Contents

Below is a detailed description of the supplementary files and workflows provided in this repository:

### 1. Coordinates and Structures
* **`xyz Cartesian Coordinates.txt`**: A plain txt file containing the optimized Cartesian coordinates (xyz) for both the QM regions in the QM/MM calculations and the truncated QM models.
* **`AusE-RC.pdb`**: A complete PDB file containing the QM/MM-optimized reactant structure of the AusE-substrate complex.

### 2. Input Files and Workflows
* **`CASSCF_SDSPT2.inp`**: A representative input file for the reactant complex (RC), detailing the active space selection and specific keywords required to execute the SDSPT2 calculations. 
  > *Please note: These multireference calculations were performed using the academic version of the BDF program package, as the commercial version does not currently support this functionality. The academic version can be obtained upon request from Prof. Wenjian Liu.*
* **`Tunneling_correction.md`**: The explicit mathematical formula for the Wigner tunneling correction factor (κ) is provided. This allows interested readers to readily reproduce our values by applying this formula to the imaginary frequencies already reported in the main text.

### 3. LMO Overlap (Releases)
* Code and raw data for some key LMOs from both the truncated and enlarged QM regions of TS2H1 and TS2rebC2 are provided. 
  > 📥 **Download Note:** Due to file size limits, this dataset is hosted as a compressed archive. Please navigate to the **[Releases](../../releases/latest)** section on the right sidebar of this repository to download the `.zip` file.

# Machine-learning-amide-II-IR-spectra
Any researchers who interested in protein spectroscopy can use our ML protcol online service: http://dcaiku.com:12880/platform/first

For the machine learning protocol source code written in Python and Bash language which including:
1.1.py: Split the protein into individual peptide bonds and dipeptides.
1.2.py: Calculate the center of mass for each each peptide bond and dipeptide.
2.1.sh: Extracte the descriptors of peptide bond.
2.2.sh: Extracte the descriptors of dipeptide.
3.1.py: Predict the vibrational frequency and vibrational transition dipole moment of each peptide bond from trained ML model.
3.2.py: Predict the neighboring coupling of each dipeptide from trained GLDP ML model.
3.3.py: Construct the model Hamiltonian for amide II vibrations in a protein based on vibration exciton model theory.
spectra_calc.sh: Diagonalize the Hamilton matrix to calculate the signal by using the SPECTRON (J. Phys. Chem. B 2006, 110, 3362-3374) program.

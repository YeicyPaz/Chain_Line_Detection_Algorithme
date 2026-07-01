# Chain Line Extraction Second Pipeline Algorithme

<big> This pipeline is the **second** approach of two approaches developed to extract string lines (also knows as Chain Lines) from manuscript images. The algorithm applies preprocessing to delete the text with the tool Magic Eraser. It uses Total Variation Spectral Decomposition to remove unnecessary textures, leaving only string lines with more clarity. In addition, the Fast Fourier Transform is used with a vertical projection to locate the lines of chains and measure the space between them. </big>

<big> This work is based on the research work of "Hidden Knowledge: Mathematical Methods for the Extraction of the Fingerprint of Medieval Paper from Digital Images" by Tamara G. Grossmann, Carola-Bibiane Schönlieb and Orietta Da Rold.

Some changes were made in order to adapt it to the needs of the project and improve its functioning. You will find some images in the folder of this project to check the execution of the algorithm</big>

@article{grossmann2023extracting,
  title={Extracting chain lines and laid lines from digital images of medieval paper using spectral total variation decomposition},
  author={Grossmann, Tamara G and Sch{\"o}nlieb, Carola-Bibiane and Da Rold, Orietta},
  journal={Heritage Science},
  volume={11},
  number={1},
  pages={180},
  year={2023},
  publisher={Springer}
}

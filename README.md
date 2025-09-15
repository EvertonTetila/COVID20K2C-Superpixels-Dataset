# COVID20K2C-Superpixels-Dataset

Superpixel dataset created from CT scans for SARS-CoV-2 (COVID-19) infection.

![fig-covid](https://github.com/EvertonTetila/COVID20K2C-Superpixels-Dataset/assets/37840161/379ef576-d629-4f66-8fe2-d754ca9e9c27)

# Image acquisition

This dataset was created from chest CT scans from a publicly available dataset called SARS-COV-2-Ct-Scan-Dataset. The source dataset contains 1252 CT scans that are positive for SARS-CoV-2 (COVID-19) infection and 1230 CT scans for patients not infected with SARS-CoV-2, 2482 CT scans in total. This data was collected from real patients in hospitals in São Paulo, Brazil.

Then, each acquired CT image was segmented by the SLIC Superpixels method and the randomly chosen segments (10,000 superpixels for each class) were labeled by a senior radiologist, thus generating the dataset called COVID20K2C-Superpixels-Dataset.

COVID20K2C-Superpixels-Dataset has 20 thousand superpixel images divided into two classes, containing 10,000 superpixels in each. The COVID class has superpixels with the characteristics of lung infections caused by COVID-19 and the non-COVID class contains superpixels with the other regions of the lung. All superpixels were labeled by a senior radiologist.

# Dataset download 

Link: http://evertontetila.ws.ufgd.edu.br/Datasets/COVID20K2C.zip

# Acknowledgements

This dataset was created by the authors and should be cited as follows:

TETILA, E. C.;BRESSEM, K. K.; ASTOLFI, G.; SANT'ANA, D. A.; PACHE, M. C. B.; WIRTI JUNIOR, G.; BARBEDO, J. G. A.; PISTORI, H. System for quantitative diagnosis of COVID-19 associated Pneumonia based on Superpixels with deep learning and chest CT. OBSERVATORIO DE LA ECONOMÍA LATINOAMERICANA, v. 21, p. 10883-10905, 2023. https://doi.org/10.55905/oelv21n9-022


# NSSP
NSSP Miniproject 1 Autumn 2026

Report is available for collaborators here : https://www.overleaf.com/project/69f9f73e3fffd2986c77f8fd/share#af1a573970cde97a613c58b11d8661c98c1f7c6ebe18afc4


## ⚠️ À modifier avant de lancer

| Où | Quoi | Action |
|---|---|---|
| Cellule d'imports | `notebook_dir` / `parent_dir` | Exemple pour moi : "data/Desktop/myfiles/NSSP/Mini Project 1" |

-> Bien vérifié où se situe "utils.py" ⚠️ ⚠️ ⚠️

-> Bien vérifié que vous utilisé un kernel Python ⚠️ ⚠️ ⚠️

## Description des fichiers

### Structural Preprocessing
| Fichier | Description |
|---|---|
| `T1w.nii.gz` | Original T1 |

### Functional Preprocessing
| Fichier | Description |
|---|---|
| `tfMRI_LANGUAGE_LR.nii` | Original fMRI |
| `tfMRI_LANGUAGE_LR_moco.nii.gz` | Motion Corrected fMRI |
| `tfMRI_LANGUAGE_LR_moco_smoothed-5mm.nii.gz` | fMRI corrigé puis lissé (gaussien, FWHM 5 mm) |
| `tfMRI_LANGUAGE_LR_bbr.nii.gz` | Volume de référence recalé sur l'anatomique (`epi_reg`, BBR) |

### GLM
| Fichier | Description |
|---|---|

### K-Means Clustering
| Fichier | Description |
|---|---|
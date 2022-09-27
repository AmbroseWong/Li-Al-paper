# Li-Al-paper

Data used in or calculated from the Li-Al paper

__crystal_structures/__ includes POSCAR files of all stable sturctures predicted by this paper;

__machine_learning/nep_train__ are files (dataset and input) used to train the machine learning potential of Li6Al ranging from 50 to 150 GPa, covering solid, superionic and liquid states. Using `cat train.xyz* > train.xyz` to restore training dataset; 

__machine_learning/mlmd/lammps__ and __machine_learning/mlmd/gpumd__ are inputs of machine learning molecular dynamics including the configuration, the potential file nep.txt and the MD software inputs. We tested nep.txt using different MD software including __LAMMPS__ and __GPUMD__. __GPUMD__ is the package we developed for NEP machine learning training and coresponding MD simulations. See details in <https://doi.org/10.1063/5.0106617> or <https://github.com/brucefan1983/GPUMD>.

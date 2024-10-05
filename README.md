# MD_Wetting
Scripts for computing the solubility parameter, surface tension, and wetting properties of liquids

To cite, please use: Jarray A.,  Wijshoff  H.,  Jurriaan  L.  A.,  and  den  Otter  W.  K.,  Systematic  approach  for wettability prediction using molecular dynamics simulations,Soft Matter16, 4299-4310 (2020)

and/or

Jarray A., Feichtinger A., and Scholten E,  Linking intermolecular interactions and rheological behaviour in capillary suspensions. Journal of Colloid and Interface Science 627, 415-426 (2022).

 
 
 To launch, you need to install lammps, and run using the compute_SP file using the command: 
 
 lmp_serial <compute_SP.in  (for parallel run, use mpirun -np 4 lmp_mpi -in compute_SP.in)

For more help,  tutorial: [Basic_Tutorial.docx](https://github.com/user-attachments/files/17265651/Basic_Tutorial.docx)

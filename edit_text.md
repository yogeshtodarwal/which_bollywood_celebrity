Analyzing conformer distributions of ligands at their highly populated binding sites of tau and comparing these with distributions in water environment uncovers significant changes in conformer patterns. Specifically, pFTAA and qFTAA-CN at site S1 of tau predominantly adopted TT (75\%) and TTT (96\%) conformers, respectively (see Figure~\ref{fig: Ligand dihedral distribution}). The structural alignment of pFTAA and qFTAA-CN positions all carboxyl groups on one side, facilitating strong Coulombic interactions with LYS369. In contrast, in a water environment, there presence in TT and TTT conformations drastically reduced to 18\% and 19\%, respectively. 


For HS-276 and bTVBT4 at site S2, they favored Tt and T conformers with 49\% and 75\% in tau whereas 19\% and 50\%  in water, respectively. 


 Furthermore, this shift in conformers is primarily influenced by the dihedral type SCCS, which displayed a strong preference for the trans position in all ligands within the tau environment. These observations imply that ligand binding can trigger structural changes that impact the conformer distribution, which may, in turn, potentially alter the photophysical properties of the ligands.



-------------------

Intriguingly, the protein environment induced significant alterations in the conformer patterns of all four ligands when compared to their behavior in water. (For neutral ligand all conformers are populated, while for anionic and neutrationic ligands significant change in pattern is observed )



Complementing these binding site observations,  the interaction energies given in Table \ref{tab:interaction_energies} show that the binding of pFTAA and qFTAA-CN to the tau fibril is driven by Coulomb interactions, while the binding of HS-276 and bTVBT4 is driven by LJ interactions. 



All ligands bind to their respective sites parallel to the A$\beta$(1––42) fibril axis. The binding sites S1 and S3 have been previously reported in the literature for other ligands.\cite{Murugan2018Jul} However, we did not find any mention of site S2 in the existing literature, where the HS-276 ligand binds. 


 Their binding to the A$\beta$(1––42) protein is driven by Coulombic interactions, as seen in Table \ref{tab:interaction_energies}.

 The binding of the neutral ligand HS-276 and cationic bTVBT4 to the A$\beta$(1––42) protein is mainly driven by LJ interactions (see Table \ref{tab:interaction_energies}).









I will give raw results based on which write three seperate paragraph. The first paragraph should be about comparing conformer percentages of all the ligands in  amyloid-beta fibril and water environment. The second paragraph should be about comparing conformer percentages of all the ligands in tau fibril and water environment. The third paragraph is about stating paterns observed in protein environment vs in water environment for give four ligands. Please note that it should this paragraphs will directly go into manuscript so please ensure that the give information by you is logically correct

Raw results:

Results from  MD simulation of pFTAA(charge -4) and qFTAA-CN (charge -3), HS-276 (charge 0), and bTVBT4 (charge +1) ligands in amyloid-beta, tau and water environment:

Note: T means trans, C means cis. if it is capital letter like T or C then it is for SCCS dihedral, and small letter is used for SCCN dihedral. "Other" is used for combined percentage of remaning dihedral conformers. 

pFTAA conformer percentage:
in water:  CC 35 , CT/TC 47 , TT 18
in amyloid-beta: CC 0 , CT/TC 6 , TT 94
in tau: CC 0 , CT/TC 25 , TT 75

qFTAA-CN conformer percentage:
in water:  TTT 19 , TTC 14 , CTT 41, Other 26 
in amyloid-beta: TTT 70 , TTC 30 , CTT 0, Other 0 
in tau: TTT 96 , TTC 4 , CTT 0, Other 0 

HS-276 conformer percentage:
in water:  Tt 19 , Tc 17 , Ct 34, Cc 30 
in amyloid-beta:  Tt 44 , Tc 21 , Ct 26, Cc 9
in tau:  Tt 49 , Tc 20 , Ct 17, Cc 14

bTVBT4 conformer percentage:
in water:  T 50  , C 50
in amyloid-beta:  T 21 , C 79
in tau:  T 75 , C 25
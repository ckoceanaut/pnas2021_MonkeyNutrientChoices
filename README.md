## Introduction
This dataset includes original choice data (N=61,655) collected from three rhesus monkeys published in "**Preferences for nutrients and sensory food qualities identify biological sources of economic values in monkeys**" (2021), _Proceedings of the National Academy of Sciences_ (Huang et al. PNAS 2021).

## Data description

Three rhesus macaques (numbered 77, 80, 81, respectively) made choices between flavor-matched (peach or blackcurrant flavor) liquids with 2 x 2 fat and sugar levels (**LFLS**: low-fat low-sugar; **HFLS**: high-fat low-sugar; **LFHS**: low-fat high-sugar; **HFHS**: high-fat high-sugar). Pairwise comparisons between these four liquid types generated 6 combinatorial session types as follows :
  - Type 1: LFLS v.s. LFHS
  - Type 2: HFLS v.s. HFHS
  - Type 3: LFLS v.s. HFLS
  - Type 4: LFHS v.s. HFHS
  - Type 5: HFLS v.s. LFHS
  - Type 6: LFLS v.s. HFHS

The session information and choice data were provided in ***SessInfo.mat*** and ***dataTbl.mat***, respectively (see below).
For the detailed task design, please refer to the original paper and its method section.
All data were generated and processed in Matlab 2017 unless otherwise specified.

### Session information (SessInfo.mat)
This table includes information of all testing sessions from three monkeys:
- **Animal**: animal identity - 77, 80, or 81
- **Session**: chronological session numbers for each animal
- **Type**: session type 1-6, indicating pair-wise comparisons between the four liquid types (see **Data description**)
- **nTrial**: completed trial numbers in each testing session
- **Flavour**: juice flavor, _Peach_ or _Ribena_ (British blackcurrant juice), for both options
- **CS1**: juice type 1, fixed within each session, but pseudorandom across sessions
- **CS2**: juice type 2, fixed within each session, but pseudorandom across sessions
- **Date**: date of data collection (dd-mm-yyyy)

### Choice data (dataTbl.mat)

This table provides complete trial-by-trial information of monkey choices from all three monkeys:
- **Animal**: animal identity, 70, 80 or 81
- **Session**: chronological session numbers for each animal
- **Trial**: chronological trial numbering in each testing session
- **LeftChosen**: whether the left option (=1) or the right option (=0) was chosen:
- **CS1First**: whether juice type 1 (CS1) was presented as the first (=1) or second (=0) stimulus in the sequential presentation 
- **CS1Left**: whether juice type 1 (CS1) was on the left (=1) side or right (=0) side during the choice epoch
- **CS1RM/CS2RM**: the offered liquid amount (mL) cued by a magnitude bar
- **CS1ribena/CS2ribena**: whether juice type 1 (CS1) or juice type 2 (CS2) was **blackcurrant** flavor (=1), or not (=0)
- **CS1peach/CS2peach**: whether juice type 1 (CS1) or juice type 2 (CS2) was **peach** flavor (=1), or not (=0)
- **CS1energy/CS2energy**: energy density (kcal/100mL) for juice type 1 (CS1) or juice type 2 (CS2)
- **CS1fatconc/CS2fatconc**: fat concentration (g/100mL) for juice type 1 (CS1) or juice type 2 (CS2)
- **CS1sugarconc/CS2sugarconc**: sugar concentration (g/100mL) for juice type 1 (CS1) or juice type 2 (CS2)
- **CS1protconc/CS2protconc**: protein concentration (g/100mL) for juice type 1 (CS1) or juice type 2 (CS2)
- **CS1visc/CS2visc**: viscosity (cP) of the liquids measured at 18.5 degrees Celsius
- **CS1sliding/CS2sliding**:  coefficient of sliding friction (CSF) measured by custom-made tribometer, normalized with the CSF of water 

## Conditions for using this dataset
Conducting this research project and collecting this dataset required years of effort. It is our lab policy that any preprint or peer-reviewed publication using these data should normally list as authors the people who collected the data (Fei-Yang Huang, Fabian Grabenhorst), and the principal investigator under whose responsibility the dataset has been collected (Fabian Grabenhorst). Therefore, before preparing publications using these data, please contact the principal investigator (fabian.grabenhorst@gmail.com). In addition, please cite the publication given above (Huang et al., 2021, PNAS) and also cite the data set using the following link:

https://github.com/ckoceanaut/pnas2021_MonkeyNutrientChoices

## Further information
In case of any questions or requests for further detials of the data, please feel free to contact the authors,
Fei-Yang Huang (ckoceanaut@gmail.com) and Fabian Grabenhorst (fabian.grabenhorst@gmail.com)

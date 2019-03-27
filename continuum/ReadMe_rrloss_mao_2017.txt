J/A+A/599/A10     Radiative recombination electron energy loss data (Mao+, 2017)
================================================================================
The electron energy-loss rate due to radiative recombination.
    Mao J., Kaastra J., Badnell N.R.
    <Astron. Astrophys. 599, A10 (2017)>
    =2017A&A...599A..10M        (SIMBAD/NED BibCode)
================================================================================
ADC_Keywords: Atomic physics
Keywords: atomic data - atomic processes

Abstract:
    For photoionized plasmas, electron energy loss rates due to radiative
    recombination (RR) are required for thermal equilibrium calculations,
    which assume a local balance between the energy gain and loss. While
    many calculations of total and/or partial RR rates are available from
    the literature, specific calculations of associated RR electron energy
    loss rates are lacking.

    Here we focus on electron energy loss rates due to radiative
    recombination of H-like to Ne-like ions for all the elements up to and
    including zinc (Z=30), over a wide temperature range.

    We used the AUTOSTRUCTURE code to calculate the level-resolved
    photoionization cross section and modify the ADASRR code so that we
    can simultaneously obtain level-resolved RR rate coefficients and
    associated RR electron energy loss rate coefficients. We compared the
    total RR rates and electron energy loss rates of HI and HeI with those
    found in the literature. Furthermore, we utilized and parameterized
    the weighted electron energy loss factors (dimensionless) to
    characterize total electron energy loss rates due to RR.

    The RR electron energy loss data are archived according to the Atomic
    Data and Analysis Structure (ADAS) data class adf48. The RR electron
    energy loss data are also incorporated into the SPEX code for detailed
    modeling of photoionized plamsas.

Description:
    The weighted electron energy loss factors (dimensionless) are defined
    by weighting the electron energy loss rate coefficients (per ion) with
    respect to the total radiative recombination rates. Both the
    unparameterized and parameterized weighted electron energy-loss
    factors for H-like to Ne-like ions from H (z=1) up to and including
    Zn (z=30), in a wide temperature range, are available here. For the
    unparameterized data set, the temperatures are set to the conventional
    ADAS temperature grid, i.e.
    c^2^*(10,20,50,100,200,...,2*10^6^,5*10^6^,10^7^)K, where c is the
    ionic charge of the recombined ion. For the fitting parameters, the
    temperature should be in units of eV. We refer to the recombined ion
    when we speak of the radiative recombination of a certain ion, for
    example, for a bare oxygen ion capturing a free electron via radiative
    recombination to form H-like oxygen (O VIII, s=1, z=8). The fitting
    accuracies are better than 4%.

File Summary:
--------------------------------------------------------------------------------
 FileName      Lrecl  Records   Explanations
--------------------------------------------------------------------------------
ReadMe            80        .   This file
calc.dat         119      255   Unparameterized data
pars.dat          86      255   Fitting parameters
--------------------------------------------------------------------------------

Byte-by-byte Description of file: calc.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  2  I2    ---     s         Isoelectronic sequence number
   4-  5  I2    ---     z         Atomic number
   7- 11  F5.3  ---     f1        Weighted electron energy-loss factors at T1
  13- 17  F5.3  ---     f2        Weighted electron energy-loss factors at T2
  19- 23  F5.3  ---     f3        Weighted electron energy-loss factors at T3
  25- 29  F5.3  ---     f4        Weighted electron energy-loss factors at T4
  31- 35  F5.3  ---     f5        Weighted electron energy-loss factors at T5
  37- 41  F5.3  ---     f6        Weighted electron energy-loss factors at T6
  43- 47  F5.3  ---     f7        Weighted electron energy-loss factors at T7
  49- 53  F5.3  ---     f8        Weighted electron energy-loss factors at T8
  55- 59  F5.3  ---     f9        Weighted electron energy-loss factors at T9
  61- 65  F5.3  ---     f10       Weighted electron energy-loss factors at T10
  67- 71  F5.3  ---     f11       Weighted electron energy-loss factors at T11
  73- 77  F5.3  ---     f12       Weighted electron energy-loss factors at T12
  79- 83  F5.3  ---     f13       Weighted electron energy-loss factors at T13
  85- 89  F5.3  ---     f14       Weighted electron energy-loss factors at T14
  91- 95  F5.3  ---     f15       Weighted electron energy-loss factors at T15
  97-101  F5.3  ---     f16       Weighted electron energy-loss factors at T16
 103-107  F5.3  ---     f17       Weighted electron energy-loss factors at T17
 109-113  F5.3  ---     f18       Weighted electron energy-loss factors at T18
 115-119  F5.3  ---     f19       Weighted electron energy-loss factors at T19
--------------------------------------------------------------------------------

Byte-by-byte Description of file: pars.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  2  I2    ---     s         Isoelectronic sequence number
   4-  5  I2    ---     z         Atomic number
   7- 16  E10.4 ---     a0        Primary fitting parameter
  18- 27  E10.4 ---     b0        Primary fitting parameter
  29- 38  E10.4 ---     c0        Addiational fitting parameter
  40- 49  E10.4 ---     a1        Primary fitting parameter
  51- 60  E10.4 ---     b1        Primary fitting parameter
  62- 71  E10.4 ---     a2        Addiational fitting parameter
  73- 82  E10.4 ---     b2        Addiational fitting parameter
  84- 86  F3.1  ---     mdp       Maximum deviation in percent
--------------------------------------------------------------------------------

Acknowledgements:
    Junjie Mao, J.Mao(at)sron.nl

================================================================================
(End)         Junjie Mao [SRON], Patricia Vannier [CDS]              09-Dec-2016

# CBT677
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 677 is from Marco Willemse and contains his Parallel      *   FILE 677
//*           Sysplex Manager ISPF application.                     *   FILE 677
//*                                                                 *   FILE 677
//*     Sysplex Manager Version 1.0.0 (Beta)                        *   FILE 677
//*     ===============                                             *   FILE 677
//*                                                                 *   FILE 677
//*     >>>  WARNING: This is a Beta version !!!     <<<            *   FILE 677
//*     >>>  Do NOT use in a Production Sysplex !!!  <<<            *   FILE 677
//*                                                                 *   FILE 677
//*     Send comments, critics, suggestions, modifications to:      *   FILE 677
//*                                                                 *   FILE 677
//*       marco.willemse@corner.ch                                  *   FILE 677
//*                                                                 *   FILE 677
//*     REXX:                                                       *   FILE 677
//*     -----                                                       *   FILE 677
//*     KSMMAIN - The main procedure                                *   FILE 677
//*     KSMCONS - To use the TSO REXX CONSOLE interface             *   FILE 677
//*                                                                 *   FILE 677
//*     Panels:                                                     *   FILE 677
//*     -------                                                     *   FILE 677
//*     KSMPRIM - The primary panel for Sysplex Manager             *   FILE 677
//*     KSMTYPE - Couple dataset type input panel                   *   FILE 677
//*     KSMCDSN - Couple dataset name input panel                   *   FILE 677
//*     KSMPNAM - Policy name input panel                           *   FILE 677
//*     KSMPTYP - Policy type input panel                           *   FILE 677
//*     KSMSDKP - Structure duplexing keep input panel              *   FILE 677
//*     KSMSSIZ - Structure size input panel                        *   FILE 677
//*                                                                 *   FILE 677
//*     Skeletons:                                                  *   FILE 677
//*     ----------                                                  *   FILE 677
//*     KSMDPOL - Policy Report Job                                 *   FILE 677
//*     KSMNCDS - New Couple Dataset Job                            *   FILE 677
//*     KSMNPOL - New Policy Job                                    *   FILE 677
//*                                                                 *   FILE 677
//*     Tables:                                                     *   FILE 677
//*     -------                                                     *   FILE 677
//*     KSMKEYS - Keylist for the panels                            *   FILE 677
//*                                                                 *   FILE 677
//*     RACF (SAF) accesses needed:                                 *   FILE 677
//*     ---------------------------                                 *   FILE 677
//*     TSOAUTH    CONSOLE           READ                           *   FILE 677
//*     OPERCMDS   MVS.SETXCF.** (G) CONTROL                        *   FILE 677
//*     Other accesses may be needed !                              *   FILE 677
//*                                                                 *   FILE 677
//*     Reference:                                                  *   FILE 677
//*     ----------                                                  *   FILE 677
//*     Actions:                                                    *   FILE 677
//*                                                                 *   FILE 677
//*     A - Alter    = Alter the size of a structure                *   FILE 677
//*     C - aCouple  = Add an Alternate CDS                         *   FILE 677
//*     D - Display  = Show the object details (D XCF)              *   FILE 677
//*     F - Force    = Force a structure or a connection            *   FILE 677
//*     I - Rebuild  = Rebuild a structure or a CF with             *   FILE 677
//*                    LOCATION=OTHER                               *   FILE 677
//*     L - List     = List the objects                             *   FILE 677
//*     N - New      = Create a new object (CDS or Pol)             *   FILE 677
//*     O - stOp     = Stop a policy                                *   FILE 677
//*     P - Populate = Perform a Rebuild with POPULATECF keyword    *   FILE 677
//*     Q - Quit     = Quit the KSMMAIN Rexx Exec                   *   FILE 677
//*     R - Report   = Create a policy report                       *   FILE 677
//*     S - Start    = Start a policy                               *   FILE 677
//*     U - Unduplex = Stop Rebuild DUPLEX                          *   FILE 677
//*     W - PsWitch  = Use the Alternate CDS as Primary             *   FILE 677
//*     X - DupleX   = Rebuild a structure with the DUPLEX keyword  *   FILE 677
//*                                                                 *   FILE 677
//*     Future plans:                                               *   FILE 677
//*     -------------                                               *   FILE 677
//*     - add support for xcf (PI,PO,TG,Cl)                         *   FILE 677
//*     - add support for system logger                             *   FILE 677
//*     - add pfkey for up and down                                 *   FILE 677
//*     - provide an edit macro to cleanup policy reports           *   FILE 677
//*     ... and a lot of other ideas                                *   FILE 677
//*                                                                 *   FILE 677
```

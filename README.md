# CBT249
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 249 is from Eileen Barkow of DOITT - New York City,       *   FILE 249
//*           New York, and contains a collection of useful         *   FILE 249
//*           programs.                                             *   FILE 249
//*                                                                 *   FILE 249
//*     email:   ebarkow@doitt.nyc.gov                              *   FILE 249
//*                                                                 *   FILE 249
//*     email:   sbgolob@cbttape.org                                *   FILE 249
//*                                                                 *   FILE 249
//*     - - - - - - - - - - - - - - - - - - - - - - - - - - - - -   *   FILE 249
//*                                                                 *   FILE 249
//*     WMOD was fixed and improved to work on OS/390 2.8.  The     *   FILE 249
//*     program broke somewhere between 2.5 and 2.8.  This fix      *   FILE 249
//*     was made by Steve Niebauer of Wachovia Bank.                *   FILE 249
//*                                                                 *   FILE 249
//*     email:   Steve.Niebauer@Wachovia.Com                        *   FILE 249
//*                                                                 *   FILE 249
//*     Steve's version of WMOD is member WMOD.  Eileen's versions  *   FILE 249
//*     are called WMODTSO and WMODCICS.  Please see members called *   FILE 249
//*     $$NOTE and $$NOTE1.                                         *   FILE 249
//*                                                                 *   FILE 249
//*     I tested the new WMOD on OS/390 2.10 and it appears to      *   FILE 249
//*     work fine.  (SBG)  For older systems, use Eileen's old      *   FILE 249
//*     version, WMODTSO2.                                          *   FILE 249
//*                                                                 *   FILE 249
//*     Tested WMOD on z/OS 2.2 and seems to work fine.             *   FILE 249
//*     Problem fixed in this version of WMOD to make sure          *   FILE 249
//*     SYSPROC was still there, before trying to close it.         *   FILE 249
//*                                                                 *   FILE 249
//*     - - - - - - - - - - - - - - - - - - - - - - - - - - - - -   *   FILE 249
//*                                                                 *   FILE 249
//*     Eileen has also fixed WMODTSO and WMODCICS for newer        *   FILE 249
//*     systems.  These are members WMODTSO and WMODCICS.  Eileen's *   FILE 249
//*     former members are WMODTSO1 and WMODCIC1.  The earlier      *   FILE 249
//*     fixed versions are WMODTSO2 and WMODCIC2.                   *   FILE 249
//*                                                                 *   FILE 249
//*     - - - - - - - - - - - - - - - - - - - - - - - - - - - - -   *   FILE 249
//*                                                                 *   FILE 249
//*     THE FOLLOWING PROGRAMS ARE IN THIS COLLECTION:              *   FILE 249
//*                                                                 *   FILE 249
//*     WMOD FOR TSO  -  FIND OCCURRENCES OF A PDS MEMBER NAME.     *   FILE 249
//*                      THIS PROGRAM WILL SEARCH ALLOCATED         *   FILE 249
//*                      PDS LIBRARIES IN THE TSO ADDRESS SPACE     *   FILE 249
//*                      FOR THE SPECIFIED MODULE NAME, INCLUDING   *   FILE 249
//*                      CLISTS, SOURCE, ISPF LIBRARIES, ETC. IT    *   FILE 249
//*                      WILL ALSO SEARCH STEPLIB, LPA, LINKLIST    *   FILE 249
//*                      AND SVCLIB.  FOR LPA MODULES, THE          *   FILE 249
//*                      ADDRESS IN LPA WILL BE RETURNED.  FOR      *   FILE 249
//*                      ALL OTHERS, THE DATASET NAME WILL BE       *   FILE 249
//*                      RETURNED.                                  *   FILE 249
//*                                                                 *   FILE 249
//*     WMOD FOR CICS -  FIND OCCURRENCES OF A PDS MEMBER NAME.     *   FILE 249
//*                      THIS PROGRAM SEARCHES ALL DFHRPL           *   FILE 249
//*                      LIBRARIES, STEPLIB, LINKLIST, LPA, AND     *   FILE 249
//*                      SVCLIB FOR SPECIFIED MODULE NAME.  IT      *   FILE 249
//*                      TAKES A GUESS AS TO WHERE CICS LOADED      *   FILE 249
//*                      THE MODULE FROM IF THE MODULE EXISTS IN    *   FILE 249
//*                      MULTIPLE PLACES (IE:  MODULE IS IN         *   FILE 249
//*                      DFHRPL AS WELL AS STEPLIB AND LPA).        *   FILE 249
//*                                                                 *   FILE 249
//*     UCB           -  IF YOU GIVE THE UNIT ADDRESS, THIS WILL    *   FILE 249
//*                      RETURN THE VOLUME SERIAL.  IF YOU GIVE     *   FILE 249
//*                      THE VOLUME SERIAL, THIS WILL GIVE THE      *   FILE 249
//*                      UNIT ADDRESS.  USES UCBLOOK AND WORKS      *   FILE 249
//*                      FOR DYNAMIC UCB'S.                         *   FILE 249
//*                      (Updated for 4-byte UCB's.  Doesn't need   *   FILE 249
//*                      the SVC to get authorized.  Only needs     *   FILE 249
//*                      an entry in the IKJEFTE2 (AUTHCMD table    *   FILE 249
//*                      in IKJTSOxx PARMLIB member).               *   FILE 249
//*                                                                 *   FILE 249
//*     UCBSVC        -  UCB program linkedited SETCODE(0) and      *   FILE 249
//*                      which gets its authorization instead,      *   FILE 249
//*                      from an SVC.  (Same program as UCB.)       *   FILE 249
//*                                                                 *   FILE 249
//*     UCBOLD        -  The previous version of UCB.               *   FILE 249
//*                                                                 *   FILE 249
//*     SVC           -  AUTH SVC                                   *   FILE 249
//*                                                                 *   FILE 249
```

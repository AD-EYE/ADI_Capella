# ADI_Capella

<br>

This repository contains code for the _**AD-EYE testbed for Automated Driving and Intelligent Transportation Systems**_, located at KTH Campus Valhallavägen, designed and developed by Naveen Mohan and others. <br><br>

This particular respository serves as a store for the work performed during the first application made by AD-EYE to Transportstyrelsen, using the RCV-E.
This repository contains work from the ITRL team in the form of the RCV-E capella library, and the work from the AD-EYE team in modelling the ADI. 

<br><br>

-------------------------------------------------
<br>

- **Webpage:** https://www.adeye.se <br> <br>

-------------------------------------------------
<br>

- **Documentation:** https://github.com/AD-EYE/AD-EYE_Core/wiki <br> <br> 
- **Full list of contributors:** https://www.adeye.se/contributors <br> <br>
- **Funding Projects:** https://www.adeye.se/home <br> <br> 

-------------------------------------------------
<br>  

The ATRIUM process was first defined in the paper: **"ATRIUM — Architecting under uncertainty: For ISO 26262 compliance"_** <br>   

- **Original Publication**:  https://doi.org/10.1109/SYSCON.2017.7934819
- **Preprint:**:  https://arxiv.org/a/mohan_n_2.html
  
- **Citation:** N. Mohan, P. Roos, J. Svahn, M. Törngren and S. Behere, "ATRIUM — Architecting under uncertainty: For ISO 26262 compliance," 2017 Annual IEEE International Systems Conference (SysCon), Montreal, QC, Canada, 2017, pp. 1-8, doi: 10.1109/SYSCON.2017.7934819.
<br><br>
--------------------------------------------------------

**Note:**
The folder "capella" contains the base software capella MBSE and requires java jre-8u221.

Once launched, by chosing the workspace "workspace", the user will be able to see and modify the model of ADI and its related library : RCVE.

The Atrium VP v1.0.0 has been added in the dropins folder of the base capella software. Although it can be used in both branches, the branch ADI_and_RCVE does not contain any Atrium elements. The Capella model in the branch Atrium_process contains the start an Atrium iteration, and can be continued by opening the Atrium UI on the diagram "Atrium process diagram" of ADI. 


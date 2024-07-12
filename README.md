# Terroism
Exploratory data analysis on global terrorism
Description:
This project involves an exploratory data analysis (EDA) on a comprehensive dataset of global terrorism incidents. The dataset includes detailed information about each terrorist event, such as the date and location of the incident, the groups involved, the types of attacks and weapons used, and the outcomes in terms of casualties and damage.

Database Scheme:
Output:
- **eventid**: Unique identifier for each event.
- **iyear**: Year in which the event occurred.
- **imonth**: Month in which the event occurred.
- **iday**: Day on which the event occurred.
- **approxdate**: Approximate date of the event.
- **extended**: Indicates if the event extended over multiple days (1 for yes, 0 for no).
- **resolution**: Resolution of the event.
- **country**: Country code where the event occurred.
- **country_txt**: Country name where the event occurred.
- **region**: Region code where the event occurred.
- **region_txt**: Region name where the event occurred.
- **provstate**: Province or state where the event occurred.
- **city**: City where the event occurred.
- **latitude**: Latitude of the event location.
- **longitude**: Longitude of the event location.
- **specificity**: Specificity of the location.
- **vicinity**: Indicates if the event occurred in the vicinity (1 for yes, 0 for no).
- **summary**: Summary of the event.
- **crit1**: Criterion 1 for inclusion (1 for yes, 0 for no).
- **crit2**: Criterion 2 for inclusion (1 for yes, 0 for no).
- **crit3**: Criterion 3 for inclusion (1 for yes, 0 for no).
- **doubtterr**: Indicates if there is doubt about the terrorism classification (1 for yes, 0 for no).
- **alternative**: Alternative designation.
- **alternative_txt**: Alternative designation text.
- **multiple**: Indicates if multiple incidents are involved (1 for yes, 0 for no).
- **success**: Indicates if the event was successful (1 for yes, 0 for no).
- **suicide**: Indicates if the event was a suicide attack (1 for yes, 0 for no).
- **attacktype1**: Attack type code.
- **attacktype1_txt**: Attack type text.
- **attacktype2**: Secondary attack type code.
- **attacktype2_txt**: Secondary attack type text.
- **attacktype3**: Tertiary attack type code.
- **attacktype3_txt**: Tertiary attack type text.
- **targtype1**: Target type code.
- **targtype1_txt**: Target type text.
- **targsubtype1**: Target subtype code.
- **targsubtype1_txt**: Target subtype text.
- **corp1**: Corporate entity affected.
- **target1**: Primary target.
- **natlty1**: Nationality of the target.
- **natlty1_txt**: Nationality of the target text.
- **targtype2**: Secondary target type code.
- **targtype2_txt**: Secondary target type text.
- **targsubtype2**: Secondary target subtype code.
- **targsubtype2_txt**: Secondary target subtype text.
- **corp2**: Secondary corporate entity affected.
- **target2**: Secondary target.
- **natlty2**: Secondary target nationality.
- **natlty2_txt**: Secondary target nationality text.
- **targtype3**: Tertiary target type code.
- **targtype3_txt**: Tertiary target type text.
- **targsubtype3**: Tertiary target subtype code.
- **targsubtype3_txt**: Tertiary target subtype text.
- **corp3**: Tertiary corporate entity affected.
- **target3**: Tertiary target.
- **natlty3**: Tertiary target nationality.
- **natlty3_txt**: Tertiary target nationality text.
- **gname**: Name of the perpetrator group.
- **gsubname**: Subgroup name of the perpetrator.
- **gname2**: Secondary perpetrator group name.
- **gsubname2**: Secondary subgroup name of the perpetrator.
- **gname3**: Tertiary perpetrator group name.
- **gsubname3**: Tertiary subgroup name of the perpetrator.
- **motive**: Motive behind the attack.
- **guncertain1**: Indicates if there is uncertainty about the group (1 for yes, 0 for no).
- **guncertain2**: Indicates if there is uncertainty about the secondary group (1 for yes, 0 for no).
- **guncertain3**: Indicates if there is uncertainty about the tertiary group (1 for yes, 0 for no).
- **individual**: Indicates if the perpetrator was an individual (1 for yes, 0 for no).
- **nperps**: Number of perpetrators.
- **nperpcap**: Number of perpetrators captured.
- **claimed**: Indicates if the attack was claimed (1 for yes, 0 for no).
- **claimmode**: Claim mode code.
- **claimmode_txt**: Claim mode text.
- **claim2**: Secondary claim indicator (1 for yes, 0 for no).
- **claimmode2**: Secondary claim mode code.
- **claimmode2_txt**: Secondary claim mode text.
- **claim3**: Tertiary claim indicator (1 for yes, 0 for no).
- **claimmode3**: Tertiary claim mode code.
- **claimmode3_txt**: Tertiary claim mode text.
- **compclaim**: Indicates if there are competing claims (1 for yes, 0 for no).
- **weaptype1**: Weapon type code.
- **weaptype1_txt**: Weapon type text.
- **weapsubtype1**: Weapon subtype code.
- **weapsubtype1_txt**: Weapon subtype text.
- **weaptype2**: Secondary weapon type code.
- **weaptype2_txt**: Secondary weapon type text.
- **weapsubtype2**: Secondary weapon subtype code.
- **weapsubtype2_txt**: Secondary weapon subtype text.
- **weaptype3**: Tertiary weapon type code.
- **weaptype3_txt**: Tertiary weapon type text.
- **weapsubtype3**: Tertiary weapon subtype code.
- **weapsubtype3_txt**: Tertiary weapon subtype text.
- **weaptype4**: Quaternary weapon type code.
- **weaptype4_txt**: Quaternary weapon type text.
- **weapsubtype4**: Quaternary weapon subtype code.
- **weapsubtype4_txt**: Quaternary weapon subtype text.
- **weapdetail**: Detailed description of the weapon.
- **nkill**: Number of people killed.
- **nkillus**: Number of US citizens killed.
- **nkillter**: Number of terrorists killed.
- **nwound**: Number of people wounded.
- **nwoundus**: Number of US citizens wounded.
- **nwoundte**: Number of terrorists wounded.
- **property**: Indicates if there was property damage (1 for yes, 0 for no).
- **propextent**: Extent of property damage code.
- **propextent_txt**: Extent of property damage text.
- **propvalue**: Value of property damage.
- **propcomment**: Comment on the property damage.
- **ishostkid**: Indicates if there were hostages or kidnapping (1 for yes, 0 for no).
- **nhostkid**: Number of hostages/kidnapped.
- **nhostkidus**: Number of US hostages/kidnapped.
- **nhours**: Number of hours held hostage/kidnapped.
- **ndays**: Number of days held hostage/kidnapped.
- **divert**: Divert indicator.
- **kidhijcountry**: Kidnapping/hijacking country code.
- **ransom**: Indicates if ransom was demanded (1 for yes, 0 for no).
- **ransomamt**: Amount of ransom demanded.
- **ransomamtus**: Amount of ransom demanded in USD.
- **ransompaid**: Amount of ransom paid.
- **ransompaidus**: Amount of ransom paid in USD.
- **ransomnote**: Ransom note details.
- **hostkidoutcome**: Outcome of the hostage/kidnapping event.
- **hostkidoutcome_txt**: Outcome of the hostage/kidnapping event text.
- **nreleased**: Number of hostages/kidnapped released.
- **addnotes**: Additional notes on the event.
- **scite1**: Source citation 1.
- **scite2**: Source citation 2.
- **scite3**: Source citation 3.
- **dbsource**: Database source.
- **INT_LOG**: Indicates if the event is logged as intentional (1 for yes, 0 for no).
- **INT_IDEO**: Indicates if the event is ideologically motivated (1 for yes, 0 for no).
- **INT_MISC**: Indicates if the event has miscellaneous characteristics (1 for yes, 0 for no).
- **INT_ANY**: Indicates if any of the INT flags are set (1 for yes, 0 for no).
- **related**: Related incidents.

Output:
# Removing irrelevant words in clean_t column
![download](https://github.com/user-attachments/assets/ebf0b3ce-1da7-437d-8bf9-6c0d4e667224)
# Number Of Terrorist Activities Each Year
![Number Of Terrorist Activities Each Year](https://github.com/user-attachments/assets/3086f99f-bbe6-4a63-90dd-5475f4deb85c)
# Top Affected Countries
![Top Affected Countries](https://github.com/user-attachments/assets/0737a248-61af-41a2-bb92-e9d96da07ff5)
# Attacks and Killed
![Attacks and KILLED](https://github.com/user-attachments/assets/66743f2f-3d27-4fbd-b4d2-c0bb010b4682)
# Activity of Top Terrorist Groups
![Activity of Top Terrorist Groups](https://github.com/user-attachments/assets/fc91b853-8863-475a-b6dd-336a030253a2)


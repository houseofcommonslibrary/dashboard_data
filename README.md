# dashboard_data
 Data from the MP activity dashboard (by session)
 
This repository contains files with data presented on the Library's dashboard 'MP data: Parliamentary activities'. It does not include data that is readily available from other sources: the APPG register (data on APPGs), the Commons Votes API (data on divisions), the Committees API (data on committee membership), the Questions API (data on EDMs), and the MNIS API (data on government and opposition roles). The Commons Library Github page includes packages to query these sources.

The data presented here covers spoken contributions, paper petitions MPs presented, Private Member's Bills they introduced, parliamentary questions they asked, and proceedings they initiated (Emergency Debates, Adjournment Debates, Urgent Questions, Westminster Hall debates and Backbench Business Debates). These data are downloaded using the clparlysearch package, which queries the Parliamentary Search website available on the Parliamentary intranet that gives access to all the data included here. There is also a file including data on the number of debates MPs contributed to; this is available from MPs' contact pages on the UK Parliament website (under spoken contributions). Due to recording errors, some questions have been removed from the data (as also noted on the dashboard). 

The files available here are structured to present activities by MP: there is a row for each activity for each MP. They all include a unique identifier number for each MP (mnis id) which can be used to link the data. For more information on how this identifier has been added, please see the clmpdashboard package. 


# Video demonstrations of IRV extensions to Corla

This repository contains some videos demonstrating our IRV extensions to colorado-rla. These are currently in prototype form, using code from (raire-java)[https://github.com/DemocracyDevelopers/raire-java], (raire-service)[https://github.com/DemocracyDevelopers/raire-service] and (our fork of colorado-rla)[https://github.com/DemocracyDevelopers/colorado-rla]. We're working actively on updating the prototype, so the version you pull may not quite match the videos you see here.

The demonstrations use real election data from Boulder (2023) and the Australian state of New South Wales (NSW) (2021). 

The root directory contains videos for a mixed election in which we pretend that the NSW data was uploaded by various Colorado counties. It shows setting up the election and generating, downloading and visualizing the assertions. You can view the assertions yourself by downloading (the assertions zip file)[https://github.com/DemocracyDevelopers/Videos-And-Large-Files/blob/main/NSW_2021_Boulder_2023_assertions.zip] and loading the individual contests into (the assertion explainer)[https://democracydevelopers.github.io/raire-rs/WebContent/explain_assertions.html].

The (Boulder23)[https://github.com/DemocracyDevelopers/Videos-And-Large-Files/tree/main/Boulder23Demo] directory shows more about the actual audit process, including how the audit board inputs audited IRV ballots. Note that the UI is still in prototype.  We get fairly high sample sizes because the public redacted CVRs have some ballots removed for privacy, but in a real IRV audit we would not expect IRV sample sizes to be significantly larger than plurality sample sizes for contests of the same margin.

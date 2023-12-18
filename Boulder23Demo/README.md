# Example run-through for IRV RLAs using redacted Boulder '23 data 

This folder contains demo videos of our colorado-rla extensions for IRV RLAs. This demo uses redacted data from Boulder county's 2023 election.
This demonstration is intended to showcase Democracy Developers' IRV RLA prototype, not to serve as any kind of audit of the Boulder '23 election.

The data has been redacted for privacy reasons, by removing some Cast Vote Records whose type was very infrequent. This means that tallies etc may be slightly different from the true ones. 

You can see the sample size estimate file [here](https://github.com/DemocracyDevelopers/Videos-And-Large-Files/blob/main/Boulder23Demo/Boulder23_Sample_Size_Estimates.csv).

1. [Generate_Assertions](Boulder23_1_Generate_Assertions.mp4) shows the process of generating assertions, and how they display in the database and can be downloaded.
2. [Start_Audit](Boulder23_2_Start_Audit.mp4) shows sample size estimation and the definition and commencement of the audit.
3. [NotesOnNumbers](Boulder23_3_NotesOnNumbers.mp4) discusses some of the numerical details.
4. [AuditingBallots](Boulder23_4_AuditingBallots.mp4) shows the county's audit board uploading (imaginary) ballot data.

Although the audit ballots are imaginary, the input data and the software are real. This is not a mock-up, it's a working prototype doing real computations for IRV audits in Colorado. 

You can try it yourself by following the [instructions for running RAIRE with colorado-rla](https://github.com/DemocracyDevelopers/raire-service) and loading the [Boulder '23 redacted data](https://github.com/DemocracyDevelopers/colorado-rla/tree/scratch/test/IRV-test/Boulder2023Data).

## Notes

The redacted ballots cause apparent-discrepancies and hence inflated sample sizes.
Some discussion of these numbers is contained in ``NotesOnNumbers.mp4'', including an explanation of why the starting number of expected ballots (703) is less than the maximum estimated sample of targeted contests (710).

At one point, I mistakenly say that the universe is ``the whole set of ballots cast in Colorado'' - it should be the whole set of ballots cast in Boulder. 




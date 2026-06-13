# Professor Outreach — Europe Deep Profile Repo

## Purpose
Build a verified, deeply-researched list of 50-60 European professors across
Track A (Biomedical AI), Track B (Molecular/Polymer ML), Track C (Optical/
Fluorescence sensing), and Track D (Spectrofluorometer/microplastics niche),
for PhD outreach starting July-October 2026.

## Structure
```
professor-outreach/
  progress.md                                  <- main tracker, read first
  templates/
    Amit_Results_Reference.md                  <- numbers/walls to cite
    European_PhD_Target_List_June10_2026.md    <- format reference
    Germany_MasterPrompt.md                    <- separate Track B-C Germany
                                                   campaign (do not duplicate)
  trackers/
    European_PhD_Target_List_Batch_1.md        <- created as batches complete
    European_PhD_Target_List_Batch_2.md
    ...
```

## How to run a session (10 professors per chat)
1. Open this repo in a new chat.
2. Say: "Continue the Europe professor outreach — next batch from progress.md"
3. Claude reads progress.md, picks the next NOT STARTED batch, researches
   10 professors at the depth shown in the format reference, and outputs a
   new tracker file.
4. Spot-check 2-3 entries (especially emails and ERC claims) before relying
   on them for outreach.
5. Update progress.md: mark the batch DONE, add new names to "Already
   profiled".

## Status (update after each batch)
- Already profiled: 19 / 50-60 target
- Batches completed: 0 / 4
- Next batch: Batch 1 (Sweden + Belgium)

## Hard rules (apply always)
- France excluded from new discovery (poor response history so far)
- CC candidate is MANDATORY for every entry — co-author from last 1-2 papers
- Every email and ERC/grant claim must be source-cited or flagged UNVERIFIED
- Max 10 professors per batch — depth over breadth

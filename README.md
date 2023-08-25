# 2023-IEEE-SPS-Video-and-Image-Processing-VIP-Cup

_**Phase 1:**_

The overall task is to predict the presence or absence of six different biomarkers 
simultaneously on every OCT scan in the held-out test set. The training set will consist of 
the labeled OCT scans for biomarkers and associated clinical information, along with the 
biomarker labels as ground-truth. Participants are encouraged to make use of all 
available modalities. Additionally, we will provide a testing dataset that is derived from a 
recent clinical study in collaboration with RCT. Teams will be provided with the OCT scans 
and their clinical information only for the test set. Participants will use the available data 
to predict the biomarkers associated with each OCT scan in this test set.

_**PHASE 2:**_

In PHASE 1 of the competition, each slice in the test set was treated as its own independent 
entity. However, every set of 49 slices within the test set was associated with a specific patient’s 
eye. In practice, practitioners may be interested in performance with respect to the patient’s eye, 
rather than performance with respect to isolated slices of the retina. Thus, in PHASE 2 of the 
competition we want to assess how well the model can personalize. To perform the 
personalization aspect of the competition, the invited TOP 10 TEAMS from PHASE 1 will have the 
opportunity to re-train their models and submit the same biomarker prediction csv files for each 
image in the test set.

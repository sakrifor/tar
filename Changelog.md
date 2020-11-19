# Changelog #

This is a changelog file containing all the changes made from 23/10/2019 and onwards. 


*Date - Commit Message - Description*

1. *23/10/2019* - Remove Icon Files - Removing **Icon** files from 2017-TAR folder which cause problems to GIT ().
2. *23/10/2019* - CD011134 Fix - Review Topic CD011134 in folder 2019-TAR/Task1/Training/DTA/topics/ was containing the boolean query for Task 2. It now contains the title and the objective of the topic.
3. *26/10/2019* - Removing .xml from Training/Intervention/Protocols - Removes .xml from files inside the 2019-TAR/Task1/Training/Intervention/protocols to be consistent with the filenames in the other folders.
4. *27/10/2019* - Removing CD012668 adding CD008201 from https://www.cochranelibrary.com/cdsr/doi/10.1002/14651858.CD008201.pub3/full - CD012668 protocol was removed since no qrels or topic files existed. CD008201 protocol added since the topic and qrels were present.
5. *6/11/2019* - Replacing Objectives with Objective for consistency - Replaces **Objectives** with **Objective** inside some of the DTA topic files in 2019 training dataset for consistency with other topics.
6. *7/11/2019* - Rename folder protocals to protocols - Renaming **protocals** to **protocols** inside the 2019-TAR/Task1/Testing folder.
7. *7/11/2019* - Fix protocol fields inconsistencies - Fixes protocol files inside 2019-TAR/Task1/Training that contain inconsistencies in the tags. The camelcase convention was used for naming. For example, type_of_study renamed to TypesOfStudies. 
8. *8/11/2019* - renaming task1.train.doc.2019.qrels -> task1.train.content.2019.qrels - 2019-TAR/Task1/Training/Intervention/qrels/task1.train.doc.2019.qrels renamed to 2019-TAR/Task1/Training/Intervention/qrels/task1.train.content.2019.qrels .
9. *14/11/2019* - Change 26954894 to 29136998 due to deletion of article https://www.ncbi.nlm.nih.gov/pubmed/26954894 - Article with PMID 26954894 changed to 29136998 as the first pmid is a duplicate as mentioned in https://www.ncbi.nlm.nih.gov/pubmed/26954894 .
10. *14/11/2019* - Removing 19347064 from qrel since it is not a valid PMID - Non existent PMID 19347064 removed from 2019-TAR/Task1/Training/DTA/qrels/task1.train.abs.2019.qrels .
11. *15/11/2019* - Removing CD011686 from test set, it is already in training - Removing CD011686 from test set, it is already in training set.
12. *15/11/2019* - Removing CD012164 from test set, it is already in training - Removing CD012164 from test set, it is already in training set.
13. *15/11/2019* - Removing CD011571 from test set, it is already in training - Removing CD011571 from test set, it is already in training set.
14. *8/1/2020* - Getting multiple fields - Creating extra field in 2019 DTA protocols (CD010339,CD011549,CD012019,CD012165,CD012179,CD012281) called **ObjectiveTable** to accommodate tables found in under **Objectives** field.
15. *4/3/2020* - Document Qrels Sort - Sorting qrel files from 2019 Dataset
16. *10/4/2020* - 2020 Qrel Update Task 1 Train Set - Updated qrels for 2020 Train Set. For DTA  -> 2019-TAR\Task1\Training\DTA\qrels\task1.train.new.2020.qrels and Intervention -> 2019-TAR\Task1\Training\Intervention\qrels\task1.train.new.2020.qrels
17. *10/04/2020* - 2020 Qrel Update Task 1 Test Set - Updated qrels for 2020 Test Set. For DTA  -> 2019-TAR\Task1\Testing\DTA\qrels\task1.train.new.dta.2020.qrels, Intervention -> 2019-TAR\Task1\Testing\Intervention\qrels\task1.train.new.intervention.2020.qrels, Qualitative -> 2019-TAR\Task1\Testing\Qualitative\qrels\task1.train.new.qualitative.2020.qrels and Prognosis -> 2019-TAR\Task1\Testing\Prognosis\qrels\task1.train.new.prognosis.2020.qrels
18. *3/9/2020* - Remove unnecessary protocols - Removing protocols  CD011686, CD012164, CD011571 from test set since they already exist in train set.
19. *4/9/2020* - Remove Test SRs with no PMIDS - CD011140 & CD012342 from Testing set since they don't contain any PMIDs.
20. *4/9/2020* - 2020 Update Info - New folder that contains the statistics and all the references found in the 2019 dataset




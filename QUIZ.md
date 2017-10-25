# Quiz

Answer the following questions. Add each answer in a separate commit. (E.g. fill in the answer for question 1. commit your changes. add the answer for question 2. commit your changes. add the answer for question 3. commit your changes)

1. Explain how git enables saving code.

Git enables saving code by allowing its users to group code changes into "commits". These commits display the history of the code and allow for its evolution over time to be observed and analyzed. Additionally, git allows users to navigate through previous commits/snapshots of the code and make changes or revert sections of code, as needed.

2. Explain how git enables tracking code.

Git enables tracking code by allowing its users to create and manipulate branchs of commits within a repository -- these branches are independent and allow multiple versions of the code (based on a common history) to be modified simultaneously without affecting the other branches or causing conflicts. Changes between these branches can be merged back together partially or entirely, as needed. The cumulative effect of this functionality is that complex and interdependent modifications can be performed and tracked with very little overhead, and git offers powerful tools for resolving merge conflicts and tracking the relative positions of the various branches that might exist in a repository at a given time.

3. Explain how git enables sharing code.

Git enables sharing code by including a simple system for moving commits back and forth between different versions of the same repository on different machines. A user can fetch a copy of a repository and perform local changes to the repository without having any effect on the original copy of the code, and the original copy of the code can be freely updated or even copied and modified further without affecting other versions. Changes made on a local machine can be easily pushed to other machines to update their copies of the repository, and if the remote repository has been modified since the first copy was made, the changes can be synced up by merging the newer changes to the remote repository with the local changes that need to be pushed upstream. This allows the local copy of the repository to update the remote repository without conflict, and the repository stays in a perfectly consistent state even when multiple users are accessing and modifying the code. This functionality enables effective team collaboration and allows each team member's individual work to stay closely in sync with the project as a whole.

# Tree-Augmented-Naive-Bayes
This project shows the accuracy of Tree Augmented Naive Bayes algorithm over the conventional Naive Bayes algorithm used in machine learning.

kr-vs-kp.txt file contains the chess dataset used in the project.

About the Dataset:

The dataset depicts a chess endgame where white pieces have a king and a rook and black has a king and a pawn at a7. The format for instances in this database is a sequence of 37 attribute values. Each instance is a board-description for this chess endgame. The first 36 attributes describe the board. The last (37th) attribute is the classification: “win” or “nowin”. There are 0 missing values. A typical board-description is f,f,f,f,f,f,f,f,f,f,f,f,l,f,n,f,f,t,f,f,f,f,f,f,f,t,f,f,f,f,f,f,f,t,t,n,won.
The names of the features do not appear in the board-descriptions. Instead, each feature corresponds to a particular position in the feature-value list. For example, the head of this list is the value for the feature “bkblkL black king block” . The following is the list of features, in the order in which their values appear in the feature-value list:
[bkblk,bknwy,bkon8,bkona,bkspr,bkxbq,bkxcr,bkxwp,blxwp,bxqsq,cntxt,dsopp,dwipd, hdchk,katri,mulch,qxmsq,r2ar8,reskd,reskr,rimmx,rkxwp,rxmsq,simpl,skach,skewr, skrxp,spcop,stlmt,thrsk,wkcti,wkna8,wknck,wkovl,wkpos,wtoeg]. 
There are a total of 3196 instances with 52% won by white and 48 won by black. The dataset doesn’t have missing values.


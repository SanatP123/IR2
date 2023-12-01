# IR2
Information Retrieval Project Group AYMS

Group Name : AYMS

Participants :
- Maxime Mu
- Yifan Jiang
-  Akash Garg
- Sanat Pradeep Paranjape



Build Commands :

- mvn install
  
- mvn compile


Running command :
java -cp target/cs7is3-AYMS.jar IR2.Index_Query_Eval_latest -analyser 4 -score 6

Analysers and Scoring Parameters:

-analyser

     * 1:StandardAnalyzer
     * 2:WhitespaceAnalyzer
     * 3SimpleAnalyzer
     * 4:EnglishAnalyzer
     * 5:CustomAnalyzer
     * default:EnglishAnalyzer
     
-score

     * 1:ClassicSimilarity
     * 2:BM25Similarity
     * 3:BooleanSimilarity
     * 4:LMDirichletSimilarity
     * 5:AxiomaticF2EXP
     * 6:MultiSimilarity
     * default:MultiSimilarity


Working code submitted on the VM (Sanat Paranjape's VM : @paranjas).
Best Results :

       - map = 0.3050

       - P_5 = 0.6000

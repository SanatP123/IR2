# IR2
Information Retrieval Project Group AYMS

Build Commands

mvn install
mvn compile


Running command :
java -cp target/cs7is3-AYMS.jar com.example.Index_Query_Eval_latest -analyser 4 -score 6

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
     * defaut:MultiSimilarity

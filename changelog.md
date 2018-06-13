- Changes to the Duckling 

Added 4Q16 support. Changes done in:
-Added regex in TG.Quarter in TimeGrain
-Added RuleNumericQuarterYear in Time/EN/Rules.hs. Also added the rule in the list at the end of file.
-Added the corresponding test cases in Corpus.hs

Added last quarter support in Corpus. Changes done in:
-Added the corresponding test cases in Corpus.hs

Removed quarter support for hour,minutes and seconds
-Commented the rules from being added in the list of Rules in Time/EN/Rules.hs
-Commented the corresponding test cases in Corpus.hs

Added YTD support. Changes done in:
-Added ruleIntervalYTD in Time/EN/Rules.hs. Also added the rule in the list at the end of file.
-Added the corresponding test cases in Corpus.hs

Added MTD support. Changes done in:
-Added ruleIntervalMTD in Time/EN/Rules.hs. Also added the rule in the list at the end of file.
-Added the corresponding test cases in Corpus.hs


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

Added Week1 2017 like support. Changes done in:
-Added ruleNumeralWeekYear in Time/EN/Rules.hs. Also added the rule in the list at the end of file.
-Added the corresponding test cases in Corpus.hs

Added 2017 Q3 like support. Changes done in:
-Added ruleQuarterNumeral in Time/EN/Rules.hs. Also added the rule in the list at the end of file.
-Added the corresponding test cases in Corpus.hs

Added Q3 2017 like support. Changes done in:
-Added ruleYearQuarterNumeral in Time/EN/Rules.hs. Also added the rule in the list at the end of file.
-Added the corresponding test cases in Corpus.hs




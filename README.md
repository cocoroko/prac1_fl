# prac1_fl
repository for my 1 practice work

вариант 12

найти максимальный префикс, который входит в данное слово.

задача решается динамичеким программированием, при помощи заведения трехмерного массива
dp[k][i][j] есть значение, которое имеет смысл того, что можно ли получить подслово 
от word[i...j) из регулярного выражения, соответствующего reg_expr[k] 

затем просто перебираем все возможные символы из заданного в условии алфавита, которые могут 
встретиться, и в зависимости от того, что за символ, принимаем то или иное решение

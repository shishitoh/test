# almost-prime

$k, n$について$n$未満の$k$-概素数を列挙する。almprm*.cppがアルゴリズムのメイン、数字の部分はバージョン。

------------------------------------------

## almprm1.cpp

激遅。オーダーは大体$O(n^2)$。話にならない。

## almprm2_*.cpp

$PF[i]$が$i$の素因数の個数を表すような配列$PF$を作成する方法。エラトステネスの篩の拡張とみなせる。

## almprm3_*.cpp

$k$個の素数の積のパターンを全通り作るというごり押しな方法。全通り作るのよりもその後作ったのを昇順にソートする方が大変。

## sieve.cpp

素数配列の作成、方法はエラトステネスの篩。

## merge.cpp

ソートされた複数個の配列をまとめてmergeする。「複数個の配列」の置き方によって複数種類の関数を用意してある。

## sieve_class.cpp

エラトステネスの篩を分割篩にして高速化しようとしてたやつ。分からな過ぎて途中で投げ出した。実装しなおすとしても多分最初から作り直した方が速い。
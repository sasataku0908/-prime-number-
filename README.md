素数の判定を行うプログラム

ただし、for文を用いて一つ一つの数字で剰余0になる数字があるかを探して、判定を行うと大きな数の場合に多大な時間がかかってしまう。
そこで、対象となる値の半分以上の場合は全て割り切ることができないのは明確なため為、√をして求められた値分だけfor文を回して判定を行えば半分の計算量で求めることが出来る。
今回使用した方法は、シンプルな試し割り方だが、時間があれば異なる手法でも試してみたい。

## SkipList
>  A implementation of SkipList use golang
```
test insert 1 3 5 7 9
(head)===============================>(9)===>(nil)
(head)===>(1)==========>(5)===>(7)===>(9)===>(nil)
(head)===>(1)===>(3)===>(5)===>(7)===>(9)===>(nil)
Size: 5
```

```
test insert 2 4 6 8 10
(head)======================================>(6)==========>(8)===>(9)===>(nil)
(head)===>(1)========================>(5)===>(6)===>(7)===>(8)===>(9)===>(nil)
(head)===>(1)===>(2)===>(3)===>(4)===>(5)===>(6)===>(7)===>(8)===>(9)===>(nil)
Size: 9
```
# インターフェース  
定数と抽象メソッドのみを定義できる。インターフェースを実装したクラスでは、すべてのメソッドの処理を定義できる。 
## 利用方法
```
interface Englishable {
}
class Student implements(インプレメント：実装する） Englishable　{
}
```
## イメージ  
継承は枝を張る、実装は色を塗る
抽象クラスはクラスなので継承できるのは一つだけ。インターフェースは複数実装できる。
インターフェースは継承関係のないクラス同士でも、メソッドを統一し準備できる。

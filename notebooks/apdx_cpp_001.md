# C++データ型まとめ
C++で使えるデータ型は以下の通り  
```c++
   bool b; // ブーリアン型true/falseの２値だけをとる。
   short si; // 2バイトの整数型
   int i; // 4バイトの整数型
   unsigned int ui; //4バイトの整数型、０および正の数のみ
   float f; //4バイトの浮動小数点型
   double d; //8バイトの浮動小数点型
   char c; // 文字型
```

データ型の前に`const`をつけるとその変数は定数とみなされてのちのコードで値の変更を行おうとするとエラーとなる。
```c++
   const int num = 10; //
```

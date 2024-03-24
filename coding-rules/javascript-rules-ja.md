# JavaScript Coding Rules

Javascriptの特別なコーディングルール

## Map型の利用は Record<string, any>型 （動的連想配列配列）の場合に限り使用を許可します。

Object型との混在がバグの温床となる恐れがあるため、Map型の利用を制限をします。

# Ruby Tutorial

## Object
Rubyでは、関数やクラス、モジュールなどが全てオブジェクトとして存在しています。

## 演算子
他の言語では組み込みの演算子なものがRubyではメソッドとして存在しているものが多い。

***Stringの+演算子は+()でStringクラスのインスタンスメソッドを実行している***
```ruby
p "str" + "ing"  # => "string"
p "str".+("ing") # => "string"
```

***独自の新しい演算子を定義することも可能***
```ruby
class String
  def -(other)
    #=> self と other を連結した文字列
  end
end
```

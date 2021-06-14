# Python
## 파이썬문법보는용도


## 포맷팅 문자열

### replacement_field ::=  "{" [field_name] ["!" conversion] [":" format_spec] "}"   
### field_name        ::=  arg_name ("." attribute_name | "[" element_index "]")*   
### arg_name          ::=  [identifier | digit+]   
### attribute_name    ::=  identifier   
### element_index     ::=  digit+ | index_string   
### index_string      ::=  <any source character except "]"> +   
### conversion        ::=  "r" | "s" | "a"
### format_spec       ::=  <described in the next section>   
### format_spec     ::=  [[fill]align][sign][#][0][width][grouping_option][.precision][type]
### fill            ::=  <any character>
### align           ::=  "<" | ">" | "=" | "^"
### sign            ::=  "+" | "-" | " "
### width           ::=  digit+
### grouping_option ::=  "_" | ","
### precision       ::=  digit+
### type            ::=  "b" | "c" | "d" | "e" | "E" | "f" | "F" | "g" | "G" | "n" | "o" | "s" | "x" | "X" | "%"
  
### 명시적 정렬이 주어지지 않을 때, width 필드 앞에 '0' 문자를 붙이면 숫자 형에 대해 부호를 고려하는 0 채움을 사용할 수 있습니다. 이것은 '0' 의 fill 문자와 '=' 의 alignment 유형을 갖는 것과 동등합니다.

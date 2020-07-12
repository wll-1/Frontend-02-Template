##产生式(BNF)
###练习
\<MD> ::= \<Number> | \<MD> "\*" \<Number> | \<MD> "/" \<Number> <br>
\<AD> ::= \<MD> "+" \<Number> | \<MD> "-" \<Number> <br>
\<PD> ::= "("\<AD> | \<MD>")" ("+" | "-" | "\*" | "/") "("\<AD> | \<MD>")"

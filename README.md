# ctvts - C Type Value To String - while we wait for full reflection in C++ and more

## What we want

- to_string(enum_value)
- to_string(enum_flag_combinations)
- to_string(struct_value), to_string(class_object)

- format("{}", enum_value)
- format("{}", struct_value) in various formats: human readable, including base classes, only public members, const function values, as initializers lists
- format("{}", define_value)
- format("{}", named_constexpr_const_value) - e.g. int converted to one of a series of named `constexpr int` e.g. enclosed by a namespace

- etc

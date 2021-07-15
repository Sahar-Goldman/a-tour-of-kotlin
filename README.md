# a-tour-of-kotlin

---

This repo contains a throughout walkthrough of the kotlin programing language,
created for education purposes.

The content is divided into two main parts, 'basic' and 'advanced'.

It is intended to be used as a 'bank' of kotlin examples 
followed by short explanations.


for example:

```scala
fun mix(c1: Color, c2: Color) =
    when (setOf(c1, c2)) { // calls equals
        setOf(Color.RED, Color.ORANGE) -> Color.ORANGE
        setOf(Color.YELLOW, Color.BLUE) -> Color.GREEN
        else -> throw RuntimeException("duck")
    }
    
// a when expression
// expression body dont require to use the 'return' key word
// koltin is statically typed, no need to explicitly define the return type
```

Most of the examples are short and simple, the purpose is to become familiar with kotlin idioms, syntax
and features, and be able to quickly edit/hack those examples localy and play.

partial list of kotlin "featues" :
- data classes
- nullability
- class properties
- destruction
- extension functions
- named arguments
- default arguments
- functional arguments
- lambdas with receivers
- delegeted properties
- delegated classes
- operator overloading
- collections, sequences
- high order functions
- generics
- inheritence
- dsl construction


.
.
.


Full list of topics can be infered from the project layout, as follows:

## basic kotlin
```
basics
├── p1_basics
│   ├── v_1_methods_and_variables
│   ├── v_2_classes_properties
│   ├── v_3_project_layout
│   ├── v_4_enums_when_expr
│   ├── v_5_smart_casts
│   └── v_6_iterating_over_things
├── p2_extension_functions
├── p3_classes_objects_interfaces
├── p4_lambda
└── p5_type_system

45 files
```

## advanced kotlin
```
├── p1_operator_overloading.kt
├── p2_collections_conventions.kt
├── p3_delegated_properties.kt
├── p4_high_order_functions.kt
├── p5_inline_functions.kt
├── p6_generics.kt
└── p7_generic_varience.kt
└── p8_annotations_and_reflection.kt
└── p9_dsl_constraction.kt

9 files
```


## Links
- [the art of command line](https://github.com/jlevy/the-art-of-command-line)
- [intelij cheat sheet](https://www.notion.so/viggin/kotlin-43585-c8c59b4a41ea47ffbcfedaaec2eb5f38#927e9ac0590a401da158a1d90e30d85d)
- [ace jumping](https://plugins.jetbrains.com/plugin/7086-acejump)
- [kotlin in action - book](https://www.manning.com/books/kotlin-in-action)
- [idea multi cursor editing](https://www.manning.com/books/kotlin-in-action)
- metaprograming exercise - try implementing a basic test runner engine - something that will execute methods annotated with @Testush and print a summary

## Extras
- [reactive spring with co-routines](https://spring.io/blog/2019/04/12/going-reactive-with-spring-coroutines-and-kotlin-flow)
- [kotlin spring support](https://spring.io/blog/2017/01/04/introducing-kotlin-support-in-spring-framework-5-0)
- [gradle in action - book ](https://www.manning.com/books/gradle-in-action)
- [spring in action - book](https://www.manning.com/books/spring-in-action-sixth-edition?query=spring%20in%20action)
- [spring graalvm native image](https://spring.io/blog/2020/04/16/spring-tips-the-graalvm-native-image-builder-feature)

## Extra Extras
- [spacevim](https://spacevim.org/)
- learn vim using vimtutor
- [oh my zsh + Hyoer](https://evdokimovm.github.io/windows/zsh/shell/syntax/highlighting/ohmyzsh/hyper/terminal/2017/02/24/how-to-install-zsh-and-oh-my-zsh-on-windows-10.html)


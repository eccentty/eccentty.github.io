---
published: true
layout: post
keywords: >-
  android developer, mobile developer, native languages, swift, kotlin, newbie, learning, coding, programming languages, data types, basic data types
categories:
  - EN
  - programming
  - mobile native languages
  - kotlin
  - swift
date: '2021-03-13'
comments: true
---

The company that I'm working as an android developer (using java) is going to change its mobile platform to flutter at the end of this year (2021). Since flutter is a UI framework, learning the native languages of the 2 major operating systems, should help a mobile developer to maximize the experience in developing a mobile application.

Currently I'm using Sololearn application for the Swift4 language and Coursera "Kotlin for Java Developers" course. In writing the article, I also refer to many other resources including the [official kotlin site](https://kotlinlang.org/docs/home.html) and the [official swift site](https://swift.org/documentation/). 

Searching the web, there are many advice on concentrating on just 1 language first before moving on to other languages. However, I feel that kotlin and swift have some similarities (in my beginner's opinion) so it would be interesting to learn them together. I will only be discussing the swift language and not the iOS (yet) as iOS would be another beast to conquer. 

I'm starting at the basic types of each languages and their declaration.
While I'm at it, I'm going to throw in the data types for java (existing) and dart (another language to learn) in the mix so that I won't forget them and will be able to see the diffrences as well.


| Language                 | Kotlin                                              | Swift                                                 | Dart                                   | Java                                                      |
|--------------------------|-----------------------------------------------------|-------------------------------------------------------|----------------------------------------|-----------------------------------------------------------|
| Constant                 | val                                                 | let                                                   |                                        |                                                           |
| Variable                 | var                                                 | var                                                   |                                        |                                                           |
| Data types <br><br><br>  | <br>Int, Double, Float<br>Boolean<br>String<br>Char | <br>Int, Double, Float<br>Bool<br>String<br>Character | <br>int, double, num<br>bool<br>String | <br>int, double, float, long<br>boolean<br>String<br>char |
{:.mytablestyle}


Back to only kotlin and swift. 

Both kotlin and swift are strongly typed languages. (please refer to [stackoverflow post by Norman Ramsey in 2010](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed) for the explanation on strongly typed language)

The val/var and let/var can only be used when the type can be inferred else the code cannot be compiled. In this case, you need to delare the types.


| Languages                                                                                                                                                                                                     	| Kotlin                                                                                                                                                                                                        	| Swift                                                                                                                                                                                                     	|
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Declaration                                                                                                                                                                                                   	| var x: String = "not null string variable"<br><br>var y: Int = 3                                                                                                                                              	| var x: String = "not nil string variable"<br><br>var y: Int = 3                                                                                                                                           	|
| nullable / optional <br><br>declaration<br><br><br><br>not null/nil assertion <br>(ignore null/nil check during compile time)<br><br><br><br>handling nullable/optional values<br>by assigning default values 	| <br><br>var z: String? = "string var that may be null"<br><br><br>var a: String!! = "this string maybe null but will compile" <br><br><br><br>var text: String? = null<br>val input = text ?: "default value" 	| <br><br>var z: String? = "string var that may be nil"<br><br><br>var a: String! = "this string maybe null but will compile"<br><br><br><br>var text: String? = nil<br>let input = text ?? "default value" 	|
{:.mytablestyle}



That's it for part one of this article. More to come will be comparison on other data types, etc. I'll be using this article for my own reference and hope you find this article useful as well.















<!--info-header-start--><h1>String to Union <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/> <img src="https://img.shields.io/badge/-%23union-999" alt="#union"/> <img src="https://img.shields.io/badge/-%23string-999" alt="#string"/></h1><blockquote><p>by Andrey Krasovsky <a href="https://github.com/bre30kra69cs" target="_blank">@bre30kra69cs</a></p></blockquote><p><a href="https://tsch.js.org/531/play" target="_blank"><img src="https://img.shields.io/badge/-Take%20the%20Challenge-3178c6?logo=typescript&logoColor=white" alt="Take the Challenge"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.ja.md" target="_blank"><img src="https://img.shields.io/badge/-%E6%97%A5%E6%9C%AC%E8%AA%9E-gray" alt="日本語"/></a> </p><!--info-header-end-->

Implement the String to Union type. Type take string argument. The output should be a union of input letters

For example

```ts
type Test = '123'
type Result = StringToUnion<Test> // expected to be "1" | "2" | "3"
```
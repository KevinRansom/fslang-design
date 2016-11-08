F# Language Design RFCs 
=================

RFCs and docs related to the F# language design process. The Process:

1. Use [F# Language Suggestions](https://github.com/fsharp/fslang-suggestions) to submit ideas, vote on them and discuss them.

2. Ideas which get "approved in principle" get an [RFC entry](https://github.com/fsharp/fslang-design/tree/master/RFCs) based on the [template](https://github.com/fsharp/fslang-design/blob/master/RFC_template.md), and a corresponding [RFC discussion thread](https://github.com/fsharp/fslang-design/issues)

   There is currently a backlog of approved ideas. If an idea has been approved and you'd
   like to accelerate the creation of an RFC,  send a PR creating the RFC document for any approved-in-principle issue.
   First in first served.  To "grab the token" send a PR doing nothing but creating or naming the RFC file, and
   then fill in the further details with additional commits to the PR.

3. Implementations and testing are usually submitted to the [visualfsharp](https://github.com/Microsoft/visualfsharp) repository and then integrated to [fsharp](https://github.com/fsharp/fsharp) and  [FSharp.Compiler.Service](https://github.com/fsharp/FSharp.Compiler.Service)

Completed RFCs

* [F# RFC FS-1005 - Underscore Literals](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1005-underscores-in-numeric-literals.md)
* [F# RFC FS-1008 - Struct Records](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1008-struct-records.md)
* [F# RFC FS-1002 - Cartesian product function for collections](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1002-cartesian-product-for-collections.md)
* [F# RFC FS-1009 - Allow mutually referential types and modules over larger scopes](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1009-mutually-referential-types-and-modules-single-scope.md)
* [F# RFC FS-1010 - Add Map.count](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1010-add-map-count.md)
* [F# RFC FS-1013 - Enable FSharp.Reflection functionality in PCLS](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1013-enable-reflection-functionality-on-portable-profiles.md)
* [F# RFC FS-1016 - Revise reserved keyword list](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1016-unreserve-keywords.md)
* [F# RFC FS-1012 - Support for caller info argument attributes (CallerLineNumber, CallerFileName, CallerMemberName)](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1012-caller-info-attributes.md)
* [F# RFC FS-1014 - Single case struct unions](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1014-struct-unions-single-case.md)
* [F# RFC FS-1015 - Support for "fixed"](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1015-support-for-fixed.md)
* [F# RFC FS-1017 - Allow all inferrable SRTP constraints to be written](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1017-fix-srtp-constraint-parsing.md)
* [F# RFC FS-1018 - Adjust extension method scope](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1018-adjust-extensions-method-scope.md)
* [F# RFC FS-1019 - Implicitly add the Module suffix if a type is being defined with the same name as a module](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1019-implicitly-add-the-module-suffix.md)

Nearing-Completion RFCs

* [F# RFC FS-1006 - Struct Tuples and Interop with C# 7.0 Tuples](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1006-struct-tuples.md)
* [F# RFC FS-1020 - Support byref returns](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1020-byref-returns.md)

Open RFCs

* [F# RFC FS-1001 - String interpolation](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1001-StringInterpolation.md)
* [F# RFC FS-1003 - Add nameof Operator](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1003-nameof-operator.md)
* [F# RFC FS-1007 - Additional Option module functions](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1007-additional-Option-module-functions.md)
* [F# RFC FS-1011 - Warn when recursive function is not tail-recursive](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1011-warn-on-recursive-without-tail-call.md)
* [F# RFC FS-1022 - Override  ToString  for discriminated unions and records](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1022-override-ToString-for-discriminated-unions-and-records.md)
* [F# RFC FS-1023 - Allow type providers to generate types from types](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1023-type-providers-generate-types-from-types.md)
* [F# RFC FS-1024 - Simplify call syntax for statically resolved member constraints](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1024-simplify-call-syntax-for-statically-resolved-member-constraints.md)
* [F# RFC FS-1025 - Improve record type inference](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1025-improve-record-type-inference.md)
* [F# RFC FS-1026 - Allow params dictionaries as method arguments](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1026-allow-params-dictionaries-as-method-arguments.md)



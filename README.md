# Intava Lang
Intava is a language completely parsed manually, with no regexes and simple code. Intava is a interface programming language that compiles to **Java bytecode**, **Javac compatible parsable syntax**, or use a externel code generator plugin.

## Syntax Example
```
package org.example

interface Test {
    
    #comment
    method onTestCalled with {java.lang.Object instance}, {java.lang.Object test}, {java.lang.String parameter}

    enum CalledType with {TEST}, {MAIN}

    method getCallType with {CalledType callType}

    value testValue as java.lang.Object readWrite

    value intValue as int accessible read

}

enum JVMTest with {TEST}, {JVM}
```

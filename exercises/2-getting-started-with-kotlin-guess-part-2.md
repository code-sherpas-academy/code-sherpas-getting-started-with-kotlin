# Kotlin challenge Part II - Guess what the code does
These Kotlin challenges will help you understand kotlin in detail.

###### Step 1: Recommendation. **If possible, print this document and complete the following exercise by hand. ✍️**

###### Step 2:
* Open your IDE.
* Open the project for the assignment `code-sherpas-getting-started-with-kotlin` that was generated yesterday.
* Checkout to a new branch `kotlin-challenge-part-I` created from `main`
* Open the file `2-getting-started-with-kotlin-guess-part-2.md`
* Update the file,
* Commit your changes frequently and push your code to the assignment's repository

###### How to get feedback
* Open a pull request to merge this branch into main
* Add reviewers to get feedback: @dgraciac(David Gracia) and @codesherpasrocks(Cristina Verdi)

###### How to submit your solution
* Visit the Getting Started with Kotlin module at Code Sherpas Academy
* Start the assessment for Kotilin challenge part 2
* Copy the URL for your assignment's repository and submit it in the assignment's form.

###### What is this challenge about?

See if you can guess ❓ what each line of code is doing. We’ve completed the first one to get you started:

```kotlin
    var song: String = "Who loves the sun?" // What is this line of code doing? // What is the type of 'song'?
    song = "Hey ho, let's go" // What is this line of code doing?

    val letter = 'a' // What is this line of code doing?, // What is the type of 'letter'?
    val anotherLetter: Char = 'a' // What is this line of code doing?

    val myChar = '\n' // What is this line of code doing?, // What is the type of 'mychar'?
    println(myChar) // What is this line of code doing?, What is the output of this statement?

    val myByte: Byte = 8 // What is this line of code doing?
    val myshort: Short = -32768 // What is this line of code doing?
    val myInt: Int = 346043456 // What is this line of code doing?
    val myLong: Long = 1_834_178_244_934_723_431 // What is this line of code doing?
    val myAnotherLong: Long = 3L // What is this line of code doing?

    val myDouble: Double // What is this line of code doing?
    val myFloat: Float // What is this line of code doing?
    myDouble = 345.66 // What is this line of code doing?
    myFloat = 4567.345678944423F // What is this line of code doing?

    val a = myByte.toInt() // What is the type of 'a'?
    val b = myByte.toDouble() // What is the type of 'b'?
    val c = myByte.toLong() // What is the type of 'c'?
    val d = myByte.toString() // What is the type of 'd'?

    val number = 1.23 // What is the type of 'number'? Is 'number' mutable?, why?
    val exponent = 1.5e10 // What is the type of 'exponent'? Is 'exponent' mutable?, why?

    println(3 + 7) // What is this line of code doing?
    println(myLong - 3L) // What is this line of code doing?
    println(8.43 * myDouble) // What is this line of code doing?
    println(myInt / 10) // What is this line of code doing?


    var e: Int // What is this line of code doing? What is the type of 'e'? Does it accepts 'null' values?, Is 'e' mutable?, why?
    var f: Int? // What is this line of code doing? What is the type of 'e'? Does it accepts 'null' values?

    e = 1 // What is this line of code doing? What is the type of 'e'?
    println(e) // What is this line of code doing? What is the type of 'e'? What is the output of this statement?
    e = myInt // What is this line of code doing? What is the type of 'e'?
    println(e) // What is this line of code doing? What is the type of 'e'? What is the output of this statement?

    var g: Int? = null // What is this line of code doing? What is the type of 'e'? Does it accepts 'null' values?, Is 'f' mutable?, why?

    f = 1 // What is this line of code doing? What is the type of 'e'?
    println(f) // What is this line of code doing? What is the type of 'e'? What is the output of this statement?
    f = g
    println(f) // What is this line of code doing? What is the type of 'e'? What is the output of this statement?

    var myBoolean: Boolean = true // What is this line of code doing? What is the type of 'myBoolean'?,  Is 'myBoolean' mutable?, why?
    myBoolean = false // What is this line of code doing?

    val truthy: Boolean = true // What is this line of code doing? What is the type of 'truthy'?,  Is 'truthy' mutable?, why?
    val falsy: Boolean = false // What is this line of code doing? What is the type of 'truthy'?,  Is 'truthy' mutable?, why?

    print(truthy && falsy) // What would be the output of this statement?, Why?
    print(truthy || falsy) // What would be the output of this statement?, Why?
    print(!falsy) // What would be the output of this statement?,Why?
    print(!truthy) // What would be the output of this statement?, Why?

    println(1 < 0) // What would be the output of this statement?,Why?
    println(1 > 0) // What would be the output of this statement?,Why?
    println(1 == 0) // What would be the output of this statement?,Why?
    println(1 === 1) // What would be the output of this statement?,Why?
    println(1 == 1) // What would be the output of this statement?,Why?

    val h = "ana" // What would be the output of this statement?,Why?
    val i = "ana" // What would be the output of this statement?,Why?
    println(h == i) // What would be the output of this statement?,Why?
    println(h === i) // What would be the output of this statement?,Why?

    println('a' > 'b') // What would be the output of this statement?,Why?
    println('a' >= 'b') // What would be the output of this statement?,Why?
    println('a' < 'b') // What would be the output of this statement?,Why?
    println('a' <= 'b') // What would be the output of this statement?,Why?
    println('b' < 'B') // What would be the output of this statement?,Why?
    println('b' > 'B') // What would be the output of this statement?,Why?
    println('b' <= 'B') // What would be the output of this statement?,Why?
    println('b' >= 'B') // What would be the output of this statement?,Why?
    println('B' >= 'B') // What would be the output of this statement?,Why?
    println('b' >= 'b') // What would be the output of this statement?,Why?


    println("manzana" > "patata") // What would be the output of this statement?,Why?
    println("manzana" < "patata") // What would be the output of this statement?,Why?
    println("manzana" <= "patata") // What would be the output of this statement?,Why?
    println("manzana" >= "patata") // What would be the output of this statement?,Why?
    println("manzana" == "patata") // What would be the output of this statement?,Why?
    println("manzana" != "patata") // What would be the output of this statement?,Why?

    val inty = Integer(1) 
    val noh = Integer(1)

    println(inty == noh) // What would be the output of this statement?,Why?
    println(inty === noh) // What would be the output of this statement?,Why?

    for(char in "manzana") println(char) // What is this line of code doing? What would be the output of this statement?

// What is the expression below doing? What would be the output of this expression?
    for (char in "pera") {  
        println(char)
    }
    
    for (number in 2..7) println(number)// What is this line of code doing? What would be the output of this statement?
    for (element in 10 downTo 3) println(element)// What is this line of code doing? What would be the output of this statement?
    for (item in 10 downTo 0 step 2) println(item) // What is this line of code doing? What would be the output of this statement?

```
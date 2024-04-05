# Learn_JavaScript

JavaScript Learning ....

    ==> Reference Video == > [ https://www.youtube.com/watch?v=toymwoKBtbM&list=PLla-GdVgzZZV-z0Gxc7rkrV4cuqYSNZMy&index=3 ]

# Topic 1 - Intro : ( about:blank ) => Basic console task.

    => JS (JavaScript) is an lightWeight interpreter programming language with first class creation.While it is most well-known as the
    scripting language for Web pages , many non-browser environment. Dynamically Script Language

        ==> INTERPRETER :

            -> Directly executes instructions written in a programming or scripting language.
            -> There are 4 ways to implement the code.
            -> JavaScript is "JUST-IN-TIME" compiler.

        ==> First Class Creation :

            -> Assigned to Variables.
            -> Passed as arguments.
            -> Returned from other functions.
            -> Stored in data structures.
            -> Dynamic creation.

        ==> Dynamically Script Language :  A programming language where the type checking is performed at runtime rather than at compile time.

    ==> alert ( window object - first prefernce ) : alert( "welcome" )

    ==> Type of Writting JS :

        -> Internal JS  (
            <script>

                code here ...

            </script>
        )

        -> External JS ( <script src=" path of JS file "></script> )

    => COMMENT LINE :

        ==> // Single line comment
        ==> /* Multi-line comment */

    => Variables : Scripting languages serve as placeholders for storing data during program execution.

        ==> Variable Syntax : (variable variableName)

        -> var ( used in es5 )

            => Reassign and Redeclare.

        -> let ( lanched in es6 )

            => Redeclare. can't Reassign the value.

        -> const

            => Can't change the value. can't Reassign and Redeclare the value.

        ==>  Variable Declaration : ( variable variableName )

        ==> Variable Initialization : ( variable variableName = value )

    => DATA TYPE (A data type is a classification that specifies which type of value a variable can hold).

        ==> Primitive-Data-Type :

            -> String ( inside the "double quotes" )
            -> Number ( numeric value )
            -> Boolean ( true or false )
            -> Undefined ( not assign the value )
            -> Null ( represents an intentional absence of a value )

        ==> Non-Primitive-Data-Type :

            -> Array ( Store multiple values in a single variable. )
            -> Object ( An object is a collection of properties, and a property is an association between a name (or key) and a value )

        ==> typrof() : ( which type of datatype. )

# Topic 2 - String : => String , String Properties and String Methods.

    => String ( inside the "double quotes" )

    => String Properties :

        -> length ( variableName.length ) :

            => How many characters in the particular variable including space.

    => String Methods :

        -> charAt() ( variableName.charAt(posistion) ) :

            => Start with " 0 ".
            => That represent the posistion character will be print.
            => Nothing to mention the posistion automatically consider as a " Posistion 0 "
            => ur posistion value higher then the " length-1 " can't display the output

        -> indexOf() ( variableName.indexOf( " inside character value " ) ) :

            => Start with " 0 ".
            => check the first occurence of the variable.
            => check the character inside the variable. and posistion of the character.
            => Nothing to mention the posistion automatically consider as a " Posistion 0 "
            => given the character not in the variable returns the output " -1 ".

        -> lastIndexOf() ( variableName.lastIndexOf ( " inside character value " ) ) :

            => Start with " 0 ".
            => check the last occurence of the variable.
            => check the character inside the variable. and posistion of the character.
            => Nothing to mention the posistion automatically consider as a " Posistion 0 "
            => given the character not in the variable returns the output " -1 ".

        -> slice() ( variableName.slice ( startingPoint  to endingPoint -1 ) ) :

            => Start with " 0 ".
            => cut the variable startingPoint to endingPoint.
            => Not giving the endingPoint print startingPoint to rest of the characters.
            => endingPoint value doesn't show.

        -> toUpperCase() ( variableName.toUpperCase() )

            => Each character shoule be convert into upperCase.
        
        -> toLowerCase() ( variableName.toLowerCase() )

            => Each character shoule be convert into LowerCase.

        -> includes() ( variableName.includes( "string value" ) )

            => return "Boolean" value
            => is the given string value inside the variable the return the true.
            => not mention anything return true.

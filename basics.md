## iOS Dev

## Shortcuts

  - command + "+" or  "-" to increase/decrease text
  - command + control+ drag to link UI to code
  - option + click file to view as assistant editor 


## Variables 

var variableName: dataType = value

```
var score:Int = 10
```

## Constants

let constantName: dataType = value

```
let hoursInADay:Int = 24
```


## Prinitng integers on lables which only accepst Strings

  - IB stands for interface builder
  - ! means you cannot store a value in it

```
@IBOutlet weak var label: UILabel!

var score:Int = 10

label.text = "Score: \(score) "

```


## Creating your own data types: enum

  - assign enum values with a preceeding " . "

enum datatypeName 
{
  case caseName1
  case caseName1
}

```
enum modes
{
  case noMode
  case addition
  case subtraction
 
}


var mode:modes = .addition
```

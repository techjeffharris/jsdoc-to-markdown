#Index

**Modules**

* [amd/export-object](#module_amd/export-object)
  * [amd/export-object.sayHello()](#module_amd/export-object.sayHello)
* [file-pet](#module_file-pet)
  * [class: FilePet ⏏](#exp_module_file-pet)
    * [new FilePet(num)](#exp_new_module_file-pet)
    * [filePet.instie](#module_file-pet#instie)
    * [filePet.files](#module_file-pet#files)
    * [filePet.delete(paths)](#module_file-pet#delete)
* [jacket](#module_jacket)
  * [class: Jacket ⏏](#exp_module_jacket)
    * [jacket.zip()](#module_jacket#zip)
* [file-set](#module_file-set)
  * [class: FileSet ⏏](#exp_module_file-set)
    * [new FileSet()](#exp_new_module_file-set)
    * [file-set.files](#module_file-set#files)
    * [file-set.delete(paths)](#module_file-set#delete)
* [function-tools](#module_function-tools)
  * [function-tools.one()](#module_function-tools.one)
* [sum-alias](#module_sum-alias)
  * [sum(a, b) ⏏](#exp_module_sum-alias)
* [commonjs/function](#module_commonjs/function)
  * [module.exports(one, two) ⏏](#exp_module_commonjs/function)
* [commonjs/ignore](#module_commonjs/ignore)
  * [ignore.visible](#module_commonjs/ignore.visible)
* [commonjs/object-alias](#module_commonjs/object-alias)
  * [_.one](#module_commonjs/object-alias.one)
  * [_.two](#module_commonjs/object-alias.two)
  * [_.three()](#module_commonjs/object-alias.three)
* [cyberdyne](#module_cyberdyne)
  * [cyber~something](#module_cyberdyne..something)
  * [cyber.createMachine()](#module_cyberdyne.createMachine)
  * [class: cyber~Machine](#module_cyberdyne..Machine)
    * [new cyber~Machine(options)](#new_module_cyberdyne..Machine)
    * [machine.eyes](#module_cyberdyne..Machine#eyes)
    * [machine.vibe](#module_cyberdyne..Machine#vibe)
* [cattle](#module_cattle)
  * [cattle~innerMember](#module_cattle..innerMember)
  * [cattle.createCow()](#module_cattle.createCow)
  * [cattle~innerFuction()](#module_cattle..innerFuction)
  * [~~cattle~anotherInnerFuction()~~](#module_cattle..anotherInnerFuction)
* [one-member](#module_one-member)
  * [object.three(four, five)](#module_one-member.three)
* [heaven](#module_heaven)
  * [heaven.Cloud](#module_heaven.Cloud)
  * [heaven.createCloud()](#module_heaven.createCloud)
  * [const: heaven~FACT](#module_heaven..FACT)
  * [class: heaven~Cloud](#module_heaven..Cloud)
    * [new heaven~Cloud(options)](#new_module_heaven..Cloud)
    * [cloud.size](#module_heaven..Cloud#size)
    * [cloud.rain](#module_heaven..Cloud#rain)
    * [Cloud.classMethod()](#module_heaven..Cloud.classMethod)
    * [const: Cloud.SPACES](#module_heaven..Cloud.SPACES)
* [private](#module_private)
  * [private.notprivate](#module_private.notprivate)
* [commonjs/single-value](#module_commonjs/single-value)
  * [module.exports ⏏](#exp_module_commonjs/single-value)
* [foo/bar](#module_foo/bar)
  * [foo/bar~linkFunction()](#module_foo/bar..linkFunction)
  * [event: "event:MyEvent"](#module_foo/bar.event_MyEvent)
  * [class: foo/bar~LinkClass](#module_foo/bar..LinkClass)
    * [new foo/bar~LinkClass()](#new_module_foo/bar..LinkClass)
    * [linkClass.foo](#module_foo/bar..LinkClass#foo)
  * [foo/bar~String](#external_String)

**Classes**

* [~~class: All~~](#All)
  * [~~new All(input, [options])~~](#new_All)
  * [all.topping](#All#topping)
  * [all.size](#All#size)
  * [~~all.allThings(one, two)~~](#All#allThings)
    * [allThings~some](#All#allThings..some)
* [class: Person](#Person)
  * [new Person()](#new_Person)
* [class: Car](#Car)
  * [new Car([options])](#new_Car)
* [class: Pipe](#Pipe)
* [~~class: Everything~~](#Everything)
  * [~~new Everything(input, [options])~~](#new_Everything)
* [class: Rice](#Rice)
  * [event: "cooked"](#Rice#event_cooked)
  * [event: "cooking"](#Rice#event_cooking)
* [class: Something](#Something)
  * [something.methodOne()](#Something#methodOne)
  * [~~something.allTogether(one, two)~~](#Something#allTogether)
* [class: Pizza](#Pizza)
  * [pizza.topping](#Pizza#topping)
  * [pizza.size](#Pizza#size)
* [class: Hurl](#Hurl)
  * [hurl.snowball()](#Hurl#snowball)
  * [event: "snowball"](#Hurl#event_snowball)
* [class: Plucker](#Plucker)
  * [plucker.doPluck(one, ...args, ...three)](#Plucker#doPluck)

**Namespaces**

* [car](#car)
  * [car.wheels](#car.wheels)
  * [car.sensors](#car.sensors)
  * [car.start()](#car.start)
  * [car.env](#car#env)
    * [env.weather](#car#env.weather)
    * [env.roads](#car#env.roads)
* [config](#config)

**Constants**

* [const: CONST_ONE](#CONST_ONE)
* [~~const: CONST_TWO~~](#CONST_TWO)

**Functions**

* [read(filename, done)](#read)
* [customTaggedFunction()](#customTaggedFunction)
* [globalFunc()](#globalFunc)
* [exampled()](#exampled)
* [multiExampled()](#multiExampled)
* [_protected()](#_protected)
* [withAuthor()](#withAuthor)
* [~~oldFunction()~~](#oldFunction)
* [newFunction()](#newFunction)
* [withParam(one)](#withParam)
* [withParams(one, two)](#withParams)
* [withOptional(one, [two])](#withOptional)
* [withBullets(one, two)](#withBullets)
* [returnsSomething()](#returnsSomething)
* [returnsSomethingDesc()](#returnsSomethingDesc)
* [returnsSeveral()](#returnsSeveral)
* [~~allTogether(one, two)~~](#allTogether)
* [doSomething(options)](#doSomething)
* [doAnother(options)](#doAnother)
* [pluck(...prop)](#pluck)
* [requirer()](#requirer)
* [setMagicNumber(x)](#setMagicNumber)
* [doSomething(options)](#doSomething)

**Members**

* [enum: eFileType](#eFileType)
  * [eFileType.NOEXIST](#eFileType.NOEXIST)
  * [eFileType.FILE](#eFileType.FILE)
  * [eFileType.DIR](#eFileType.DIR)
* [visible](#visible)
* [variable](#variable)
* [typed](#typed)
* [types](#types)
* [exampled](#exampled)
* [examples](#examples)
* [_protected](#_protected)
* [withAuthor](#withAuthor)
* [hasDefault](#hasDefault)
* [hasDefaultObject](#hasDefaultObject)
* [~~deprecated~~](#deprecated)
* [readOnly](#readOnly)
* [hasSince](#hasSince)
* [something](#something)
* [another](#another)

**Typedefs**

* [callback: onComplete](#onComplete)
* [type: NumberLike](#NumberLike)
 
<a name="module_amd/export-object"></a>
#amd/export-object
A module that says hello!

<a name="module_amd/export-object.sayHello"></a>
##amd/export-object.sayHello()
Say hello.

<a name="module_file-pet"></a>
#file-pet
this module returns a pet of files

**Example**  
```js
var cowFiles = FilePet("cow/*");
```

<a name="exp_module_file-pet"></a>
##class: FilePet ⏏
this class returns a pet of files

**Members**

* [class: FilePet ⏏](#exp_module_file-pet)
  * [new FilePet(num)](#exp_new_module_file-pet)
  * [filePet.instie](#module_file-pet#instie)
  * [filePet.files](#module_file-pet#files)
  * [filePet.delete(paths)](#module_file-pet#delete)

<a name="exp_new_module_file-pet"></a>
###new FilePet(num)
this is the contructor

**Params**

- num `number` - the input number  

**Example**  
```js
var cowFiles = FilePet("cow/*");
```


<a name="module_file-pet#instie"></a>
###filePet.instie
an instance ting

<a name="module_file-pet#files"></a>
###filePet.files
the prototype instance property

**Type**: `boolean`  
**Default**: `true`  
<a name="module_file-pet#delete"></a>
###filePet.delete(paths)
A prototype instance methy meth

**Params**

- paths `array` - the paths to delete  

<a name="module_jacket"></a>
#jacket
A module representing a jacket.

<a name="exp_module_jacket"></a>
##class: Jacket ⏏
**Members**

* [class: Jacket ⏏](#exp_module_jacket)
  * [jacket.zip()](#module_jacket#zip)

<a name="module_jacket#zip"></a>
###jacket.zip()
Open and close your Jacket.

<a name="module_file-set"></a>
#file-set
this module exports a class constructor

**Example**  
```js
var FileSet = require("file-set");
```

<a name="exp_module_file-set"></a>
##class: FileSet ⏏
this class returns a set of files

**Members**

* [class: FileSet ⏏](#exp_module_file-set)
  * [new FileSet()](#exp_new_module_file-set)
  * [file-set.files](#module_file-set#files)
  * [file-set.delete(paths)](#module_file-set#delete)

<a name="exp_new_module_file-set"></a>
###new FileSet()
Takes a list of path patterns

**Params**

-  `Array.<string>` - a list of file patterns  

**Example**  
```js
var cowFiles = new FileSet("cow/*");
```

<a name="module_file-set#files"></a>
###file-set.files
the prototype instance property

<a name="module_file-set#delete"></a>
###file-set.delete(paths)
A prototype instance methy meth

**Params**

- paths `array` - the paths to delete  

<a name="module_function-tools"></a>
#function-tools
This is the module description

<a name="module_function-tools.one"></a>
##function-tools.one()
the main function description

<a name="module_sum-alias"></a>
#sum-alias
This module exports a simple maths function

**Example**  
```js
var sum = require("sum-alias");
```

<a name="exp_module_sum-alias"></a>
##sum(a, b) ⏏
Sums two numbers together

**Params**

- a `number` - first number  
- b `number` - second number  

**Returns**: `number` - the result  
**Example**  
```js
var result = sum(1, 1);
```

<a name="module_commonjs/function"></a>
#commonjs/function
This is the module description

**Since**: v0.10.28  
**Author**: Lloyd <75pound@gmail.com>  
<a name="exp_module_commonjs/function"></a>
##module.exports(one, two) ⏏
the main function description

**Params**

- one `string` - The input string  
- two `object` - a second input  

**Returns**: `object` | `string` - this return has several types  
<a name="module_commonjs/ignore"></a>
#commonjs/ignore
module with ignored shiz

<a name="module_commonjs/ignore.visible"></a>
##ignore.visible
visible property

<a name="module_commonjs/object-alias"></a>
#commonjs/object-alias
simple object export

**Members**

* [commonjs/object-alias](#module_commonjs/object-alias)
  * [_.one](#module_commonjs/object-alias.one)
  * [_.two](#module_commonjs/object-alias.two)
  * [_.three()](#module_commonjs/object-alias.three)

<a name="module_commonjs/object-alias.one"></a>
##_.one
first property

<a name="module_commonjs/object-alias.two"></a>
##_.two
second property

<a name="module_commonjs/object-alias.three"></a>
##_.three()
a function

<a name="module_cyberdyne"></a>
#cyberdyne
exports an object.. has an inner class.

**Example**  
```js
var cyber = require("cyberdyne");
```

**Members**

* [cyberdyne](#module_cyberdyne)
  * [cyber~something](#module_cyberdyne..something)
  * [cyber.createMachine()](#module_cyberdyne.createMachine)
  * [class: cyber~Machine](#module_cyberdyne..Machine)
    * [new cyber~Machine(options)](#new_module_cyberdyne..Machine)
    * [machine.eyes](#module_cyberdyne..Machine#eyes)
    * [machine.vibe](#module_cyberdyne..Machine#vibe)

<a name="module_cyberdyne..something"></a>
##cyber~something
random

**Scope**: inner member of [cyberdyne](#module_cyberdyne)  
<a name="module_cyberdyne.createMachine"></a>
##cyber.createMachine()
**Returns**: [Machine](#module_cyberdyne..Machine)  
<a name="module_cyberdyne..Machine"></a>
##class: cyber~Machine
The main class of machine

**Members**

* [class: cyber~Machine](#module_cyberdyne..Machine)
  * [new cyber~Machine(options)](#new_module_cyberdyne..Machine)
  * [machine.eyes](#module_cyberdyne..Machine#eyes)
  * [machine.vibe](#module_cyberdyne..Machine#vibe)

<a name="new_module_cyberdyne..Machine"></a>
###new cyber~Machine(options)
the Machine constructor

**Params**

- options `object` - constructor options  

**Scope**: inner class of [cyberdyne](#module_cyberdyne)  
<a name="module_cyberdyne..Machine#eyes"></a>
###machine.eyes
**Type**: `number`  
<a name="module_cyberdyne..Machine#vibe"></a>
###machine.vibe
**Type**: `string`  
<a name="module_cattle"></a>
#cattle
exported object, with-inner-members

**Members**

* [cattle](#module_cattle)
  * [cattle~innerMember](#module_cattle..innerMember)
  * [cattle.createCow()](#module_cattle.createCow)
  * [cattle~innerFuction()](#module_cattle..innerFuction)
  * [~~cattle~anotherInnerFuction()~~](#module_cattle..anotherInnerFuction)

<a name="module_cattle..innerMember"></a>
##cattle~innerMember
the inner member

**Scope**: inner member of [cattle](#module_cattle)  
<a name="module_cattle.createCow"></a>
##cattle.createCow()
**Returns**: `boolean`  
<a name="module_cattle..innerFuction"></a>
##cattle~innerFuction()
the inner function

**Scope**: inner function of [cattle](#module_cattle)  
<a name="module_cattle..anotherInnerFuction"></a>
##~~cattle~anotherInnerFuction()~~
another inner function

***Deprecated***  
**Scope**: inner function of [cattle](#module_cattle)  
<a name="module_one-member"></a>
#one-member
simple object, one member. It shouldn't have an index.

<a name="module_one-member.three"></a>
##object.three(four, five)
a function

**Params**

- four `string` - The input string  
- five `object` - a second input  

**Returns**: `object` | `string` - this return has several types  
**Since**: v0.10.28  
**Author**: Lloyd <75pound@gmail.com>  
**Example**  
```js
allTogether(true);
```

<a name="module_heaven"></a>
#heaven
factory module creating dodgy cloud. object-with-static-class.

**Members**

* [heaven](#module_heaven)
  * [heaven.Cloud](#module_heaven.Cloud)
  * [heaven.createCloud()](#module_heaven.createCloud)
  * [const: heaven~FACT](#module_heaven..FACT)
  * [class: heaven~Cloud](#module_heaven..Cloud)
    * [new heaven~Cloud(options)](#new_module_heaven..Cloud)
    * [cloud.size](#module_heaven..Cloud#size)
    * [cloud.rain](#module_heaven..Cloud#rain)
    * [Cloud.classMethod()](#module_heaven..Cloud.classMethod)
    * [const: Cloud.SPACES](#module_heaven..Cloud.SPACES)

<a name="module_heaven.Cloud"></a>
##heaven.Cloud
access to the Cloud class

**Type**: [Cloud](#module_heaven..Cloud)  
<a name="module_heaven.createCloud"></a>
##heaven.createCloud()
**Returns**: [Cloud](#module_heaven..Cloud)  
<a name="module_heaven..FACT"></a>
##const: heaven~FACT
an inner constant

**Scope**: inner constant of [heaven](#module_heaven)  
**Type**: `boolean`  
<a name="module_heaven..Cloud"></a>
##class: heaven~Cloud
The main class for a cloud

**Members**

* [class: heaven~Cloud](#module_heaven..Cloud)
  * [new heaven~Cloud(options)](#new_module_heaven..Cloud)
  * [cloud.size](#module_heaven..Cloud#size)
  * [cloud.rain](#module_heaven..Cloud#rain)
  * [Cloud.classMethod()](#module_heaven..Cloud.classMethod)
  * [const: Cloud.SPACES](#module_heaven..Cloud.SPACES)

<a name="new_module_heaven..Cloud"></a>
###new heaven~Cloud(options)
cloud constructor

**Params**

- options `object` - the options  

**Scope**: inner class of [heaven](#module_heaven)  
<a name="module_heaven..Cloud#size"></a>
###cloud.size
**Type**: `number`  
**Default**: `4`  
<a name="module_heaven..Cloud#rain"></a>
###cloud.rain
**Type**: `boolean`  
**Default**: `false`  
<a name="module_heaven..Cloud.classMethod"></a>
###Cloud.classMethod()
a class method

<a name="module_heaven..Cloud.SPACES"></a>
###const: Cloud.SPACES
a class constant

**Type**: `number`  
<a name="module_private"></a>
#private
module with private shiz

<a name="module_private.notprivate"></a>
##private.notprivate
visible property

<a name="module_commonjs/single-value"></a>
#commonjs/single-value
this module exports one value, that's it

<a name="module_foo/bar"></a>
#foo/bar
A module. Refer to it using [foo/bar](#module_foo/bar).

**Members**

* [foo/bar](#module_foo/bar)
  * [foo/bar~linkFunction()](#module_foo/bar..linkFunction)
  * [event: "event:MyEvent"](#module_foo/bar.event_MyEvent)
  * [class: foo/bar~LinkClass](#module_foo/bar..LinkClass)
    * [new foo/bar~LinkClass()](#new_module_foo/bar..LinkClass)
    * [linkClass.foo](#module_foo/bar..LinkClass#foo)
  * [foo/bar~String](#external_String)

<a name="module_foo/bar..linkFunction"></a>
##foo/bar~linkFunction()
See `LinkClass` and `LinkClass#foo`.
Also check out [Google](http://www.google.com) and [GitHub](http://github.com).

**Scope**: inner function of [foo/bar](#module_foo/bar)  
<a name="module_foo/bar.event_MyEvent"></a>
##event: "event:MyEvent"
An event. Refer to with [event:MyEvent](#module_foo/bar.event_MyEvent).

<a name="module_foo/bar..LinkClass"></a>
##class: foo/bar~LinkClass
**Members**

* [class: foo/bar~LinkClass](#module_foo/bar..LinkClass)
  * [new foo/bar~LinkClass()](#new_module_foo/bar..LinkClass)
  * [linkClass.foo](#module_foo/bar..LinkClass#foo)

<a name="new_module_foo/bar..LinkClass"></a>
###new foo/bar~LinkClass()
A class.

**Scope**: inner class of [foo/bar](#module_foo/bar)  
<a name="module_foo/bar..LinkClass#foo"></a>
###linkClass.foo
foo property

<a name="All"></a>
#~~class: All~~
a class with all of the things

**Extends**: `Number`  
**Members**

* [~~class: All~~](#All)
  * [~~new All(input, [options])~~](#new_All)
  * [all.topping](#All#topping)
  * [all.size](#All#size)
  * [~~all.allThings(one, two)~~](#All#allThings)
    * [allThings~some](#All#allThings..some)

<a name="new_All"></a>
##~~new All(input, [options])~~
the constructor description

**Params**

- input `object` - an input  
- \[options\] `object` - optional shit  

***Deprecated***  
**Extends**: `Number`  
**Since**: v0.10.28  
**Author**: 75lb <75pound@gmail.com>  
**Example**  
```js
var yeah = new Everything(true);
```

<a name="All#topping"></a>
##all.topping
the ingredients on top

**Type**: `string`  
**Default**: `mud, lettuce`  
**Since**: v1.0.0  
<a name="All#size"></a>
##all.size
the general size

<a name="All#allThings"></a>
##~~all.allThings(one, two)~~
This function has all tags set

**Params**

- one `string` - The input string  
- two `object` - a second input  

***Deprecated***  
**Returns**: `object` | `string` - this return has several types  
**Since**: v0.10.28  
**Author**: Lloyd <75pound@gmail.com>  
**Example**  
```js
all.allTogether(true);
```

<a name="Person"></a>
#class: Person
simple class description

**Extends**: `Object`  
**Members**

* [class: Person](#Person)
  * [new Person()](#new_Person)

<a name="new_Person"></a>
##new Person()
a constructor description

**Extends**: `Object`  
<a name="Car"></a>
#class: Car
**Members**

* [class: Car](#Car)
  * [new Car([options])](#new_Car)

<a name="new_Car"></a>
##new Car([options])
a constructor with args

**Params**

- \[options\] `object` - optional shit  

<a name="Pipe"></a>
#class: Pipe
a class which extends

**Extends**: `Pipe`  
**Members**

* [class: Pipe](#Pipe)

<a name="Everything"></a>
#~~class: Everything~~
a class with all trimmings

**Extends**: `Pipe`  
**Members**

* [~~class: Everything~~](#Everything)
  * [~~new Everything(input, [options])~~](#new_Everything)

<a name="new_Everything"></a>
##~~new Everything(input, [options])~~
the constructor description

**Params**

- input `object` - an input  
- \[options\] `object` - optional shit  

***Deprecated***  
**Extends**: `Pipe`  
**Since**: v0.10.28  
**Author**: 75lb <75pound@gmail.com>  
**Example**  
```js
var yeah = new Everything(true);
```

<a name="Rice"></a>
#class: Rice
**Members**

* [class: Rice](#Rice)
  * [event: "cooked"](#Rice#event_cooked)
  * [event: "cooking"](#Rice#event_cooking)

<a name="Rice#event_cooked"></a>
##event: "cooked"
Fired when rice is ready

<a name="Rice#event_cooking"></a>
##event: "cooking"
Fired when rice is cooking

<a name="Something"></a>
#class: Something
**Members**

* [class: Something](#Something)
  * [something.methodOne()](#Something#methodOne)
  * [~~something.allTogether(one, two)~~](#Something#allTogether)

<a name="Something#methodOne"></a>
##something.methodOne()
method description

<a name="Something#allTogether"></a>
##~~something.allTogether(one, two)~~
This function has all tags set

**Params**

- one `string` - The input string  
- two `object` - a second input  

***Deprecated***  
**Returns**: `object` | `string` - this return has several types  
**Since**: v0.10.28  
**Author**: Lloyd <75pound@gmail.com>  
**Example**  
```js
something.allTogether(true);
```

<a name="Pizza"></a>
#class: Pizza
**Members**

* [class: Pizza](#Pizza)
  * [pizza.topping](#Pizza#topping)
  * [pizza.size](#Pizza#size)

<a name="Pizza#topping"></a>
##pizza.topping
the ingredients on top

**Type**: `string`  
**Default**: `mud, lettuce`  
**Since**: v1.0.0  
<a name="Pizza#size"></a>
##pizza.size
the general size

<a name="Hurl"></a>
#class: Hurl
**Members**

* [class: Hurl](#Hurl)
  * [hurl.snowball()](#Hurl#snowball)
  * [event: "snowball"](#Hurl#event_snowball)

<a name="Hurl#snowball"></a>
##hurl.snowball()
Throw a snowball.

<a name="Hurl#event_snowball"></a>
##event: "snowball"
Snowball event.

**Properties**

- isPacked `boolean` - Indicates whether the snowball is tightly packed.  

**Type**: `object`  
<a name="Plucker"></a>
#class: Plucker
**Members**

* [class: Plucker](#Plucker)
  * [plucker.doPluck(one, ...args, ...three)](#Plucker#doPluck)

<a name="Plucker#doPluck"></a>
##plucker.doPluck(one, ...args, ...three)
This function takes variable input

**Params**

- one `string` - an input  
- ...args `string` - the property(s) as input  
- ...three `string` - more input  

<a name="car"></a>
#car
**Members**

* [car](#car)
  * [car.wheels](#car.wheels)
  * [car.sensors](#car.sensors)
  * [car.start()](#car.start)
  * [car.env](#car#env)
    * [env.weather](#car#env.weather)
    * [env.roads](#car#env.roads)

<a name="car.wheels"></a>
##car.wheels
the round things

<a name="car.sensors"></a>
##car.sensors
the electronics that always go wrong

<a name="car.start"></a>
##car.start()
start the car

**Params**

-  `string`  
-  `function`  

<a name="car#env"></a>
##car.env
decribes the current conditions

**Members**

* [car.env](#car#env)
  * [env.weather](#car#env.weather)
  * [env.roads](#car#env.roads)

<a name="car#env.weather"></a>
###env.weather
what kind of day is it

**Type**: `string`  
**Default**: `choppy`  
<a name="car#env.roads"></a>
###env.roads
road condition

**Type**: `string`  
**Default**: `wet`  
<a name="config"></a>
#config
**Properties**

- defaults `object` - The default values for parties.  
  - defaults.players `number` - The default number of players.  
  - defaults.level `string` - The default level for the party.  
  - defaults.treasure `object` - The default treasure.  
  - defaults.treasure.gold `number` - How much gold the party starts with.  

**Members**

* [config](#config)

<a name="read"></a>
#read(filename, done)
**Params**

- filename `string` - the filename  
- done <code>[onComplete](#onComplete)</code> - the callback  

<a name="customTaggedFunction"></a>
#customTaggedFunction()
this function has a wonderful custom tag

<a name="globalFunc"></a>
#globalFunc()
a global function

<a name="exampled"></a>
#exampled()
a function with an example

**Example**  
```js
var result = exampled();
```

<a name="multiExampled"></a>
#multiExampled()
a function with multiple examples

**Example**  
```js
var another = 100;
```

**Example**  
```js
var next = "p";
```

<a name="_protected"></a>
#_protected()
**Access**: protected  
<a name="withAuthor"></a>
#withAuthor()
**Author**: Clive Jones <clive@jones.com>  
<a name="oldFunction"></a>
#~~oldFunction()~~
***Deprecated***  
<a name="newFunction"></a>
#newFunction()
**Since**: v0.10.28  
<a name="withParam"></a>
#withParam(one)
**Params**

- one `string` - The input string  

<a name="withParams"></a>
#withParams(one, two)
**Params**

- one `string` - The input string  
- two `object`  

<a name="withOptional"></a>
#withOptional(one, [two])
**Params**

- one `string` - The input string  
- \[two\] `object` - this one is optional  

<a name="withBullets"></a>
#withBullets(one, two)
this description has 

- bullet
- points

and needs this line to separate the above list from the below

**Params**

- one `string` - The input string  
- two `object` - a second input  

<a name="returnsSomething"></a>
#returnsSomething()
**Returns**: `string`  
<a name="returnsSomethingDesc"></a>
#returnsSomethingDesc()
**Returns**: `object` - this return has a description  
<a name="returnsSeveral"></a>
#returnsSeveral()
**Returns**: `object` | `string` - this return has several types  
<a name="allTogether"></a>
#~~allTogether(one, two)~~
This function has all tags set

**Params**

- one `string` - The input string  
- two `object` - a second input  

***Deprecated***  
**Returns**: `object` | `string` - this return has several types  
**Since**: v0.10.28  
**Author**: Lloyd <75pound@gmail.com>  
**Example**  
```js
allTogether(true);
```

<a name="doSomething"></a>
#doSomething(options)
**Params**

- options `object` - the function options  
  - one `string` - first option  
  - two `string` - second option  

<a name="doAnother"></a>
#doAnother(options)
**Params**

- options `Object` - the function options  

<a name="pluck"></a>
#pluck(...prop)
This function takes variable input

**Params**

- ...prop `string` - the property(s) as input  

<a name="requirer"></a>
#requirer()
ensure you have some-module installed

<a name="setMagicNumber"></a>
#setMagicNumber(x)
Set the magic number.

**Params**

- x <code>[NumberLike](#NumberLike)</code> - The magic number.  

<a name="doSomething"></a>
#doSomething(options)
**Params**

- options `object` - the function options  
  - one `string` - first option  
  - two `string` - second option  

<a name="eFileType"></a>
#enum: eFileType
Enum for the `type` value

**Type**: `number`  
**Properties**: `NOEXIST`, `FILE`, `DIR`  
**Read only**: true  
<a name="visible"></a>
#visible
a visible global

<a name="variable"></a>
#variable
a global variable

<a name="typed"></a>
#typed
**Type**: `string`  
<a name="types"></a>
#types
**Type**: `string` | `number`  
<a name="exampled"></a>
#exampled
a var with an example

**Example**  
```js
var another = 100;
```

<a name="examples"></a>
#examples
a var with multiple examples

**Example**  
```js
var another = 100;
```

**Example**  
```js
var next = "p";
```

<a name="_protected"></a>
#_protected
**Access**: protected  
<a name="withAuthor"></a>
#withAuthor
**Author**: Clive Jones <clive@jones.com>  
<a name="hasDefault"></a>
#hasDefault
**Default**: `23`  
<a name="hasDefaultObject"></a>
#hasDefaultObject
**Default**: `{"one":1,"two":2}`  
<a name="deprecated"></a>
#~~deprecated~~
***Deprecated***  
<a name="readOnly"></a>
#readOnly
**Read only**: true  
<a name="hasSince"></a>
#hasSince
**Since**: v0.10.28  
<a name="something"></a>
#something
this is for something

**Type**: `string`  
<a name="another"></a>
#another
this is for something else

**Type**: `string`  
<a name="onComplete"></a>
#callback: onComplete
Called when an async operation completes

**Params**

- err `object` - an error, or `null`  
- result `string` - the result info  

**Type**: `function`  
<a name="NumberLike"></a>
#type: NumberLike
A number, or a string containing a number.

**Type**: `number` | `string`  
<a name="CONST_ONE"></a>
#const: CONST_ONE
the first important constant

**Type**: `number`  
<a name="CONST_TWO"></a>
#~~const: CONST_TWO~~
This variable has all tags set

***Deprecated***  
**Type**: `boolean`  
**Read only**: true  
**Since**: v0.10.28  
**Author**: Lloyd Brookes <lloyd@brookes.com>  
**Example**  
```js
var CONST_TWO = true;
```


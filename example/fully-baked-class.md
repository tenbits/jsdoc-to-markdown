## Classes
<dl>
<dt><a href="#FurQ">FurQ</a> ⇐ <code><a href="#Rapper">Rapper</a></code></dt>
<dd><p>C*ck, b!tch, c*ck, b!tch, m*therf!cker. You gotta kill people, to respect people.</p>
</dd>
<dt><a href="#Rapper">Rapper</a></dt>
<dd></dd>
</dl>
## Functions
<dl>
<dt><a href="#plant">plant()</a></dt>
<dd><p>to plant ones fist in a buster&#39;s mush</p>
</dd>
</dl>
<a name="FurQ"></a>
## FurQ ⇐ <code>[Rapper](#Rapper)</code>
C\*ck, b!tch, c\*ck, b!tch, m\*therf!cker. You gotta kill people, to respect people.

**Extends:** <code>[Rapper](#Rapper)</code>  
**Scope**: global class  
**Emits**: <code>[pop](#FurQ#event_pop)</code>, <code>[slap](#FurQ#event_slap)</code>  
**Access:** public  
**See**: https://www.youtube.com/watch?v=1sxZ4tsp8gc  
**Author:** Chris Morris  

* [FurQ](#FurQ) ⇐ <code>[Rapper](#Rapper)</code>
  * [new FurQ()](#new_FurQ_new)
  * _instance_
    * [.wannaTryIt](#FurQ#wannaTryIt) : <code>string</code>
    * [.LOVE](#FurQ#LOVE) : <code>string</code>
    * [.spit()](#FurQ#spit)
    * [.battle()](#Rapper#battle)
    * [.punch()](#FurQ#punch)
    * ["pop" (zoop)](#FurQ#event_pop)
    * ["slap"](#FurQ#event_slap)
    * _standard_
      * [.kill()](#FurQ#kill)
      * [.respect(done)](#FurQ#respect)
  * _static_
    * [.enemy](#FurQ.enemy) : <code>number</code>
    * ~~[.peace()](#FurQ.peace)~~
  * _inner_
    * [~onRespect](#FurQ..onRespect) : <code>function</code>

<a name="new_FurQ_new"></a>
### new FurQ()
She's an Uzi lover. 

![uzi](https://sampleface.co.uk/wp-content/uploads/2013/07/fur-q-uzi-lover.png)

**Example**  
```js
var uziLover = require("FurQ");
```
<a name="FurQ#wannaTryIt"></a>
### furQ.wannaTryIt : <code>string</code>
**Default**: <code>&quot;bitch&quot;</code>  
**Scope**: instance property of <code>[FurQ](#FurQ)</code>  
**See**

- "Uzi like a metal dick in my hand."
- "Magazine like a big testicle gland."

<a name="FurQ#LOVE"></a>
### furQ.LOVE : <code>string</code>
**Default**: <code>&quot;UZI&quot;</code>  
**Scope**: instance constant of <code>[FurQ](#FurQ)</code>  
<a name="FurQ#spit"></a>
### furQ.spit()
override

**Scope**: instance method of <code>[FurQ](#FurQ)</code>  
**Overrides:** <code>[spit](#Rapper#spit)</code>  
<a name="FurQ#punch"></a>
### furQ.punch()
to plant ones fist in a buster's mush

**Scope**: instance method of <code>[FurQ](#FurQ)</code>  
<a name="FurQ#event_pop"></a>
### "pop" (zoop)
fire weapon

**Scope**: event emitted by <code>[FurQ](#FurQ)</code>  

| Param | Type | Description |
| --- | --- | --- |
| zoop | <code>boolean</code> | make 'zooping' sound as you fire |

<a name="FurQ#event_slap"></a>
### "slap"
slap man

**Scope**: event emitted by <code>[FurQ](#FurQ)</code>  
<a name="FurQ#kill"></a>
### furQ.kill()
kill

**Scope**: instance method of <code>[FurQ](#FurQ)</code>  
**Category**: standard  
**Example**  
```js
var kill = uziLover.kill();
    
```
**Example**  
```js
uziLover.kill();
```
<a name="FurQ#respect"></a>
### furQ.respect(done)
respect

**Scope**: instance method of <code>[FurQ](#FurQ)</code>  
**Category**: standard  

| Param | Type | Description |
| --- | --- | --- |
| done | <code>[onRespect](#FurQ..onRespect)</code> | called on reciprocation of respect |

**Example**  
```js
uziLover.respect(function(err, gain){
    console.log(gain);
});
```
<a name="FurQ.enemy"></a>
### FurQ.enemy : <code>number</code>
FUR-Q enemy types

**Scope**: static enum property of <code>[FurQ](#FurQ)</code>  
**Read only**: true  
**Properties**

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| COCK | <code>number</code> | <code>0</code> | an awful individual |
| BITCH | <code>number</code> | <code>1</code> |  |
| MUTHAFUCKA | <code>number</code> | <code>2</code> |  |

<a name="FurQ.peace"></a>
### ~~FurQ.peace()~~
***Deprecated***

check if at peace

**Scope**: static method of <code>[FurQ](#FurQ)</code>  
**Example**  
```js
var peace = FurQ.peace();
```
<a name="FurQ..onRespect"></a>
### FurQ~onRespect : <code>function</code>
Passed to [respect](#FurQ#respect)

**Scope**: inner typedef of <code>[FurQ](#FurQ)</code>  

| Param | Type | Description |
| --- | --- | --- |
| err | <code>Error</code> | an issue with the punch |
| gain | <code>\*</code> | the respect percentage gained |

<a name="Rapper"></a>
## Rapper
**Scope**: global class  

* [Rapper](#Rapper)
  * _instance_
    * [.spit()](#Rapper#spit)
    * [.battle()](#Rapper#battle)
  * _static_
    * [.train()](#Rapper.train)
      * [~School](#Rapper.train..School)
        * [new School()](#new_Rapper.train..School_new)
        * [.bestStudent](#Rapper.train..School#bestStudent)

<a name="Rapper#spit"></a>
### rapper.spit()
spit

**Scope**: instance method of <code>[Rapper](#Rapper)</code>  
<a name="Rapper#battle"></a>
### rapper.battle()
battle

**Scope**: instance method of <code>[Rapper](#Rapper)</code>  
<a name="Rapper.train"></a>
### Rapper.train()
train new rappers

**Scope**: static method of <code>[Rapper](#Rapper)</code>  

  * [.train()](#Rapper.train)
    * [~School](#Rapper.train..School)
      * [new School()](#new_Rapper.train..School_new)
      * [.bestStudent](#Rapper.train..School#bestStudent)

<a name="Rapper.train..School"></a>
#### train~School
**Scope**: inner class of <code>[train](#Rapper.train)</code>  

* [~School](#Rapper.train..School)
  * [new School()](#new_Rapper.train..School_new)
  * [.bestStudent](#Rapper.train..School#bestStudent)

<a name="new_Rapper.train..School_new"></a>
##### new School()
rap school

<a name="Rapper.train..School#bestStudent"></a>
##### school.bestStudent
best student

**Scope**: instance property of <code>[School](#Rapper.train..School)</code>  
<a name="plant"></a>
## plant()
to plant ones fist in a buster's mush

**Scope**: global function  
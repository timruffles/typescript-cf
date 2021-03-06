## Prologue
{state:'title'}

## Javascript
{class:'notitle'}

```javascript
function improveUserExperience() {
  if(prompt("Do you love Javascript yet?") !== "yes")
    improveUserExperience();
}

improveUserExperience();
```

<aside class=notes>
TypeScript is part of the JS ecosystem
</aside>

## Interactivity

![behaviour](src/img/behaviour.gif)


## JS is a 'dynamic' language

## Static vs dynamic

## Static vs dynamic
{class:'notitle'}

![tab sp](src/img/tab-spaces.jpg)

## Self-image
{class:'notitle'}

![mac-pc](src/img/self-image.png)

## Q-Basic
{class:"q-basic"}

```
10 PRINT "Tim is cool"
20 GOTO 10
```

<aside class=notes>
I started out with dynamic
</aside>

## HTML + CSS + JS
{class:'notitle'}

![24-hours](src/img/24-hours.jpg)

## It was wonderful, then...

## Horror

## C++
{class:'notitle'}

![c++](src/img/cpp.png)

## C++
{class:'notitle'}

![win+](src/img/win.png)

## Java
{class:'notitle'}

![ugly](src/img/ugly.png)

## Ruby
{class:'notitle'}

![picklive](src/img/picklive_homepage.png)

## _why
{class:'notitle'}

![why](src/img/why.png)

## Java
{class:'notitle'}

```java
// A generic greeting program
public class HelloWorld{
  private static HelloWorld instance;

  public static void main(String[] args){
    instantiateHelloWorldMainClassAndRun();
  }

  public static void instantiateHelloWorldMainClassAndRun(){
    instance = new HelloWorld();
  }

  public HelloWorld(){
    HelloWorldFactory factory =
      HelloWorldFactory.getInstance();
    IHelloWorld helloWorld = 
      factory.createHelloWorld();
    IHelloWorldString helloWorldString =
      helloWorld.getHelloWorld();
    IPrintStrategy printStrategy =
      helloWorld.getPrintStrategy();
    IStatusCode code = helloWorld.print(
      printStrategy, helloWorldString);
    if(code.getStatusCode() != 0){
      throw new RuntimeException("Failed to print: " 
        + code.getStatusCode());
    }
  }
}
```

## Many have tried to kill JS
{class:'noshadow'}

![replace](src/img/replace-js.png)

## JS started ugly

> JS had to "look like Java" only less so, be Java's dumb kid brother or boy-hostage sidekick.

> Plus, I had to be done in ten days or something worse than JS would have happened.

## But people loved it

> Any application that can be written in JavaScript, will eventually be written in JavaScript

Jeff Atwood

## So all have failed

## This was the status quo...

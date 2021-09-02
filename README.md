# The 0777 JS Challange

### Welcome to the `0777` JavaScript Challange!

## Story

The JavaScript world is in Danger! The Evil king of the Bugs is destroying the codes written in js making them useless. You are being choosen by the JavaScript Community to go and fight the bug king so that the JavaScript developers can again live a happy and peaceful life. 

You Enter the Bug Territory and secretly managed to reach the control centre of the bug king. Now you see here and there and you find that there is a large source of energy that powers the Bug King and other bug Army. If could turn off the power supply, the Bug Army and The Bug King would die. Making the JavaScript Community Bug Free.

You head on to the power source and see something there. It is a JavaScript Pass Lock. It accepts JavaScript Code as Input and if the code meets certain criteria then you will get the access.

You go a bit closer to the source and in the Pass Lock Display you see 
```javascript
function key(){
  var passKey;
  // Write The Javascript Here and Return The Key
  console.log(passKey);
  console.log(typeof(passKey));
}
```
Still you are thinking how to crack the lock that you see something on the floor. 

It was the manual to open The Pass Lock.

The Following was written in the manual:

**To Open The Pass Lock You have to `console log` the `0777`. There is only criteria that the type of the the returned value should be `number` nothing else.**

Once you write the correct code you would be able to deactivate the power source and save the community!

So all in your hands!
Good Luck!

## Problem

Given the code

```javascript
function key(){
  var passKey;
  // Write The Javascript Here and Log as Following
  console.log(passKey); // Should log 0777
  console.log(typeof(passKey)); // Should log "number"
}
```
You have to log the value such that when logged to the console the output should be `0777`. And the type of the logged value should be `number`.

In Points:
* console output should be `0777`
* typeof the value should be `number`

## Test Cases

your code will be tested as follows:
```javascript
function key(){
  var passKey;
  // Write The Javascript Here and Log as Following
  console.log(passKey);
  console.log(typeof(passKey));
}
// Should Output Following:
// 0777
// "number"
```

> The code will be also tested by a human for correct validation.

## Constraints:

* Lines of Code Should Not be greater than 10 lines (After formatting the code with 2 indentions).
* The code would be run in the console of the `chrome Dev Tools` with version `92.0.4515.159 (Official Build) (64-bit) (cohort: Stable)` on the inspected `https://google.com` site.

## Submission

Submit your code by the following google form:


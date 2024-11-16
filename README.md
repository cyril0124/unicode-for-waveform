# unicode-for-wavefom
This repo consists of unicode characters that can be used for drawing waveform in your code comment.

Also, this repo is not going to introduce every unicode character and waveform examples are provided instead for simplicity.

```C
// 
// A: XXX, T: XXX, R: XXX
// 
// mode:    <--------T----->|<------R------>|<---T-->|<----------A---------->|<--T-->|<------R------>
// clk:  ___/⎺⎺⎺\___/⎺⎺⎺\___/⎺⎺⎺⎺\___/⎺⎺⎺\___/⎺⎺⎺\___/⎺⎺⎺\___/⎺⎺⎺\___/⎺⎺⎺\___/⎺⎺⎺\___/⎺⎺⎺\___/⎺⎺⎺\___
// req:  ___/⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺\_______________________________/⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺
// ack:  ___________________/⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺\_______________________________/⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺
// rdy:  ⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺\_______________________________/⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺
//                                   ↑                              ↑
//                                   |                              |
//     Xxxxxxxxxxxxxxxxxxxxxxxxxxx. _/                               \_ Xxxxxxxxxxxxxxxxxxxxxxxxx.
//     Xxxxxxxxxxxxxxxxxxxxxxxxxxx.                                     Xxxxxxxxxxxxxxxxxxxxxxxxx.
//  
```

```C
//
// clock: __|````|___|````|___|````|___|````|___
// ready:	__|`````````````|_____________________
// valid:	________________|````````|____________
// 						            |
// 						   	        | <--- Xxxxxxxxxxxxxxxx.
//

//
// clock: __|````|___|````|___|````|___|````|___
// ready:	___________|````````|_________________
// valid:	__|``````````````````````|____________
// 								            |
// 								            | <--- Xxxxxxxxxxxxxxx.
//
```

WIP...

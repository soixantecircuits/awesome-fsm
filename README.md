# Awesome FSM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/DFAexample.svg/500px-DFAexample.svg.png" align="right" width="100">](https://en.wikipedia.org/wiki/Finite-state_machine)

> Useful resources for creating apps that use the [finite state machine](https://en.wikipedia.org/wiki/Finite-state_machine) pattern

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.*

## Préambule 🌭

Finite state machine won't save the world. This pattern address issues where you want to drive a user from a point A to Z following various state. Thus make sure you really need a state machine before using one. But also make sure you won't need one, because most of the time **you will**.
We have **four rules** that leads this design:

1. The state machine is defined by a finite number of states
2. This states are triggered by conditions
3. Each conditions shapes **transition**
4. The machine is in **only one state at a time**; we call it the current state

## Interesting reading about state machine 📖

- [FSM and event driven programming](http://www.robert-drummond.com/2015/04/21/event-driven-programming-finite-state-machines-and-nodejs/)

> FSM can be simply compared to somebody with amnesia who is constantly asking:
> Where am I?
> What just happened?
> and…
>
> So what do I do (or where do I go) next?

*Robert Drummond*

- [State design pattern](http://www.dofactory.com/javascript/state-design-pattern)

> Two other examples where the State pattern is useful include: vending machines that dispense products when a correct combination of coins is entered, and elevator logic which moves riders up or down depending on certain complex rules that attempt to minimize wait and ride times.

*dofactory*

- [Hacker news thread](https://news.ycombinator.com/item?id=2949543)

> This man has never heard of video game A.I. programming :)

*davedx*

- [gameprogrammingpatterns.com](http://gameprogrammingpatterns.com/state.html)

> There’s nothing to prevent “air jumping” — keep hammering B while she’s in the air, and she will float forever. The simple fix is to add an isJumping_ Boolean field to Heroine that tracks

*Robert Nystrom*

- [Why developers never use state machines](http://www.skorks.com/2011/09/why-developers-never-use-state-machines/)

> We Don't Need One Until We Do
> So, early on you don't feel like your objects' state machine behaviour is complex enough to warrant a **"full-blown"** state machine (YAGNI and all that jazz), but later on – **when it IS complex enough** – you feel like you've invested too much time/effort to replace it with something that has equivalent functionality

*Alan Skorkin*

- [About React and State Machine](https://facebook.github.io/react/docs/interactivity-and-dynamic-uis.html)

> React thinks of UIs as simple state machines.



## Libraries 📚

- State.js: https://github.com/steelbreeze/state.js [<img src="https://img.shields.io/npm/dt/state.js.svg" align="right">](https://www.npmjs.com/package/state.js)
- Machina.js: https://github.com/ifandelse/machina.js [<img src="https://img.shields.io/npm/dt/machina.svg" align="right">](https://www.npmjs.com/package/machina)
- Javascript State Machine: https://github.com/jakesgordon/javascript-state-machine [<img src="https://img.shields.io/npm/dt/javascript-state-machine.svg" align="right">](https://www.npmjs.com/package/javascript-state-machine)
- Promise State Machine: https://github.com/patbenatar/promise-state-machine [<img src="https://img.shields.io/npm/dt/promise-state-machine.svg" align="right">](https://www.npmjs.com/package/promise-state-machine)
- Chine: https://github.com/mtabini/chine [<img src="https://img.shields.io/npm/dt/chine.svg" align="right">](https://www.npmjs.com/package/chine)
- Machineto: https://github.com/itkoren/machineto [<img src="https://img.shields.io/npm/dt/machineto.svg" align="right">](https://www.npmjs.com/package/machineto)
- Makina: https://github.com/atabel/makina [<img src="https://img.shields.io/npm/dt/makina.svg" align="right">](https://www.npmjs.com/package/makina)
- StateJS: https://github.com/hufyhang/state-js [<img src="https://img.shields.io/npm/dt/state-js.svg" align="right">](https://www.npmjs.com/package/state-js)
- Mistic: https://github.com/benaston/mistic [<img src="https://img.shields.io/npm/dt/mistic.svg" align="right">](https://www.npmjs.com/package/mistic)
- fluent-state-machine: https://github.com/nickuraltsev/fluent-state-machine [<img src="https://img.shields.io/npm/dt/fluent-state-machine.svg" align="right">](https://www.npmjs.com/package/fluent-state-machine)
- Bon Etat: https://github.com/gausby/bon-etat [<img src="https://img.shields.io/npm/dt/bon-etat.svg" align="right">](https://www.npmjs.com/package/bon-etat)
- Hierarchical-fsm: https://github.com/cassiozen/State-Machine [<img src="https://img.shields.io/npm/dt/hierarchical-fsm.svg" align="right">](https://www.npmjs.com/package/hierarchical-fsm)
- iFsm - jQuery: https://github.com/intersel/iFSM [<img src="https://img.shields.io/npm/dt/ifsm.svg" align="right">](https://www.npmjs.com/package/ifsm)
- State flow: https://github.com/philipdev/stateflow [<img src="https://img.shields.io/npm/dt/stateflow.svg" align="right">](https://www.npmjs.com/package/stateflow)

## Examples

TODO 🛠








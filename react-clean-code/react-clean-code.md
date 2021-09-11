# React Clean Code

by Juntao@Thoughtworks



## What is clean code

![cetus](react-clean-code/cetus.png)


> Any one can write code that a computer can understand. Good programmers write code that humans can understand. — Martin Fowler


## Unclean code

**unclean** means not easy to understand

- Long file
- Hard to test
- Hard to change
- Misleading names (`setCetus`)
- Not following general principles


### Large file

- Big function body
- Big props list (not quite relevant props)
- Passing data through


### Hard to test 

- Overly use mocks
- Long setup steps
- Verifying behaviors instead of data


### Hard to change

- Have to change a lot of other things


### Naming

- Misleading names - incorrect terms usage
- Outdated - when the function changed


### Difficult to change

- Have to make a lot of preparation
- Break a lot of other things


## Clean code

- The file is normally short 
- The component is easy to test / change
- They have meaningful names
- Following general OO principles 



## Clean up techniques


## General principles

- Small component
- Move JavaScript out of your JSX/TSX
	- util / helper function - no mock
	- separate hooks
	- context
	- render props (composable)
- OO principles
	- S.O.L.I.D
	- Simple Design


## General principles

![solid](react-clean-code/solid.png)



## Refactoring

- Make sure tests are solid and correct
- Small steps first (move, rename)
- Practice makes progress - IDE shortcuts


## Demo time
<!-- .slide: data-background-color="#CA7822" -->


## Code snippets

![portion-line](react-clean-code/portion-line.png)


## Code snippets

![voucher-lin](react-clean-code/voucher-line.png)


### Some other examples

-  `voucher-input.tsx`
-  `order-details-card.tsx`



## Other references

- [Clean code by Uncle Bob](https://blog.cleancoder.com/)
- [Refactor by Martin](https://martinfowler.com/articles/refactoring-2nd-ed.html)
- [Composition in React](https://javascript.plainenglish.io/did-someone-say-composition-c7843d898b2)
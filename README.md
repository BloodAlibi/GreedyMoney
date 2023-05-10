# Greedy Money
**Greedy Money is a Python tool to decompose a large number in smaller fixed ones.** For instance, it will return 50;20;2;1 if you ask for 73.

## How to use

You enter the number you want, and it will return the least fixed values decomposing it.

![image](https://github.com/BloodAlibi/Greedy_Money/assets/66722031/8ea6f470-f082-46bb-89c3-7e19944a32ab)

Please note that values can only be changed in the source file (Py).


## Real life Use

In today's world, we sometimes use cash to pay. Unless we want to empty our wallet from the dozens of coins we have, it may be useful to give the least cash/coins.
Without noticing it, our brain will automatically make the required operation. In fact, it can be giving 50€ and 20€ to pay 70€, instead of 50€ and 10€ twice.

## Aglorithm

This script is based on the famous Greedy Algorithm. It will simply choose the biggest value to remove from the number. For instance, if we only have as values : 50, 20 and 10 ; we can for 70 first remove 50, then 20.
To make it work in most cases, we need to make sure our number can be decomposed with the chosen values. If we for example have 78 as number, we won't be able to decompose it with 50, 20 and 10. The use of small values, such as 2 and 1, will allow us to treat more precise numbers, such as 45, 26, 91, ... It would be the same with decimal numbers (1, 2, and 10 can't decompose 0.86 ; but 0.1, 0.4 can).

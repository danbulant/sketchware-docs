---
title: Control blocks
id: control
---

Control blocks have a yellow color and are used to check for condition or repeat part of code.

## Repeat (number)

Repeat block is used to repeat the blocks inside x times, where x is the number parameter. Can be stopped before it repeats all time with stop block, which will skip remaining loops and continue after the repeat block.

## Forever

Forever block is used to repeat the blocks inside until it's stopped with a stop block. *Compilation will not work if forever block doesn't have a stop block.* Please keep in mind, that **your app will be unusable if forever block doesn't run stop (for example when used with if<false>)**.

## Stop

Stop block can be placed only inside repeat and forever blocks. It will immediately stop the execution of the block and skip *after* the end of repeat/forever.

## If<bool>

If block is used to run blocks inside it only when bool is true. You can use bool variable or use operator blocks.

## If<bool> else

The if-else block works like if, but if the bool is false, it will execute blocks inside else instead.

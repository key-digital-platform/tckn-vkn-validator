# What is this?

This is TCKN and VKN validator which available in Turkey.

# How to install

`npm i tckn-vkn-validator --save`

Then...

```
import { isTcNoValid, isTaxNoValid } from 'tckn-vkn-validator'

isTcNoValid(12345678901); // => true || false
isTaxNoValid(1234567890); // => true || false

```

# Introduction 

## what is it?

SVD (System view Description) format is the standardized format to describe peripherals, registers, interrupts and other important things that has to be taken into consideration when developing low-level code for MCUs.

## why it exists?

  It provides source of truth for code-generators, debuggers and other tools that have to know how internals of MCUs are organized. It's intended to by readable mainly for such a software, not necessarily for humans.

# Examples of tools operating on SVD files

[svd2rust](https://github.com/rust-embedded/svd2rust): Tool for generating [[PAC]]s that allows rust code to operate on MCU's registers

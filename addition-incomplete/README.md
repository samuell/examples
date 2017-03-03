# Addition Example

## Usage

This is an incomplete version of our addition example to be used along with the following tutorial: http://docs.reconfigure.io/tutorial_2_addition.html.

## Structure

This directory contains a kernel located at `main.go`. It also has a
command, `test-addition`, located at `cmd/test-addition/main.go`.

## Testing

To run this example in a simulator, execute the following:

```
reco-jarvice test test-addition
```

This will simulate the kernel using a hardware simulator, and test it
using the `test-addition` command.

## Building

```
reco-jarvice build
```

This will build your commands and kernel for execution on hardware.

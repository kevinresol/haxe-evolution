# Feature name

* Proposal: [HXP-NNNN](NNNN-inline-enum-declaration.md)
* Author: [kevinresol](https://github.com/kevinresol)

## Introduction

Allow declaring enum in a inlined fashion for one-off use. Example:

```haxe
public function pronounForGender(gender:{Male; Female;}) {
	switch gender {
		case Male: 'he';
		case Female: 'she';
	}
}

```

## Motivation

Inlining the declaration reduces the number of single-use Types in the codebase.
It also reduces the effort of thinking names for them.

## Detailed design

TODO:

> Describe the proposed design in details the way language user can understand
and compiler developer can implement. Show corner cases, provide usage examples,
describe how this solution is better than current workarounds.

## Impact on existing code

TODO:

> What impact this change will have on existing code? Will it break compilation?
Will it compile, but break in run-time? How easy it is to migrate existing Haxe code?

## Drawbacks

TODO:

> Describe the drawbacks of the proposed design worth consideration. This doesn't include
breaking changes, since that's described in the previous section.

## Alternatives

TODO:

> What alternatives have you considered to address the same problem, why the proposed solution is better?

## Unresolved questions

TODO:

> Which parts of the design in question is still to be determined?

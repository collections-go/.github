# collections-go

## Mission

**To provide a minimal set of data structures missing from the standard
library that are reasonable to write now that we have generics, while
keeping the code and philosophy as idiomatic as possible.**

## Who Are We?

We're founded by two experienced and anti-dependency engineers who believe
many projects overuse libraries to their detriment only to experience
dependency hell, and strongly believe that [a little copying is better than a
little dependency][dep].

That said, how many times have you used a `map[string]bool` or more
cumbersomely but effecient `map[string]struct{}` when you really just wanted a
set? I've even aliased it before and then wrote union and intersect operators.

This organizations tends to provide a few minimal datastructures like a
`Set[T]` written in well-tested truly idiomatic Go to make your life a little
easier.

## State

This is just the beginning of an experiment to see if we actually can build something useful, thinking of datastructures beyond just the `Set[T]` type. Let's see where this takes us!

[dep]: https://go-proverbs.github.io/#:~:text=A%20little%20copying%20is%20better%20than%20a%20little%20dependency.
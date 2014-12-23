# Abstract

This is my thoughts on something; quite possibly sparse arrays or entity systems.


# Motivation

When handling entity systems, entities are commonly identified by `id`s.


# Unsorted

- Hash maps have near-constant lookup while only accessing memory a few times.
    - Sorted binary search is `O(log n)` accessing memory just as often ... given the arrays is always sorted at least.
    - But the memory might be littered with empty buckets making iteration slower?
    - Hash map lookup requires key lookup rather than array indexing.

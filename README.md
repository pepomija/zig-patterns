# Zig Patterns
A list of links to code references showing common patterns in Zig.

## Goals
* This document lives!  Please make frequent updates.
* Beware of bitrot! Look at the date of the entry and/or the version of zig referenced
* Context Matters! Links to working code examples, for example the zig standard library, are preferred
* Inclusive over canonical! Prefer showing different approaches side-by-side instead of annoiting a "best" approach.

## Patterns
### Arena Allocator
* [0.13.0/lib/std/heap/arena_allocator.zig#L8](https://github.com/ziglang/zig/blob/0.13.0/lib/std/heap/arena_allocator.zig#L8)

### Closure
* [0.13.0/zig/lib/std/Thread/Pool.zig#L93](https://github.com/ziglang/zig/blob/0.13.0/lib/std/Thread/Pool.zig#L93)

### Comptime String Interning
* [zig.news - Cool Zig Patterns - Comptime String Interning](https://zig.news/xq/cool-zig-patterns-comptime-string-interning-3558)

### Context
* [0.13.0/zig/lib/std/hash_map.zig#L128](https://github.com/ziglang/zig/blob/0.13.0/lib/std/hash_map.zig#L128)

### Custom Type Format
* [0.13.0/lib/std/Uri.zig#L43](https://github.com/ziglang/zig/blob/0.13.0/lib/std/Uri.zig#L43)

### Default Argument Values
* [0.13.0/lib/std/fmt.zig#L23](https://github.com/ziglang/zig/blob/0.13.0/lib/std/fmt.zig#L23)

### Deferred Resource Deinitialization
*[0.13.0/lib/std/once.zig#L31](https://github.com/ziglang/zig/blob/0.13.0/lib/std/once.zig#L31)

### Diagnostics
* [zig.news - Applying the Diagnostics pattern in practice](https://zig.news/cancername/applying-the-diagnostics-pattern-in-practice-21ja)

### Dynamic Dispatch (Fat Pointer)
* [0.13.0/lib/std/mem/Allocator.zig#L14](https://github.com/ziglang/zig/blob/0.13.0/lib/std/mem/Allocator.zig#L14)

### Error Deferred Resource Deinitialization
*[0.13.0/lib/std/tz.zig#L92](https://github.com/ziglang/zig/blob/0.13.0/lib/std/tz.zig#L92)

### Field Parent Pointer
* [0.13.0/lib/std/Thread/Futex.zig#L647](https://github.com/ziglang/zig/blob/0.13.0/lib/std/Thread/Futex.zig#L647)

### File Struct
* [0.13.0/lib/std/Thread.zig#L25](https://github.com/ziglang/zig/blob/0.13.0/lib/std/Thread.zig#L25)

### Generic Function
* [0.13.0/lib/std/mem.zig#L1188](https://github.com/ziglang/zig/blob/0.13.0/lib/std/mem.zig#L1188)

### Generic Type
* [0.13.0/lib/std/hash_map.zig#L360](0.13.0/lib/std/hash_map.zig#L360)

### Interfaces
* [openmymind.net - Zig Interfaces](https://www.openmymind.net/Zig-Interfaces/)
* [zig-interface](https://github.com/nilslice/zig-interface)

### Memory Pool - Fast Allocation
* [Cool Zig Patterns - Gotta alloc fast](https://zig.news/xq/cool-zig-patterns-gotta-alloc-fast-23h)

### Static Dispatch (Tagged Union)
* [zig.news - Easy Interfaces with Zig 0.10.0](https://zig.news/xq/cool-zig-patterns-305o)

### Static Error Absence Guarantee
*[0.13.0/lib/std/hash_map.zig#L1563](https://github.com/ziglang/zig/blob/0.13.0/lib/std/hash_map.zig#L1563)

### Struct of Arrays
* [zig.news - Multi-Object For Loops + Struct-Of-Arrays](https://zig.news/andrewrk/multi-object-for-loops-data-oriented-design-41ob)

### WaitGroup + ThreadPool
* [0.13.0/lib/compiler/build_runner.zig#L890](https://github.com/ziglang/zig/blob/0.13.0/lib/compiler/build_runner.zig#L890)

### Web Request
* [Zig.news - Easy web requests in Zig with Client.fetch](https://zig.news/andrewgossage/easy-web-requests-in-zig-with-clientfetch-k43)

## References
Many thanks to all the blog posts that served as references
* [ziggit.dev - Zig Patterns](https://ziggit.dev/t/zig-patterns/1748)
* [zig.news - Cool Zig Patterns Series' Articles](https://zig.news/xq/series/10)
* [Mitchell Hashimoto - Zig](https://mitchellh.com/zig)

## TODO
* Support Patterns links to blog posts with links to working code on github

# GCC 14.1.0: C++ Standard Library

## Overview

A repo containing the libstdc++-v3 folder from the main GCC GitHub repo
which can be found here:
[https://github.com/gcc-mirror/gcc](https://github.com/gcc-mirror/gcc)

*Please note: the tag/release 14.1.0 was used to minimise the repo size.*

## Folder structure

```txt
📂 /include
├── 📂 bits
│   ├── 📄 algorithmfwd.h
│   ├── 📄 alloc_traits.h
│   ├── 📄 allocator.h
│   ├── 📄 allocator_traits.h
│   ├── 📄 basic_ios.h
│   ├── 📄 basic_string.h
│   ├── 📄 char_traits.h
│   ├── 📄 codecvt.h
│   ├── 📄 cstring
│   ├── 📄 deque.tcc
│   ├── 📄 exception.h
│   ├── 📄 forward_list.h
│   ├── 📄 hash_bytes.h
│   ├── 📄 initializer_list.h
│   ├── 📄 ios_base.h
│   ├── 📄 iostream.h
│   ├── 📄 istream.tcc
│   ├── 📄 list.tcc
│   ├── 📄 map.tcc
│   ├── 📄 mask_array.h
│   ├── 📄 matrix.h
│   ├── 📄 move.h
│   ├── 📄 numeric.h
│   ├── 📄 ostream.tcc
│   ├── 📄 ptr_traits.h
│   ├── 📄 queue.tcc
│   ├── 📄 random.h
│   ├── 📄 set.tcc
│   ├── 📄 shared_ptr.h
│   ├── 📄 sstream.tcc
│   ├── 📄 stl_algo.h
│   ├── 📄 stl_bvector.h
│   ├── 📄 stl_construct.h
│   ├── 📄 stl_deque.h
│   ├── 📄 stl_function.h
│   ├── 📄 stl_heap.h
│   ├── 📄 stl_iterator.h
│   ├── 📄 stl_list.h
│   ├── 📄 stl_map.h
│   ├── 📄 stl_multimap.h
│   ├── 📄 stl_multiset.h
│   ├── 📄 stl_numeric.h
│   ├── 📄 stl_queue.h
│   ├── 📄 stl_set.h
│   ├── 📄 stl_stack.h
│   ├── 📄 stl_uninitialized.h
│   ├── 📄 stl_vector.h
│   ├── 📄 stringfwd.h
│   ├── 📄 type_traits.h
│   ├── 📄 unordered_map.h
│   ├── 📄 utility.h
│   ├── 📄 vector.tcc
├── 📂 debug
│   ├── 📄 debug.h
│   ├── 📄 formatter.h
│   ├── 📄 hash_policy.h
│   ├── 📄 safe_base.h
│   ├── 📄 safe_iterator.h
│   ├── 📄 safe_unordered_container.h
│   ├── 📄 self_construct.h
│   ├── 📄 function_annotations.h
│   ├── 📄 safe_node.h
├── 📂 ext
│   ├── 📄 algorithm.h
│   ├── 📄 array_allocator.h
│   ├── 📄 atomicity.h
│   ├── 📄 hash_map.h
│   ├── 📄 hash_set.h
│   ├── 📄 memory.h
│   ├── 📄 new_allocator.h
│   ├── 📄 pool_allocator.h
│   ├── 📄 rb_tree.h
│   ├── 📄 rope.h
│   ├── 📄 ropeimpl.h
│   ├── 📄 smart_ptr.h
│   ├── 📄 throw_allocator.h
│   ├── 📄 unique_ptr.h
│   ├── 📄 valarray.h
│   ├── 📄 sso_string.h
│   ├── 📄 stdio_sync_filebuf.h
├── 📂 experimental
│   ├── 📄 array
│   ├── 📄 memory_resource
│   ├── 📄 optional
│   ├── 📄 regex
│   ├── 📄 simd
│   ├── 📄 variant
│   ├── 📄 unordered_map
├── 📂 std
│   ├── 📄 array
│   ├── 📄 complex
│   ├── 📄 deque
│   ├── 📄 initializer_list
│   ├── 📄 ios
│   ├── 📄 iterator
│   ├── 📄 list
│   ├── 📄 map
│   ├── 📄 memory
│   ├── 📄 mutex
│   ├── 📄 numeric
│   ├── 📄 optional
│   ├── 📄 queue
│   ├── 📄 ratio
│   ├── 📄 set
│   ├── 📄 shared_mutex
│   ├── 📄 stack
│   ├── 📄 stdexcept
│   ├── 📄 string
│   ├── 📄 tuple
│   ├── 📄 type_traits
│   ├── 📄 unordered_map
│   ├── 📄 utility
│   ├── 📄 vector
├── 📂 tr1
│   ├── 📄 array
│   ├── 📄 cctype
│   ├── 📄 cmath
│   ├── 📄 cstddef
│   ├── 📄 functional
│   ├── 📄 random
│   ├── 📄 regex
│   ├── 📄 tuple
│   ├── 📄 unordered_map
│   ├── 📄 utility
├── 📂 c_compatibility
│   ├── 📄 stdlib.h
│   ├── 📄 stdalign.h
├── 📂 backward
│   ├── 📄 binders.h
│   ├── 📄 iterator.h
│   ├── 📄 pair.h
```

### Brief description of each header:

#### bits
- **algorithmfwd.h**: Forward declarations for algorithm-related functions.
- **alloc_traits.h**: Traits class for allocator properties.
- **allocator.h**: Definitions for the allocator class template.
- **allocator_traits.h**: Provides allocator traits.
- **basic_ios.h**: Core input/output stream classes.
- **basic_string.h**: Internal implementation of the `std::string` class.
- **char_traits.h**: Character traits for `std::string`.
- **codecvt.h**: Code conversion facets for locale.
- **cstring**: C-style string handling utilities.
- **deque.tcc**: Implementation details for `std::deque`.
- **exception.h**: Exception handling utilities.
- **forward_list.h**: Implementation details for `std::forward_list`.
- **hash_bytes.h**: Hashing utilities for byte sequences.
- **initializer_list.h**: Support for initializer lists.
- **ios_base.h**: Base class for all input/output stream classes.
- **iostream.h**: Input/output stream operations.
- **istream.tcc**: Implementation details for input stream classes.
- **list.tcc**: Implementation details for `std::list`.
- **map.tcc**: Implementation details for `std::map`.
- **mask_array.h**: Support for masked array operations.
- **matrix.h**: Matrix data structure and operations.
- **move.h**: Utilities for move semantics.
- **numeric.h**: Numeric operations and algorithms.
- **ostream.tcc**: Implementation details for output stream classes.
- **ptr_traits.h**: Traits class for pointer properties.
- **queue.tcc**: Implementation details for `std::queue`.
- **random.h**: Random number generation utilities.
- **set.tcc**: Implementation details for `std::set`.
- **shared_ptr.h**: Implementation of `std::shared_ptr`.
- **sstream.tcc**: Implementation details for string stream classes.
- **stl_algo.h**: Implementation of STL algorithms.
- **stl_bvector.h**: Specialization of `std::vector` for boolean elements.
- **stl_construct.h**: Construct and destroy object utilities.
- **stl_deque.h**: Implementation of `std::deque`.
- **stl_function.h**: Function object utilities.
- **stl_heap.h**: Heap operations.
- **stl_iterator.h**: Iterator utilities.
- **stl_list.h**: Implementation of `std::list`.
- **stl_map.h**: Implementation of `std::map`.
- **stl_multimap.h**: Implementation of `std::multimap`.
- **stl_multiset.h**: Implementation of `std::multiset`.
- **stl_numeric.h**: Numeric algorithms and operations.
- **stl_queue.h**: Implementation of `std::queue`.
- **stl_set.h**: Implementation of `std::set`.
- **stl_stack.h**: Implementation of `std::stack`.
- **stl_uninitialized.h**: Utilities for uninitialized memory.
- **stl_vector.h**: Implementation of `std::vector`.
- **stringfwd.h**: Forward declarations for string-related classes.
- **type_traits.h**: Compile-time type information utilities.
- **unordered_map.h**: Implementation of `std::unordered_map`.
- **utility.h**: Utility functions and classes.
- **vector.tcc**: Implementation details for `std::vector`.

### tr1
- **array**: Implementation of `std::tr1::array`.
- **cctype**: Character classification utilities.
- **cmath**: Mathematical functions and utilities.
- **cstddef**: Standard definitions and types.
- **functional**: Function objects and utilities.
- **random**: Random number generation utilities.
- **regex**: Regular expression utilities.
- **tuple**: Tuple data structure.
- **unordered_map**: Implementation of `std::tr1::unordered_map`.
- **utility**: Utility functions and classes.

### experimental
- **array**: Implementation of experimental array utilities.
- **memory_resource**: Polymorphic memory resources.
- **optional**: Implementation of `std::experimental::optional`.
- **regex**: Experimental regular expression utilities.
- **simd**: Experimental SIMD (Single Instruction, Multiple Data) utilities.
- **variant**: Implementation of `std::experimental::variant`.
- **unordered_map**: Implementation of experimental unordered map utilities.
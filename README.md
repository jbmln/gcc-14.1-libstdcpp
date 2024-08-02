# GCC 14.1.0: C++ Standard Library
- [GCC 14.1.0: C++ Standard Library](#gcc-1410-c-standard-library)
  - [Overview](#overview)
  - [Description of each header:](#description-of-each-header)
    - [bits](#bits)
    - [tr1](#tr1)
    - [experimental](#experimental)
  - [Folder structure](#folder-structure)

## Overview

A repo containing the libstdc++-v3 folder from the main GCC GitHub repo
which can be found here:
[https://github.com/gcc-mirror/gcc](https://github.com/gcc-mirror/gcc)

*Please note: the tag/release 14.1.0 was used to minimise the repo size.*

## Description of each header:

Here are the headers in the `bits`, `tr1`, and `experimental` folders with clickable links to their files in the specified GitHub repository:

### bits
- [**algorithmfwd.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/algorithmfwd.h): Forward declarations for algorithm-related functions.
- [**alloc_traits.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/alloc_traits.h): Traits class for allocator properties.
- [**allocator.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/allocator.h): Definitions for the allocator class template.
- [**allocator_traits.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/allocator_traits.h): Provides allocator traits.
- [**basic_ios.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/basic_ios.h): Core input/output stream classes.
- [**basic_string.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/basic_string.h): Internal implementation of the `std::string` class.
- [**char_traits.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/char_traits.h): Character traits for `std::string`.
- [**codecvt.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/codecvt.h): Code conversion facets for locale.
- [**cstring**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/cstring): C-style string handling utilities.
- [**deque.tcc**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/deque.tcc): Implementation details for `std::deque`.
- [**exception.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/exception.h): Exception handling utilities.
- [**forward_list.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/forward_list.h): Implementation details for `std::forward_list`.
- [**hash_bytes.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/hash_bytes.h): Hashing utilities for byte sequences.
- [**initializer_list.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/initializer_list.h): Support for initializer lists.
- [**ios_base.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/ios_base.h): Base class for all input/output stream classes.
- [**iostream.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/iostream.h): Input/output stream operations.
- [**istream.tcc**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/istream.tcc): Implementation details for input stream classes.
- [**list.tcc**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/list.tcc): Implementation details for `std::list`.
- [**map.tcc**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/map.tcc): Implementation details for `std::map`.
- [**mask_array.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/mask_array.h): Support for masked array operations.
- [**matrix.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/matrix.h): Matrix data structure and operations.
- [**move.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/move.h): Utilities for move semantics.
- [**numeric.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/numeric.h): Numeric operations and algorithms.
- [**ostream.tcc**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/ostream.tcc): Implementation details for output stream classes.
- [**ptr_traits.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/ptr_traits.h): Traits class for pointer properties.
- [**queue.tcc**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/queue.tcc): Implementation details for `std::queue`.
- [**random.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/random.h): Random number generation utilities.
- [**set.tcc**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/set.tcc): Implementation details for `std::set`.
- [**shared_ptr.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/shared_ptr.h): Implementation of `std::shared_ptr`.
- [**sstream.tcc**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/sstream.tcc): Implementation details for string stream classes.
- [**stl_algo.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_algo.h): Implementation of STL algorithms.
- [**stl_bvector.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_bvector.h): Specialization of `std::vector` for boolean elements.
- [**stl_construct.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_construct.h): Construct and destroy object utilities.
- [**stl_deque.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_deque.h): Implementation of `std::deque`.
- [**stl_function.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_function.h): Function object utilities.
- [**stl_heap.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_heap.h): Heap operations.
- [**stl_iterator.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_iterator.h): Iterator utilities.
- [**stl_list.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_list.h): Implementation of `std::list`.
- [**stl_map.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_map.h): Implementation of `std::map`.
- [**stl_multimap.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_multimap.h): Implementation of `std::multimap`.
- [**stl_multiset.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_multiset.h): Implementation of `std::multiset`.
- [**stl_numeric.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_numeric.h): Numeric algorithms and operations.
- [**stl_queue.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_queue.h): Implementation of `std::queue`.
- [**stl_set.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_set.h): Implementation of `std::set`.
- [**stl_stack.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_stack.h): Implementation of `std::stack`.
- [**stl_uninitialized.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_uninitialized.h): Utilities for uninitialized memory.
- [**stl_vector.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stl_vector.h): Implementation of `std::vector`.
- [**stringfwd.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/stringfwd.h): Forward declarations for string-related classes.
- [**type_traits.h**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/bits/cpp_type_traits.h): Provides type traits for compile-time type introspection & metaprogramming

### tr1
- [**array**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/array): Implementation of `std::tr1::array`.
- [**cctype**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/cctype): Character classification utilities.
- [**cmath**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/cmath): Mathematical functions and utilities.
- [**cstddef**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/cstddef): Standard definitions and types.
- [**functional**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/functional): Function objects and utilities.
- [**random**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/random): Random number generation utilities.
- [**regex**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/regex): Regular expression utilities.
- [**tuple**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/tuple): Tuple data structure.
- [**unordered_map**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/unordered_map): Implementation of `std::tr1::unordered_map`.
- [**utility**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/tr1/utility): Utility functions and classes.

### experimental
- [**array**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/experimental/array): Implementation of experimental array utilities.
- [**memory_resource**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/experimental/memory_resource): Polymorphic memory resources.
- [**optional**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/experimental/optional): Implementation of `std::experimental::optional`.
- [**regex**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/experimental/regex): Experimental regular expression utilities.
- [**simd**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/experimental/simd): Experimental SIMD (Single Instruction, Multiple Data) utilities.
- [**variant**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/experimental/variant): Implementation of `std::experimental::variant`.
- [**unordered_map**](https://github.com/jbmln/gcc-14.1-libstdcpp/blob/main/include/experimental/unordered_map): Implementation of experimental unordered map utilities.

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
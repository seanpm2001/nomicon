# Summary

* [Meet Safe and Unsafe](meet-safe-and-unsafe.md)
	* [What Do Safe and Unsafe Mean](safe-unsafe-meaning.md)
	* [Working with Unsafe](working-with-unsafe.md)
* [Data Layout](data.md)
	* [repr(Rust)](repr-rust.md)
	* [Exotically Sized Types](exotic-sizes.md)
	* [Other reprs](other-reprs.md)
* [Ownership](ownership.md)
	* [References](references.md)
	* [Lifetimes](lifetimes.md)
	* [Limits of lifetimes](lifetime-mismatch.md)
	* [Lifetime Elision](lifetime-elision.md)
	* [Unbounded Lifetimes](unbounded-lifetimes.md)
	* [Higher-Rank Trait Bounds](hrtb.md)
	* [Subtyping and Variance](subtyping.md)
	* [Misc](lifetime-misc.md)
* [Type Conversions](conversions.md)
	* [Coercions](coercions.md)
	* [The Dot Operator](dot-operator.md)
	* [Casts](casts.md)
	* [Transmutes](transmutes.md)
* [Uninitialized Memory](uninitialized.md)
	* [Checked](checked-uninit.md)
	* [Unchecked](unchecked-uninit.md)
* [Ownership-Oriented Resource Management](raii.md)
	* [Constructors](constructors.md)
	* [Destructors](destructors.md)
	* [Leaking](leaking.md)
* [Unwinding](unwinding.md)
* [Concurrency](concurrency.md)
* [Example: Implementing Vec](vec.md)
	* [Layout](vec-layout.md)
	* [Allocating](vec-alloc.md)
	* [Push and Pop](vec-push-pop.md)
	* [Deallocating](vec-dealloc.md)
	* [Deref](vec-deref.md)
	* [Insert and Remove](vec-insert-remove.md)
	* [IntoIter](vec-into-iter.md)
	* [Drain](vec-drain.md)
	* [Final Code](vec-final.md)
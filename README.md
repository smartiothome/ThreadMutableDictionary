# ThreadMutableDictionary
Implementation of a sub-class on NSMutableArray that offers thread-safety by using GCD to efficiently solve the readers-writers problem

Usage is simple, just put the .h and .m in your project.  Then, initialize and use ThreadSafeMutabelArray objects just like you would MutableArray objects.  The class uses GCD efficiently o make it thread-safe.  SInce this has overhead, use it only if you think the object will be used from multiple threads.



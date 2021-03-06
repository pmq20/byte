
1.1.3 / 2015-07-01
==================

 * fix: putRawString emoji

1.1.2 / 2015-05-22
==================

 * deps: upgrade debug, long, utility

1.1.1 / 2014-10-23
==================

 * fix bugs: buffer copy (@gxcsoccer)

1.1.0 / 2014-10-18
==================

 * add missing methods (@gxcsoccer)

1.0.0 / 2014-08-27
==================

 * add optimized for numbers
 * refact put
 * refactor putChar
 * optimize put, putChar
 * add 0.11.13 benchmark result
 * add test ubffer slice and copy in node 0.10.28
 * add write int and fill byte benchmark
 * add more benchmarks

0.3.1 / 2014-05-15
==================

  * Merge pull request #9 from node-modules/array-as-copy
  * exports copy bytes, support copy(start, end)

0.3.0 / 2014-05-13
==================

 * add more buffer copy test cases
 * array() must always copy. close #8
 * improve getString performance
 * return this on putNumber*
 * fix putLong convert
 * support auto change save string long to number
 * add test for putString
 * add test for put buffer string
 * improve getString, getRawString
 * improve putString
 * add putBufString benchmark
 * improve putRawString
 * improve performance
 * use ~ for deps
 * fix jshint
 * fix benchmark string
 * add test for fastSlice
 * add benchmark for string, use _fastSlice
 * remove dynamic method name

0.2.3 / 2014-05-07 
==================

  * remove annoying warn

0.2.2 / 2014-04-22
==================

 * use taobao npm
 * use instanbul and jshint
 * use n.high and n.low to check Long instance, because long module will be diff in the top project

0.2.1 / 2014-02-08 
==================

  * Support (U)Int8 8 bit int

0.2.0 / 2014-01-25 
==================

  * add test for rawString (@dead-horse)
  * add rawString methods (@dead-horse)

0.1.3 / 2014-01-23 
==================

  * update authors
  * add test for uint, uint16
  * refactor put and get number of bytes (@dead-horse)
  * install from cnpm

0.1.2 / 2013-11-14 
==================

  * add read(size)

0.1.1 / 2013-11-14 
==================

  * handle empty string

0.1.0 / 2013-11-14 
==================

  * add getString() and putString()
  * add ByteBuffer.wrap()
  * add ByteBuffer get*()

0.0.2 / 2013-11-13 
==================

  * add warnning when buffer reallocate

0.0.1 / 2013-11-13 
==================

  * add benchmark
  * add putInt(), putChar(), putDouble(), put*()
  * update readme
  * first commit

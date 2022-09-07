��Ԫ���� (Unit test)
=====
## ���Ի��� (Test environment)
  ����ֱ���� `Travis CI` �� `AppVeyor` �Ϲ��������У��������»������������ԣ�
  
  Tests were built and run directly on `Tracis CI` and `AppVeyor` and had been tested in the following environments:

  * linux, ubuntu 14.04, gcc5/6/7
  * osx, xcode5/6/7/8
  * windows, VS2015/VS2017, [x64|x86], [Release|Debug]
  
## ���Կ�� (Test frame)
  �� [test.h](https://github.com/Alinshans/MyTinySTL/blob/master/Test/test.h) �У�����������ʵ����һ���򵥵Ĳ��Կ�ܣ��������˴���������װ���Թ��̡�</br>
  In this file [test.h](https://github.com/Alinshans/MyTinySTL/blob/master/Test/test.h), I used two class to implement a simple test framework, and defined a lot of macros to package testing process.
  
## �������� (Test content)
  �� [test.h](https://github.com/Alinshans/MyTinySTL/blob/master/Test/test.h) �ж����������꣬`PERFORMANCE_TEST_ON` �� `LARGER_TEST_DATA_ON`��`PERFORMANCE_TEST_ON` ���������ܲ��ԣ�Ĭ�϶���Ϊ `1`��`LARGER_TEST_DATA_ON` ��������������ݣ�Ĭ�϶���Ϊ `0`��**�������� `LARGER_TEST_DATA_ON` ����Ϊ `1`�������������Ϊ�������� i5 �����ϣ��ڴ� 8G ���ϡ�**<br>
  In this file [test.h](https://github.com/Alinshans/MyTinySTL/blob/master/Test/test.h), I defined two marcos: `PERFORMANCE_TEST_ON` and `LARGER_TEST_DATA_ON`. `PERFORMANCE_TEST_ON` means to run performance test, the default is defined as `1`. `LARGER_TEST_DATA_ON` means to increase the test data, the default is defined as `0`. **If you want to set `LARGER_TEST_DATA_ON` to `1`, the proposed computer configuration is: CPU i5 or above, memory 8G or more.**

  ���԰������£�<br>
  The test cases are as follows:

  * [algorithm](https://github.com/Alinshans/MyTinySTL/blob/master/Test/algorithm_test.h) *(100%/100%)*
  * [algorithm_performance](https://github.com/Alinshans/MyTinySTL/blob/master/Test/algorithm_performance_test.h) *(100%/100%)*
  * [deque](https://github.com/Alinshans/MyTinySTL/blob/master/Test/deque_test.h) *(100%/100%)*
  * [list](https://github.com/Alinshans/MyTinySTL/blob/master/Test/list_test.h) *(100%/100%)*
  * [map](https://github.com/Alinshans/MyTinySTL/blob/master/Test/map_test.h) *(100%/100%)*
    * map
    * multimap
  * [queue](https://github.com/Alinshans/MyTinySTL/blob/master/Test/queue_test.h) *(100%/100%)*
    * queue
    * priority_queue
  * [set](https://github.com/Alinshans/MyTinySTL/blob/master/Test/set_test.h) *(100%/100%)*
    * set
    * multiset
  * [stack](https://github.com/Alinshans/MyTinySTL/blob/master/Test/stack_test.h) *(100%/100%)*
  * [string_test](https://github.com/Alinshans/MyTinySTL/blob/master/Test/string_test.h) *(100%/100%)*
  * [unordered_map](https://github.com/Alinshans/MyTinySTL/blob/master/Test/unordered_map_test.h) *(100%/100%)*
    * unordered_map
    * unordered_multimap
  * [unordered_set](https://github.com/Alinshans/MyTinySTL/blob/master/Test/unordered_set_test.h) *(100%/100%)*
    * unordered_set
    * unordered_multiset
  * [vector](https://github.com/Alinshans/MyTinySTL/blob/master/Test/vector_test.h) *(100%/100%)*
  
  
## ���Խ�� (Test result)
  �� [Travis CI](https://travis-ci.org/Alinshans/MyTinySTL) �� [AppVeyor](https://ci.appveyor.com/project/Alinshans/mytinystl)��

  See [Travis CI](https://travis-ci.org/Alinshans/MyTinySTL) and [AppVeyor](https://ci.appveyor.com/project/Alinshans/mytinystl).
  

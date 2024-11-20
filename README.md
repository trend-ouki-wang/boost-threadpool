# boost-threadpool
This library is built on the Thread Pool library (latest stable version 0.2.5) by Philipp Henkel.  
You can access the raw source code at: [http://threadpool.sourceforge.net/index.html](http://threadpool.sourceforge.net/index.html).  

To meet project requirements, the following issues in the library have been addressed:  

1. Resolved a compilation error with newer Boost versions.  
2. Fixed a memory leak related to the pool core and worker threads.

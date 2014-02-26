Release Notes
=============

1.0.17
------

 - Initial version.


1.0.18
------

 - Improved support for Samsung Galaxy S3.
 - Memory used during signal analysis is now recycled, resulting in less CPU
   cycles spent on garbage collection.
 - Improved automatic volume adjustment. Previously, stream volume weren't 
   adjusted fully on some devices, resulting in poor measurements.
 - Added `Thermodo.isMeasuring()` call allowing clients to query whether the
   ThermodoSDK is currently in the measuring state.

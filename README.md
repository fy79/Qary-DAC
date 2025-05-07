qoac_codec.zip is an upgraded version of Software_Qary_DAC.zip by introducing the backward interleaved symbol-interval mapping. I added the line #define REVERSE in the share.h. If this line is uncommented, the backward interleaved symbol-interval mapping will be used, otherwise the original forward interleaved symbol-interval mapping will be used. A significant performance improvement can be seen by using the backward mapping.

This job was supported by the National Science Foundation of China under grant 62350069.

# Parquet #

### Version 1.2.4 ###
* ISSUE 191: Add compatibility checker for ThriftStruct to check for backward compatibility of two thrift structs

### Version 1.2.3 ###
* ISSUE 186: add parquet-pig-bundle
* ISSUE 184: Update ParquetReader to take Configuration as a constructor argument.
* ISSUE 183: Disable the time read counter check in DeprecatedInputFormatTest.
* ISSUE 182: Fix a maven warning about a missing version number.
* ISSUE 181: FIXED_LEN_BYTE_ARRAY support
* ISSUE 180: Support writing Avro records with maps with Utf8 keys
* ISSUE 179: Added Or/Not logical filters for column predicates
* ISSUE 172: Add sink support for parquet.cascading.ParquetTBaseScheme
* ISSUE 169: Support avro records with empty maps and arrays
* ISSUE 162: Avro schema with empty arrays and maps

### Version 1.2.2 ###
* ISSUE 175: fix problem with projection pushdown in parquetloader
* ISSUE 174: improve readability by renaming variables
* ISSUE 173: make numbers in log messages easy to read in InternalParquetRecordWriter
* ISSUE 171: add unit test for parquet-scrooge
* ISSUE 165: distinguish recoverable exception in BufferedProtocolReadToWrite
* ISSUE 166: support projection when required fields in thrift class are not projected

### Version 1.2.1 ###
* ISSUE 167: fix oom error dues to bad estimation

### Version 1.2.0 ###
* ISSUE 154: improve thrift error message
* ISSUE 161: support schema evolution
* ISSUE 160: Resource leak in parquet.hadoop.ParquetFileReader.readFooter(Configurati...
* ISSUE 163: remove debugging code from hot path
* ISSUE 155: Manual pushdown for thrift read support
* ISSUE 159: Counter for mapred
* ISSUE 156: Fix site
* ISSUE 153: Fix projection required field
    
### Version 1.1.1 ###
* ISSUE 150: add thrift validation on read

### Version 1.1.0 ###
* ISSUE 149: changing default block size to 128mb  
* ISSUE 146: Fix and add unit tests for Hive nested types  
* ISSUE 145: add getStatistics method to parquetloader  
* ISSUE 144: Map key fields should allow other types than strings  
* ISSUE 143: Fix empty encoding col metadata  
* ISSUE 142: Fix total size row group  
* ISSUE 141: add parquet counters for benchmark  
* ISSUE 140: Implemented partial schema for GroupReadSupport  
* ISSUE 138: fix bug of wrong column metadata size  
* ISSUE 137: ParquetMetadataConverter bug  
* ISSUE 133: Update plugin versions for maven aether migration - fixes #125  
* ISSUE 130: Schema validation should not validate the root element's name  
* ISSUE 127: Adding dictionary encoding for non string types.. #99  
* ISSUE 125: Unable to build  
* ISSUE 124: Fix Short and Byte types in Hive SerDe.  
* ISSUE 123: Fix Snappy compressor in parquet-hadoop.  
* ISSUE 120: Fix RLE bug with partial literal groups at end of stream.  
* ISSUE 118: Refactor column reader  
* ISSUE 115: Map key fields should allow other types than strings  
* ISSUE 103: Map key fields should allow other types than strings  
* ISSUE 99: Dictionary encoding for non string types (float  double  int  long  boolean)  
* ISSUE 47: Add tests for parquet-scrooge and parquet-cascading 

### Version 1.0.1 ###
* ISSUE 126: Unit tests for parquet cascading  
* ISSUE 121: fix wrong RecordConverter for ParquetTBaseScheme  
* ISSUE 119: fix compatibility with thrift  remove unused dependency 

### Version 1.0.0 ###

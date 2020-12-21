# Important note
TerseTools is not set up yet and this documentation will be non-functional. If you need decompression, see the original repo this was forked from. Compression functionality is not currently available.

# TerseTools
TerseTools is a Java program that recreates the compression/decomperssion of TERSE files, originally implemented on IBM mainframes with the TERSE / AMATERSE program (on IBM z/OS or IBM z/VM).

## Purpose & benefit
As Java programs can virtually run on any platform / operating system with a JVM, this tool can be used to analyze TERSE files created on an IBM mainframe or create TERSE files for your own purposes without needing a mainframe yourself.

## Arguments
Usage: "TerseTools {-d|-c} [-b]"

 -d or -c chooses whether to compress or decompress the file.

 Default mode is text mode, which will attempt ebcdic -> ASCII conversion.

 The -b flag turns on binary mode, no conversion will be attempted.

## Build instructions
To compile the Java source code, a JDK is required.

Build command: "javac TerseDecompress.java"

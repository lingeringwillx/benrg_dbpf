This is a backup of the DBPF library made by benrg and found in moreawesomethanyou.com.

- **dbpf.cpp** contains the dbpf library.
- **dbpf-recompress.cpp** contains a program that recompresses Sims 2 package files (same tool used in The Compressorizer). The old executable stored here requires MSVCR71.dll.
- **qfs.cpp** is the QFS compression code from dbpf.cpp with the DBPF code stripped out. Minimal modifications were made to make it easier to call the functions and to speed up the compression. It's also available as a precompiled dll.
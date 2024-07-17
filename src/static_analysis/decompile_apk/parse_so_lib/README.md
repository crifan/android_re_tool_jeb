# 解析so库文件

继续查看，JEB反编译apk后，对于其中的so库文件的解析。

展开到：`apk`->`app包名`->`Libraries`->此处的某个so库文件：`libThreeWP.so`

![jeb_apk_libraries_so_file](../../../assets/img/jeb_apk_libraries_so_file.jpg)

然后可以分别查看解析效果：

* （ELF格式的）so库文件
  * Overview
    * ![jeb_so_elf_overview](../../../assets/img/jeb_so_elf_overview.jpg)
  * Description
    * ![jeb_so_elf_description](../../../assets/img/jeb_so_elf_description.jpg)
  * Hex Dump
    * ![jeb_so_elf_hex_dump](../../../assets/img/jeb_so_elf_hex_dump.jpg)
  * ELF Program Table (raw)
    * ![jeb_so_elf_elf_program_table_raw](../../../assets/img/jeb_so_elf_elf_program_table_raw.jpg)
  * Segements
    * ![jeb_so_elf_segements](../../../assets/img/jeb_so_elf_segements.jpg)
  * Sections
    * ![jeb_so_elf_sections](../../../assets/img/jeb_so_elf_sections.jpg)
  * Symbols
    * ![jeb_so_elf_symbols](../../../assets/img/jeb_so_elf_symbols.jpg)
* so下面还有2个子项
  * metadata
    * ![jeb_so_sub_metadata](../../../assets/img/jeb_so_sub_metadata.jpg)
  * arm64 image
    * ![jeb_so_sub_arm64_image](../../../assets/img/jeb_so_sub_arm64_image.jpg)
    * 其也有各个子页面
      * Description
        * ![jeb_so_arm64_description](../../../assets/img/jeb_so_arm64_description.jpg)
          ```bash
          arm64 image (arm64)

          Info:
          - Processor: ARM64
          - Compiler (detected): Android NDK compiler
          - Methods: 129 (internal: 106)
          ```
      * Hex Dump
        * ![jeb_so_arm64_hex_dump](../../../assets/img/jeb_so_arm64_hex_dump.jpg)
      * Disassembly
        * ![jeb_so_arm64_disassembly](../../../assets/img/jeb_so_arm64_disassembly.jpg)
      * Graph
        * ![jeb_so_arm64_graph](../../../assets/img/jeb_so_arm64_graph.jpg)
      * Callgraph
        * 注：容易导致卡死
          * TODO：有空再去试试
      * Stings
        * ![jeb_so_arm64_strings](../../../assets/img/jeb_so_arm64_strings.jpg)
      * Types
        * ![jeb_so_arm64_types](../../../assets/img/jeb_so_arm64_types.jpg)
      * Imports
        * ![jeb_so_arm64_imports](../../../assets/img/jeb_so_arm64_imports.jpg)
      * Exports
        * ![jeb_so_arm64_exports](../../../assets/img/jeb_so_arm64_exports.jpg)
      * Referenced Methods
        * ![jeb_so_arm64_referenced_methods](../../../assets/img/jeb_so_arm64_referenced_methods.jpg)
    * 其下也有子项
      * decompiler
        * ![jeb_so_arm64_sub_decompiler](../../../assets/img/jeb_so_arm64_sub_decompiler.jpg)

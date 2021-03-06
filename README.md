WiredTiger Docs
===================
see also <http://source.wiredtiger.com/2.6.0/index.html>

#### 内容

##### 1. 管理

- [数据库HOME路径](101_home_directory.md)
- [数据库配置](102_configuration.md)
- [命令行工具](103_command_line_utility.md)
    - [导出格式](104_dump_formats.md)
- [测试](105_testing.md)

##### 2. 应用

**使用API**

- [开始使用API](201_getting_started.md)
- [配置字符串](202_configuration_strings.md)
- [游标](203_cursors.md)
    - [游标操作](204_cursor_operations.md)
    - [随机游标](205_cursor_random.md)
    - [数据源](206_data_sources.md)
- [事务](207_transactions.md)
- [错误处理](208_error_handling.md)

**存储选项**

- [模式、列、列组、索引和投影](301_schema_columns_columngroups_indices_projections.md)
    - [键值对](302_key_value_pairs.md)
    - [打包与解包数据](303_packing_and_unpacking_data.md)
- [日志结构合并树(LSM树)](304_log_structured_merge_trees.md)
- [文件格式和压缩](305_file_formats_and_compression.md)
    - [哈夫曼编码](306_huffman_encoding.md)

# Struct: <code>ftrace_graph_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    long unsigned int * table;
    size_t size;
    int * count;
    const struct seq_operations * seq_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    long unsigned int * table;
    size_t size;
    int * count;
    const struct seq_operations * seq_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    long unsigned int * table;
    size_t size;
    int * count;
    const struct seq_operations * seq_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ftrace_graph_data {
    struct ftrace_hash * hash;
    struct ftrace_func_entry * entry;
    int idx;
    enum graph_filter_type type;
    struct ftrace_hash * new_hash;
    const struct seq_operations * seq_ops;
    struct trace_parser parser;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ftrace_hash * hash</code>
</li>
<li>
<b>Field added. </b>
<code>struct ftrace_func_entry * entry</code>
</li>
<li>
<b>Field added. </b>
<code>int idx</code>
</li>
<li>
<b>Field added. </b>
<code>enum graph_filter_type type</code>
</li>
<li>
<b>Field added. </b>
<code>struct ftrace_hash * new_hash</code>
</li>
<li>
<b>Field added. </b>
<code>struct trace_parser parser</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * table</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Field removed. </b>
<code>int * count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

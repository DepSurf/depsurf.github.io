# Struct: <code>event_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    bool post_trigger;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) parse;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) parse;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) parse;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) parse;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
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
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
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
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct event_command {
    struct list_head list;
    char * name;
    enum event_trigger_type trigger_type;
    int flags;
    int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func;
    int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg;
    void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg;
    void (*)(struct trace_event_file *) unreg_all;
    int (*)(char *, struct event_trigger_data *, struct trace_event_file *) set_filter;
    struct event_trigger_ops * (*)(char *, char *) get_trigger_ops;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int flags</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct trace_event_file *) unreg_all</code>
</li>
<li>
<b>Field removed. </b>
<code>bool post_trigger</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) parse</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct event_command *, struct trace_event_file *, char *, char *, char *) func</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) reg</code> ➡️ <code>int (*)(char *, struct event_trigger_data *, struct trace_event_file *) reg</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(char *, struct event_trigger_ops *, struct event_trigger_data *, struct trace_event_file *) unreg</code> ➡️ <code>void (*)(char *, struct event_trigger_data *, struct trace_event_file *) unreg</code>
</li>
</ul>
</details>
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

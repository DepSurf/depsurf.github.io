# Struct: <code>tracer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
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
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
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
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tracer {
    const char * name;
    int (*)(struct trace_array *) init;
    void (*)(struct trace_array *) reset;
    void (*)(struct trace_array *) start;
    void (*)(struct trace_array *) stop;
    int (*)(struct trace_array *) update_thresh;
    void (*)(struct trace_iterator *) open;
    void (*)(struct trace_iterator *) pipe_open;
    void (*)(struct trace_iterator *) close;
    void (*)(struct trace_iterator *) pipe_close;
    ssize_t (*)(struct trace_iterator *, struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct trace_iterator *, struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct seq_file *) print_header;
    enum print_line_t (*)(struct trace_iterator *) print_line;
    int (*)(struct trace_array *, u32, u32, int) set_flag;
    int (*)(struct trace_array *, u32, int) flag_changed;
    struct tracer * next;
    struct tracer_flags * flags;
    int enabled;
    int ref;
    bool print_max;
    bool allow_instances;
    bool use_max_tr;
    bool noboot;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool noboot</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int ref</code>
</li>
</ul>
</details>
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

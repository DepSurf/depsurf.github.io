# Function: <code>xbc_node_get_child</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609293631,
      "name": "xbc_node_get_child",
      "external": true,
      "loc": "lib/bootconfig.c:89",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init_instances",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_key_value",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_value",
        "lib/bootconfig.c:xbc_node_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609293631,
      "name": "xbc_node_get_child",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612363019,
      "name": "xbc_node_get_child",
      "external": true,
      "loc": "lib/bootconfig.c:89",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init_instances",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_key_value",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_value",
        "lib/bootconfig.c:xbc_node_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612363019,
      "name": "xbc_node_get_child",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614504432,
      "name": "xbc_node_get_child",
      "external": true,
      "loc": "lib/bootconfig.c:89",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_node_find_next_key_value",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_value",
        "lib/bootconfig.c:xbc_node_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614504432,
      "name": "xbc_node_get_child",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615452454,
      "name": "xbc_node_get_child",
      "external": true,
      "loc": "lib/bootconfig.c:89",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_array",
        "kernel/trace/trace_boot.c:trace_boot_add_synth_event",
        "kernel/trace/trace_boot.c:trace_boot_add_kprobe_event",
        "kernel/trace/trace_boot.c:trace_boot_enable_events",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/trace/trace_boot.c:xbc_node_get_subkey",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_node_get_subkey",
        "lib/bootconfig.c:xbc_node_find_next_key_value",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615452454,
      "name": "xbc_node_get_child",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617252852,
      "name": "xbc_node_get_child",
      "external": true,
      "loc": "lib/bootconfig.c:154",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_array",
        "kernel/trace/trace_boot.c:trace_boot_add_synth_event",
        "kernel/trace/trace_boot.c:trace_boot_add_kprobe_event",
        "kernel/trace/trace_boot.c:trace_boot_enable_events",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/trace/trace_boot.c:xbc_node_get_subkey",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_get_subkey",
        "lib/bootconfig.c:xbc_node_find_next_key_value",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617252852,
      "name": "xbc_node_get_child",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627974280,
      "name": "xbc_node_get_child",
      "external": true,
      "loc": "lib/bootconfig.c:154",
      "file": "lib/bootconfig.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_key_value",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_value",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_array",
        "kernel/trace/trace_boot.c:trace_boot_add_synth_event",
        "kernel/trace/trace_boot.c:trace_boot_add_kprobe_event",
        "kernel/trace/trace_boot.c:trace_boot_enable_events",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627975424,
      "name": "xbc_node_get_child",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619740662,
      "name": "xbc_node_get_child",
      "external": true,
      "loc": "lib/bootconfig.c:154",
      "file": "lib/bootconfig.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_key_value",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_value",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_array",
        "kernel/trace/trace_boot.c:trace_boot_add_synth_event",
        "kernel/trace/trace_boot.c:trace_boot_add_kprobe_event",
        "kernel/trace/trace_boot.c:trace_boot_enable_events",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619741232,
      "name": "xbc_node_get_child",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622048822,
      "name": "xbc_node_get_child",
      "external": true,
      "loc": "lib/bootconfig.c:154",
      "file": "lib/bootconfig.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_key_value",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_value",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_array",
        "kernel/trace/trace_boot.c:trace_boot_add_synth_event",
        "kernel/trace/trace_boot.c:trace_boot_add_kprobe_event",
        "kernel/trace/trace_boot.c:trace_boot_enable_events",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622049392,
      "name": "xbc_node_get_child",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct xbc_node * xbc_node_get_child(struct xbc_node * node)
```
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

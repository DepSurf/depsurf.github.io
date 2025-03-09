# Function: <code>xbc_node_get_next</code>

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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609293658,
      "name": "xbc_node_get_next",
      "external": true,
      "loc": "lib/bootconfig.c:103",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init_instances",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_add_synth_event",
        "kernel/trace/trace_boot.c:trace_boot_add_kprobe_event",
        "kernel/trace/trace_boot.c:trace_boot_enable_events",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:find_match_node",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609293658,
      "name": "xbc_node_get_next",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612363046,
      "name": "xbc_node_get_next",
      "external": true,
      "loc": "lib/bootconfig.c:103",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init_instances",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_add_synth_event",
        "kernel/trace/trace_boot.c:trace_boot_add_kprobe_event",
        "kernel/trace/trace_boot.c:trace_boot_enable_events",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:find_match_node",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612363046,
      "name": "xbc_node_get_next",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614504459,
      "name": "xbc_node_get_next",
      "external": true,
      "loc": "lib/bootconfig.c:103",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:xbc_snprint_cmdline",
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_add_synth_event",
        "kernel/trace/trace_boot.c:trace_boot_add_kprobe_event",
        "kernel/trace/trace_boot.c:trace_boot_enable_events",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "fs/proc/bootconfig.c:copy_xbc_key_value_list",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:find_match_node",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614504459,
      "name": "xbc_node_get_next",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615452481,
      "name": "xbc_node_get_next",
      "external": true,
      "loc": "lib/bootconfig.c:103",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers",
        "kernel/trace/trace_boot.c:xbc_node_get_subkey",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:find_match_node",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_get_subkey",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615452481,
      "name": "xbc_node_get_next",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617252886,
      "name": "xbc_node_get_next",
      "external": true,
      "loc": "lib/bootconfig.c:168",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers",
        "kernel/trace/trace_boot.c:xbc_node_get_subkey",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:find_match_node",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_get_subkey",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617252886,
      "name": "xbc_node_get_next",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627974904,
      "name": "xbc_node_get_next",
      "external": true,
      "loc": "lib/bootconfig.c:168",
      "file": "lib/bootconfig.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627975488,
      "name": "xbc_node_get_next",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619740712,
      "name": "xbc_node_get_next",
      "external": true,
      "loc": "lib/bootconfig.c:168",
      "file": "lib/bootconfig.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619741296,
      "name": "xbc_node_get_next",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622048872,
      "name": "xbc_node_get_next",
      "external": true,
      "loc": "lib/bootconfig.c:168",
      "file": "lib/bootconfig.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:xbc_verify_tree",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_key",
        "lib/bootconfig.c:__xbc_add_sibling",
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622049456,
      "name": "xbc_node_get_next",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct xbc_node * xbc_node_get_next(struct xbc_node * node)
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

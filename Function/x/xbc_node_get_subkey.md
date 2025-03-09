# Function: <code>xbc_node_get_subkey</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
struct xbc_node * xbc_node_get_subkey(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_subkey",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615360495,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:161",
      "file": "kernel/trace/trace_boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers"
      ]
    },
    {
      "addr": 18446744071615452507,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:161",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615360495,
      "name": "xbc_node_get_subkey",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071615452507,
      "name": "xbc_node_get_subkey",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
struct xbc_node * xbc_node_get_subkey(struct xbc_node * node)
```

```json
{
  "name": "xbc_node_get_subkey",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617147515,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:171",
      "file": "kernel/trace/trace_boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers"
      ]
    },
    {
      "addr": 18446744071617252919,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:171",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617147515,
      "name": "xbc_node_get_subkey",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071617252919,
      "name": "xbc_node_get_subkey",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xbc_node_get_subkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627835102,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:171",
      "file": "kernel/trace/trace_boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627976229,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:171",
      "file": "lib/bootconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xbc_node_get_subkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619599310,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:171",
      "file": "kernel/trace/trace_boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619742037,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:171",
      "file": "lib/bootconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xbc_node_get_subkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621902846,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:171",
      "file": "kernel/trace/trace_boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance",
        "kernel/trace/trace_boot.c:trace_boot_init_one_event",
        "kernel/trace/trace_boot.c:trace_boot_hist_add_handlers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622050197,
      "name": "xbc_node_get_subkey",
      "external": false,
      "loc": "include/linux/bootconfig.h:171",
      "file": "lib/bootconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bootconfig.c:xbc_node_find_next_leaf",
        "lib/bootconfig.c:xbc_node_find_subkey",
        "lib/bootconfig.c:xbc_node_find_subkey"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct xbc_node * xbc_node_get_subkey(struct xbc_node * node)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct xbc_node * xbc_node_get_subkey(struct xbc_node * node)
```
</details>
</li>
</ul>

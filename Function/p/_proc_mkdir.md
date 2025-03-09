# Function: <code>_proc_mkdir</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * _proc_mkdir(const char * name, umode_t mode, struct proc_dir_entry * parent, void * data, bool force_lookup)
```

```json
{
  "name": "_proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582853802,
      "name": "_proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:484",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode"
      ],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_ns_init",
        "net/netfilter/core.c:netfilter_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582853504,
      "name": "_proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * _proc_mkdir(const char * name, umode_t mode, struct proc_dir_entry * parent, void * data, bool force_lookup)
```

```json
{
  "name": "_proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882106,
      "name": "_proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:479",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode"
      ],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_ns_init",
        "net/netfilter/core.c:netfilter_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881808,
      "name": "_proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * _proc_mkdir(const char * name, umode_t mode, struct proc_dir_entry * parent, void * data, bool force_lookup)
```

```json
{
  "name": "_proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583215722,
      "name": "_proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:479",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode"
      ],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_ns_init",
        "net/netfilter/core.c:netfilter_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215424,
      "name": "_proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * _proc_mkdir(const char * name, umode_t mode, struct proc_dir_entry * parent, void * data, bool force_lookup)
```

```json
{
  "name": "_proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712986,
      "name": "_proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:482",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode"
      ],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_ns_init",
        "net/netfilter/core.c:netfilter_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712656,
      "name": "_proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct proc_dir_entry * _proc_mkdir(const char * name, umode_t mode, struct proc_dir_entry * parent, void * data, bool force_lookup)
```

```json
{
  "name": "_proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584324474,
      "name": "_proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:482",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode"
      ],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_ns_init",
        "net/netfilter/core.c:netfilter_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584324112,
      "name": "_proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct proc_dir_entry * _proc_mkdir(const char * name, umode_t mode, struct proc_dir_entry * parent, void * data, bool force_lookup)
```

```json
{
  "name": "_proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584554522,
      "name": "_proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:481",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode"
      ],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_ns_init",
        "net/netfilter/core.c:netfilter_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554160,
      "name": "_proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct proc_dir_entry * _proc_mkdir(const char * name, umode_t mode, struct proc_dir_entry * parent, void * data, bool force_lookup)
```

```json
{
  "name": "_proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584786378,
      "name": "_proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:481",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode"
      ],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_ns_init",
        "net/netfilter/core.c:netfilter_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786016,
      "name": "_proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct proc_dir_entry * _proc_mkdir(const char * name, umode_t mode, struct proc_dir_entry * parent, void * data, bool force_lookup)
```
</details>
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

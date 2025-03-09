# Function: <code>bpf_trampoline_update</code>

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
int bpf_trampoline_update(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069888,
      "name": "bpf_trampoline_update",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:186",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069888,
      "name": "bpf_trampoline_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
int bpf_trampoline_update(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581084608,
      "name": "bpf_trampoline_update",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:301",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084608,
      "name": "bpf_trampoline_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int bpf_trampoline_update(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103104,
      "name": "bpf_trampoline_update",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:331",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103104,
      "name": "bpf_trampoline_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_trampoline_update",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:333",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332736,
      "name": "bpf_trampoline_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1450
    },
    {
      "addr": 18446744071592186697,
      "name": "bpf_trampoline_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_trampoline_update",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:333",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637744,
      "name": "bpf_trampoline_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1453
    },
    {
      "addr": 18446744071593961021,
      "name": "bpf_trampoline_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline * tr, bool lock_direct_mutex)
```

```json
{
  "name": "bpf_trampoline_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_trampoline_update",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:416",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:__bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027200,
      "name": "bpf_trampoline_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1730
    },
    {
      "addr": 18446744071596021690,
      "name": "bpf_trampoline_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline * tr, bool lock_direct_mutex)
```

```json
{
  "name": "bpf_trampoline_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_trampoline_update",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:393",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:__bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219488,
      "name": "bpf_trampoline_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1515
    },
    {
      "addr": 18446744071596543592,
      "name": "bpf_trampoline_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline * tr, bool lock_direct_mutex)
```

```json
{
  "name": "bpf_trampoline_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_trampoline_update",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:393",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:__bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375296,
      "name": "bpf_trampoline_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1606
    },
    {
      "addr": 18446744071597446825,
      "name": "bpf_trampoline_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int bpf_trampoline_update(struct bpf_trampoline * tr)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool lock_direct_mutex</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

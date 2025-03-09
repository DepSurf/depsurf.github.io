# Function: <code>bpf_prog_array_delete_safe_at</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_array_delete_safe_at(struct bpf_prog_array * array, int index)
```

```json
{
  "name": "bpf_prog_array_delete_safe_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917344,
      "name": "bpf_prog_array_delete_safe_at",
      "external": true,
      "loc": "kernel/bpf/core.c:1978",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917344,
      "name": "bpf_prog_array_delete_safe_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int bpf_prog_array_delete_safe_at(struct bpf_prog_array * array, int index)
```

```json
{
  "name": "bpf_prog_array_delete_safe_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921296,
      "name": "bpf_prog_array_delete_safe_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2074",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921296,
      "name": "bpf_prog_array_delete_safe_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int bpf_prog_array_delete_safe_at(struct bpf_prog_array * array, int index)
```

```json
{
  "name": "bpf_prog_array_delete_safe_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123808,
      "name": "bpf_prog_array_delete_safe_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2087",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123808,
      "name": "bpf_prog_array_delete_safe_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int bpf_prog_array_delete_safe_at(struct bpf_prog_array * array, int index)
```

```json
{
  "name": "bpf_prog_array_delete_safe_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393200,
      "name": "bpf_prog_array_delete_safe_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2373",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393200,
      "name": "bpf_prog_array_delete_safe_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_array_delete_safe_at(struct bpf_prog_array * array, int index)
```

```json
{
  "name": "bpf_prog_array_delete_safe_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742944,
      "name": "bpf_prog_array_delete_safe_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2367",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742944,
      "name": "bpf_prog_array_delete_safe_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_array_delete_safe_at(struct bpf_prog_array * array, int index)
```

```json
{
  "name": "bpf_prog_array_delete_safe_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902256,
      "name": "bpf_prog_array_delete_safe_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2384",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902256,
      "name": "bpf_prog_array_delete_safe_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_array_delete_safe_at(struct bpf_prog_array * array, int index)
```

```json
{
  "name": "bpf_prog_array_delete_safe_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025920,
      "name": "bpf_prog_array_delete_safe_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2560",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025920,
      "name": "bpf_prog_array_delete_safe_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int bpf_prog_array_delete_safe_at(struct bpf_prog_array * array, int index)
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

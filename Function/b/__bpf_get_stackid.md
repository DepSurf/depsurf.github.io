# Function: <code>__bpf_get_stackid</code>

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
long int __bpf_get_stackid(struct bpf_map * map, struct perf_callchain_entry * trace, u64 flags)
```

```json
{
  "name": "__bpf_get_stackid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152928,
      "name": "__bpf_get_stackid",
      "external": false,
      "loc": "kernel/bpf/stackmap.c:387",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152928,
      "name": "__bpf_get_stackid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1099
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
long int __bpf_get_stackid(struct bpf_map * map, struct perf_callchain_entry * trace, u64 flags)
```

```json
{
  "name": "__bpf_get_stackid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168736,
      "name": "__bpf_get_stackid",
      "external": false,
      "loc": "kernel/bpf/stackmap.c:252",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168736,
      "name": "__bpf_get_stackid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1101
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
long int __bpf_get_stackid(struct bpf_map * map, struct perf_callchain_entry * trace, u64 flags)
```

```json
{
  "name": "__bpf_get_stackid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407792,
      "name": "__bpf_get_stackid",
      "external": false,
      "loc": "kernel/bpf/stackmap.c:259",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407792,
      "name": "__bpf_get_stackid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1101
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
long int __bpf_get_stackid(struct bpf_map * map, struct perf_callchain_entry * trace, u64 flags)
```

```json
{
  "name": "__bpf_get_stackid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731760,
      "name": "__bpf_get_stackid",
      "external": false,
      "loc": "kernel/bpf/stackmap.c:213",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731760,
      "name": "__bpf_get_stackid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1035
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
long int __bpf_get_stackid(struct bpf_map * map, struct perf_callchain_entry * trace, u64 flags)
```

```json
{
  "name": "__bpf_get_stackid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139472,
      "name": "__bpf_get_stackid",
      "external": false,
      "loc": "kernel/bpf/stackmap.c:213",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139472,
      "name": "__bpf_get_stackid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1035
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
long int __bpf_get_stackid(struct bpf_map * map, struct perf_callchain_entry * trace, u64 flags)
```

```json
{
  "name": "__bpf_get_stackid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582336688,
      "name": "__bpf_get_stackid",
      "external": false,
      "loc": "kernel/bpf/stackmap.c:210",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582336688,
      "name": "__bpf_get_stackid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1034
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
long int __bpf_get_stackid(struct bpf_map * map, struct perf_callchain_entry * trace, u64 flags)
```

```json
{
  "name": "__bpf_get_stackid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502944,
      "name": "__bpf_get_stackid",
      "external": false,
      "loc": "kernel/bpf/stackmap.c:210",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502944,
      "name": "__bpf_get_stackid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1034
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
long int __bpf_get_stackid(struct bpf_map * map, struct perf_callchain_entry * trace, u64 flags)
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

# Function: <code>bpf_trampoline_lookup</code>

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
struct bpf_trampoline * bpf_trampoline_lookup(u64 key)
```

```json
{
  "name": "bpf_trampoline_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068912,
      "name": "bpf_trampoline_lookup",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:66",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_attach_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068912,
      "name": "bpf_trampoline_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
struct bpf_trampoline * bpf_trampoline_lookup(u64 key)
```

```json
{
  "name": "bpf_trampoline_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082896,
      "name": "bpf_trampoline_lookup",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:60",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082896,
      "name": "bpf_trampoline_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_trampoline_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581102002,
      "name": "bpf_trampoline_lookup",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:61",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_get"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_trampoline_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581331634,
      "name": "bpf_trampoline_lookup",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:61",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_get"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_trampoline_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581636337,
      "name": "bpf_trampoline_lookup",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:73",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_get"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline * bpf_trampoline_lookup(u64 key)
```

```json
{
  "name": "bpf_trampoline_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025072,
      "name": "bpf_trampoline_lookup",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:135",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_get",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025072,
      "name": "bpf_trampoline_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
struct bpf_trampoline * bpf_trampoline_lookup(u64 key)
```

```json
{
  "name": "bpf_trampoline_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217040,
      "name": "bpf_trampoline_lookup",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:134",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_get",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217040,
      "name": "bpf_trampoline_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
struct bpf_trampoline * bpf_trampoline_lookup(u64 key)
```

```json
{
  "name": "bpf_trampoline_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582372304,
      "name": "bpf_trampoline_lookup",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:134",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_get",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372304,
      "name": "bpf_trampoline_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
struct bpf_trampoline * bpf_trampoline_lookup(u64 key)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct bpf_trampoline * bpf_trampoline_lookup(u64 key)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_trampoline * bpf_trampoline_lookup(u64 key)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

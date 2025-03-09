# Function: <code>bpf_trampoline_get_progs</code>

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
struct bpf_tramp_progs * bpf_trampoline_get_progs(const struct bpf_trampoline * tr, int * total)
```

```json
{
  "name": "bpf_trampoline_get_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068512,
      "name": "bpf_trampoline_get_progs",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:163",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068512,
      "name": "bpf_trampoline_get_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
struct bpf_tramp_progs * bpf_trampoline_get_progs(const struct bpf_trampoline * tr, int * total)
```

```json
{
  "name": "bpf_trampoline_get_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082656,
      "name": "bpf_trampoline_get_progs",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:145",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082656,
      "name": "bpf_trampoline_get_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
  "name": "bpf_trampoline_get_progs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581103135,
      "name": "bpf_trampoline_get_progs",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:175",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
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
  "name": "bpf_trampoline_get_progs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581332766,
      "name": "bpf_trampoline_get_progs",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:175",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
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
  "name": "bpf_trampoline_get_progs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581637775,
      "name": "bpf_trampoline_get_progs",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:175",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_trampoline_get_progs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582027252,
      "name": "bpf_trampoline_get_progs",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:257",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
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
  "name": "bpf_trampoline_get_progs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582219540,
      "name": "bpf_trampoline_get_progs",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:229",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
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
  "name": "bpf_trampoline_get_progs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582375346,
      "name": "bpf_trampoline_get_progs",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:229",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_tramp_progs * bpf_trampoline_get_progs(const struct bpf_trampoline * tr, int * total)
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
struct bpf_tramp_progs * bpf_trampoline_get_progs(const struct bpf_trampoline * tr, int * total)
```
</details>
</li>
</ul>

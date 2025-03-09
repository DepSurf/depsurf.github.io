# Function: <code>bpf_prog_ksym_set_name</code>

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
void bpf_prog_ksym_set_name(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_ksym_set_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907520,
      "name": "bpf_prog_ksym_set_name",
      "external": false,
      "loc": "kernel/bpf/core.c:539",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907520,
      "name": "bpf_prog_ksym_set_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void bpf_prog_ksym_set_name(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_ksym_set_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580903392,
      "name": "bpf_prog_ksym_set_name",
      "external": false,
      "loc": "kernel/bpf/core.c:535",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903392,
      "name": "bpf_prog_ksym_set_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
  "name": "bpf_prog_ksym_set_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580917814,
      "name": "bpf_prog_ksym_set_name",
      "external": false,
      "loc": "kernel/bpf/core.c:541",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
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
  "name": "bpf_prog_ksym_set_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581120262,
      "name": "bpf_prog_ksym_set_name",
      "external": false,
      "loc": "kernel/bpf/core.c:542",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
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
  "name": "bpf_prog_ksym_set_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581389176,
      "name": "bpf_prog_ksym_set_name",
      "external": false,
      "loc": "kernel/bpf/core.c:551",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
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
  "name": "bpf_prog_ksym_set_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581737688,
      "name": "bpf_prog_ksym_set_name",
      "external": false,
      "loc": "kernel/bpf/core.c:559",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
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
  "name": "bpf_prog_ksym_set_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581897112,
      "name": "bpf_prog_ksym_set_name",
      "external": false,
      "loc": "kernel/bpf/core.c:560",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
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
  "name": "bpf_prog_ksym_set_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582020872,
      "name": "bpf_prog_ksym_set_name",
      "external": false,
      "loc": "kernel/bpf/core.c:577",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
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
void bpf_prog_ksym_set_name(struct bpf_prog * prog)
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
void bpf_prog_ksym_set_name(struct bpf_prog * prog)
```
</details>
</li>
</ul>

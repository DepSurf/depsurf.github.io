# Function: <code>bpf_ksym_add</code>

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
void bpf_ksym_add(struct bpf_ksym * ksym)
```

```json
{
  "name": "bpf_ksym_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917552,
      "name": "bpf_ksym_add",
      "external": true,
      "loc": "kernel/bpf/core.c:610",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/trampoline.c:bpf_trampoline_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917552,
      "name": "bpf_ksym_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void bpf_ksym_add(struct bpf_ksym * ksym)
```

```json
{
  "name": "bpf_ksym_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580913504,
      "name": "bpf_ksym_add",
      "external": true,
      "loc": "kernel/bpf/core.c:606",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/trampoline.c:bpf_tramp_image_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913504,
      "name": "bpf_ksym_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void bpf_ksym_add(struct bpf_ksym * ksym)
```

```json
{
  "name": "bpf_ksym_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917056,
      "name": "bpf_ksym_add",
      "external": true,
      "loc": "kernel/bpf/core.c:612",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917056,
      "name": "bpf_ksym_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void bpf_ksym_add(struct bpf_ksym * ksym)
```

```json
{
  "name": "bpf_ksym_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119504,
      "name": "bpf_ksym_add",
      "external": true,
      "loc": "kernel/bpf/core.c:613",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119504,
      "name": "bpf_ksym_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void bpf_ksym_add(struct bpf_ksym * ksym)
```

```json
{
  "name": "bpf_ksym_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388384,
      "name": "bpf_ksym_add",
      "external": true,
      "loc": "kernel/bpf/core.c:622",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388384,
      "name": "bpf_ksym_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void bpf_ksym_add(struct bpf_ksym * ksym)
```

```json
{
  "name": "bpf_ksym_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736848,
      "name": "bpf_ksym_add",
      "external": true,
      "loc": "kernel/bpf/core.c:630",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736848,
      "name": "bpf_ksym_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void bpf_ksym_add(struct bpf_ksym * ksym)
```

```json
{
  "name": "bpf_ksym_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896272,
      "name": "bpf_ksym_add",
      "external": true,
      "loc": "kernel/bpf/core.c:631",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896272,
      "name": "bpf_ksym_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void bpf_ksym_add(struct bpf_ksym * ksym)
```

```json
{
  "name": "bpf_ksym_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582020032,
      "name": "bpf_ksym_add",
      "external": true,
      "loc": "kernel/bpf/core.c:652",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020032,
      "name": "bpf_ksym_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void bpf_ksym_add(struct bpf_ksym * ksym)
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

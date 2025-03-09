# Function: <code>bpf_prog_get_target_btf</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_get_target_btf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581092677,
      "name": "bpf_prog_get_target_btf",
      "external": true,
      "loc": "kernel/bpf/btf.c:3662",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_ctx_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_attach_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092592,
      "name": "bpf_prog_get_target_btf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_get_target_btf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581119652,
      "name": "bpf_prog_get_target_btf",
      "external": true,
      "loc": "kernel/bpf/btf.c:4559",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_ctx_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119568,
      "name": "bpf_prog_get_target_btf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_get_target_btf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581138606,
      "name": "bpf_prog_get_target_btf",
      "external": true,
      "loc": "kernel/bpf/btf.c:4630",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_ctx_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138512,
      "name": "bpf_prog_get_target_btf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_get_target_btf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581371230,
      "name": "bpf_prog_get_target_btf",
      "external": true,
      "loc": "kernel/bpf/btf.c:4678",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_ctx_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371136,
      "name": "bpf_prog_get_target_btf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_get_target_btf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581687405,
      "name": "bpf_prog_get_target_btf",
      "external": true,
      "loc": "kernel/bpf/btf.c:5197",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_ctx_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687296,
      "name": "bpf_prog_get_target_btf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_get_target_btf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582084318,
      "name": "bpf_prog_get_target_btf",
      "external": true,
      "loc": "kernel/bpf/btf.c:5785",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_ctx_access"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084192,
      "name": "bpf_prog_get_target_btf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_get_target_btf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582280654,
      "name": "bpf_prog_get_target_btf",
      "external": true,
      "loc": "kernel/bpf/btf.c:5863",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_ctx_access"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280528,
      "name": "bpf_prog_get_target_btf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_get_target_btf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582437310,
      "name": "bpf_prog_get_target_btf",
      "external": true,
      "loc": "kernel/bpf/btf.c:6033",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_ctx_access"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437184,
      "name": "bpf_prog_get_target_btf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct btf * bpf_prog_get_target_btf(const struct bpf_prog * prog)
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

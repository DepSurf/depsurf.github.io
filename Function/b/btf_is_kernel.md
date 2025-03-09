# Function: <code>btf_is_kernel</code>

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
bool btf_is_kernel(const struct btf * btf)
```

```json
{
  "name": "btf_is_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125888,
      "name": "btf_is_kernel",
      "external": true,
      "loc": "kernel/bpf/btf.c:5741",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125888,
      "name": "btf_is_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool btf_is_kernel(const struct btf * btf)
```

```json
{
  "name": "btf_is_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581141223,
      "name": "btf_is_kernel",
      "external": true,
      "loc": "kernel/bpf/btf.c:5934",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145776,
      "name": "btf_is_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool btf_is_kernel(const struct btf * btf)
```

```json
{
  "name": "btf_is_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581374051,
      "name": "btf_is_kernel",
      "external": true,
      "loc": "kernel/bpf/btf.c:5987",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592187282,
      "name": "btf_is_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581379152,
      "name": "btf_is_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool btf_is_kernel(const struct btf * btf)
```

```json
{
  "name": "btf_is_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581696239,
      "name": "btf_is_kernel",
      "external": true,
      "loc": "kernel/bpf/btf.c:6720",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593961733,
      "name": "btf_is_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581694144,
      "name": "btf_is_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool btf_is_kernel(const struct btf * btf)
```

```json
{
  "name": "btf_is_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_is_kernel",
      "external": true,
      "loc": "kernel/bpf/btf.c:7211",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596022243,
      "name": "btf_is_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582093120,
      "name": "btf_is_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool btf_is_kernel(const struct btf * btf)
```

```json
{
  "name": "btf_is_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582289859,
      "name": "btf_is_kernel",
      "external": true,
      "loc": "kernel/bpf/btf.c:7310",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_kptr"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596544153,
      "name": "btf_is_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582289248,
      "name": "btf_is_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool btf_is_kernel(const struct btf * btf)
```

```json
{
  "name": "btf_is_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582447347,
      "name": "btf_is_kernel",
      "external": true,
      "loc": "kernel/bpf/btf.c:7374",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_kptr"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597447334,
      "name": "btf_is_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582446736,
      "name": "btf_is_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool btf_is_kernel(const struct btf * btf)
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

# Function: <code>btf_try_get_module</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct module * btf_try_get_module(const struct btf * btf)
```

```json
{
  "name": "btf_try_get_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145920,
      "name": "btf_try_get_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:6079",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145920,
      "name": "btf_try_get_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct module * btf_try_get_module(const struct btf * btf)
```

```json
{
  "name": "btf_try_get_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379328,
      "name": "btf_try_get_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:6132",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379328,
      "name": "btf_try_get_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct module * btf_try_get_module(const struct btf * btf)
```

```json
{
  "name": "btf_try_get_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694352,
      "name": "btf_try_get_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:6887",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:btf_parse_kptrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694352,
      "name": "btf_try_get_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct module * btf_try_get_module(const struct btf * btf)
```

```json
{
  "name": "btf_try_get_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093280,
      "name": "btf_try_get_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:7366",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:btf_parse_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093280,
      "name": "btf_try_get_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct module * btf_try_get_module(const struct btf * btf)
```

```json
{
  "name": "btf_try_get_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582289408,
      "name": "btf_try_get_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:7468",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:btf_parse_kptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289408,
      "name": "btf_try_get_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct module * btf_try_get_module(const struct btf * btf)
```

```json
{
  "name": "btf_try_get_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446896,
      "name": "btf_try_get_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:7532",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:btf_parse_kptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446896,
      "name": "btf_try_get_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct module * btf_try_get_module(const struct btf * btf)
```
</details>
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

# Function: <code>btf_is_module</code>

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
bool btf_is_module(const struct btf * btf)
```

```json
{
  "name": "btf_is_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145808,
      "name": "btf_is_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:5939",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145808,
      "name": "btf_is_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool btf_is_module(const struct btf * btf)
```

```json
{
  "name": "btf_is_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581361845,
      "name": "btf_is_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:5992",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592187314,
      "name": "btf_is_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581379184,
      "name": "btf_is_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool btf_is_module(const struct btf * btf)
```

```json
{
  "name": "btf_is_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581678139,
      "name": "btf_is_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:6725",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_kptrs",
        "kernel/bpf/btf.c:btf_free_kfunc_set_tab",
        "kernel/bpf/btf.c:bpf_find_btf_id"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593961775,
      "name": "btf_is_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581694192,
      "name": "btf_is_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool btf_is_module(const struct btf * btf)
```

```json
{
  "name": "btf_is_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582072603,
      "name": "btf_is_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:7216",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_fields",
        "kernel/bpf/btf.c:btf_free_kfunc_set_tab",
        "kernel/bpf/btf.c:bpf_find_btf_id"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596022285,
      "name": "btf_is_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582093184,
      "name": "btf_is_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool btf_is_module(const struct btf * btf)
```

```json
{
  "name": "btf_is_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582268726,
      "name": "btf_is_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:7315",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/btf.c:btf_free_kfunc_set_tab",
        "kernel/bpf/btf.c:bpf_find_btf_id"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596544195,
      "name": "btf_is_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582289312,
      "name": "btf_is_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool btf_is_module(const struct btf * btf)
```

```json
{
  "name": "btf_is_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582424262,
      "name": "btf_is_module",
      "external": true,
      "loc": "kernel/bpf/btf.c:7379",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/btf.c:btf_free_kfunc_set_tab",
        "kernel/bpf/btf.c:bpf_find_btf_id"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597447376,
      "name": "btf_is_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582446800,
      "name": "btf_is_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool btf_is_module(const struct btf * btf)
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

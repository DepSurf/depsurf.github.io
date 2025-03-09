# Function: <code>btf_type_is_void</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580711639,
      "name": "btf_type_is_void",
      "external": false,
      "loc": "kernel/bpf/btf.c:307",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580790543,
      "name": "btf_type_is_void",
      "external": false,
      "loc": "kernel/bpf/btf.c:317",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580875836,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878432,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580926812,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929392,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581083244,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:334",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085040,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581102709,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105968,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581121869,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:426",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125152,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581353426,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:426",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356928,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581678017,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:458",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/bloom_filter.c:bloom_map_check_btf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668288,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582072480,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:463",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/bloom_filter.c:bloom_map_check_btf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062000,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582268600,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:485",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/bloom_filter.c:bloom_map_check_btf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257040,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582424136,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:486",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/bloom_filter.c:bloom_map_check_btf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414240,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492263548,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492267928,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226153420,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226157432,
      "name": "btf_type_is_void",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285493832,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285497984,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272405500,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272405500,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580895612,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898192,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580841676,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844256,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580886860,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889440,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```

```json
{
  "name": "btf_type_is_void",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945500,
      "name": "btf_type_is_void",
      "external": true,
      "loc": "kernel/bpf/btf.c:329",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948080,
      "name": "btf_type_is_void",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool btf_type_is_void(const struct btf_type * t)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

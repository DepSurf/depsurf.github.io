# Function: <code>__btf_name_valid</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580876208,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876208,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927184,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927184,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581073680,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:555",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073680,
      "name": "__btf_name_valid.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087120,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:657",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087120,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106224,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:659",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106224,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581336320,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:659",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336320,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643232,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:754",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643232,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582034752,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:755",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034752,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bool __btf_name_valid(const struct btf * btf, u32 offset)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229664,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:777",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229664,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
bool __btf_name_valid(const struct btf * btf, u32 offset)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582385616,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:778",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385616,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492264192,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492264192,
      "name": "__btf_name_valid.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226154444,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226154444,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285494352,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285494352,
      "name": "__btf_name_valid.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272403350,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272403350,
      "name": "__btf_name_valid.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895984,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895984,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842048,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842048,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887232,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887232,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```

```json
{
  "name": "__btf_name_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945872,
      "name": "__btf_name_valid",
      "external": false,
      "loc": "kernel/bpf/btf.c:540",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945872,
      "name": "__btf_name_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool dot_ok</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool __btf_name_valid(const struct btf * btf, u32 offset, bool dot_ok)
```
</details>
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

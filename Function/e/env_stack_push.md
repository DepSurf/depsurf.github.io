# Function: <code>env_stack_push</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580710928,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:762",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710928,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580789680,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:894",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789680,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580875232,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875232,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580926208,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926208,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581072080,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:1023",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072080,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086016,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:1617",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086016,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105120,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:1618",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105120,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335152,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:1618",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335152,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640336,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:1746",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640336,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031424,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:1769",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031424,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223488,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:1799",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223488,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582379440,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:1800",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379440,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492262896,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492262896,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226149420,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226149420,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285492880,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285492880,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272402084,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272402084,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580895008,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895008,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580841072,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841072,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580886256,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886256,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "env_stack_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580944896,
      "name": "env_stack_push",
      "external": false,
      "loc": "kernel/bpf/btf.c:995",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580944896,
      "name": "env_stack_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int env_stack_push(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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

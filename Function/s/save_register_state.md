# Function: <code>save_register_state</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580776208,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1869",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776208,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580827136,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827136,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950048,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2189",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950048,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948624,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2262",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948624,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952560,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2567",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952560,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157456,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2635",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157456,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg, int size)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581524383,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2971",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434000,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg, int size)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787760,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3396",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787760,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg, int size)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948848,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4259",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948848,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void save_register_state(struct bpf_verifier_env * env, struct bpf_func_state * state, int spi, struct bpf_reg_state * reg, int size)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4417",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086448,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    },
    {
      "addr": 18446744071597435274,
      "name": "save_register_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492149968,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492149968,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg)
```

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226042556,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226042556,
      "name": "save_register_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285359104,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285359104,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272310810,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272310810,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580795936,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795936,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580742112,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742112,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580787184,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787184,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "save_register_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580845568,
      "name": "save_register_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1870",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845568,
      "name": "save_register_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_env * env</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, spi, reg, size</code> ➡️ <code>env, state, spi, reg, size</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void save_register_state(struct bpf_func_state * state, int spi, struct bpf_reg_state * reg)
```
</details>
</li>
</ul>

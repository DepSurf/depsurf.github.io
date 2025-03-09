# Function: <code>__update_reg32_bounds</code>

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
void __update_reg32_bounds(struct bpf_reg_state * reg)
```

```json
{
  "name": "__update_reg32_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951776,
      "name": "__update_reg32_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1099",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__reg_combine_64_into_32",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951776,
      "name": "__update_reg32_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __update_reg32_bounds(struct bpf_reg_state * reg)
```

```json
{
  "name": "__update_reg32_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950864,
      "name": "__update_reg32_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1131",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__reg_combine_64_into_32",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950864,
      "name": "__update_reg32_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __update_reg32_bounds(struct bpf_reg_state * reg)
```

```json
{
  "name": "__update_reg32_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954928,
      "name": "__update_reg32_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1225",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:__reg_combine_64_into_32",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954928,
      "name": "__update_reg32_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __update_reg32_bounds(struct bpf_reg_state * reg)
```

```json
{
  "name": "__update_reg32_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159808,
      "name": "__update_reg32_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1239",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__reg_combine_64_into_32",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159808,
      "name": "__update_reg32_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __update_reg32_bounds(struct bpf_reg_state * reg)
```

```json
{
  "name": "__update_reg32_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437728,
      "name": "__update_reg32_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync",
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437728,
      "name": "__update_reg32_bounds",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __update_reg32_bounds(struct bpf_reg_state * reg)
```

```json
{
  "name": "__update_reg32_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790912,
      "name": "__update_reg32_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1657",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync",
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790912,
      "name": "__update_reg32_bounds",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __update_reg32_bounds(struct bpf_reg_state * reg)
```

```json
{
  "name": "__update_reg32_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956144,
      "name": "__update_reg32_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2054",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync",
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956144,
      "name": "__update_reg32_bounds",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __update_reg32_bounds(struct bpf_reg_state * reg)
```

```json
{
  "name": "__update_reg32_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582084512,
      "name": "__update_reg32_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1908",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync",
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084512,
      "name": "__update_reg32_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void __update_reg32_bounds(struct bpf_reg_state * reg)
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

# Function: <code>ubsan_epilogue</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ubsan_epilogue()
```

```json
{
  "name": "ubsan_epilogue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592339305,
      "name": "ubsan_epilogue",
      "external": false,
      "loc": "lib/ubsan.c:149",
      "file": "lib/ubsan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_builtin_unreachable",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592339305,
      "name": "ubsan_epilogue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void ubsan_epilogue()
```

```json
{
  "name": "ubsan_epilogue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594199963,
      "name": "ubsan_epilogue",
      "external": false,
      "loc": "lib/ubsan.c:149",
      "file": "lib/ubsan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_builtin_unreachable",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594199963,
      "name": "ubsan_epilogue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void ubsan_epilogue()
```

```json
{
  "name": "ubsan_epilogue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587897793,
      "name": "ubsan_epilogue",
      "external": false,
      "loc": "lib/ubsan.c:149",
      "file": "lib/ubsan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_builtin_unreachable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587896448,
      "name": "ubsan_epilogue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void ubsan_epilogue()
```

```json
{
  "name": "ubsan_epilogue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588169201,
      "name": "ubsan_epilogue",
      "external": false,
      "loc": "lib/ubsan.c:215",
      "file": "lib/ubsan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_builtin_unreachable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168144,
      "name": "ubsan_epilogue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void ubsan_epilogue()
```

```json
{
  "name": "ubsan_epilogue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588460017,
      "name": "ubsan_epilogue",
      "external": false,
      "loc": "lib/ubsan.c:215",
      "file": "lib/ubsan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_builtin_unreachable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458960,
      "name": "ubsan_epilogue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void ubsan_epilogue()
```
</details>
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

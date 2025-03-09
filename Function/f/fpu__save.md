# Function: <code>fpu__save</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082560,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:186",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082560,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579079408,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:194",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579079408,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076944,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:146",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076944,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068912,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:145",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068912,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078496,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:145",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078496,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083152,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:146",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083152,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088560,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:144",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088560,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099056,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:121",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099056,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579101040,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:121",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579101040,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114112,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:127",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114112,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114224,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:167",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114224,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579120880,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:167",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120880,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579101424,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:121",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579101424,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033840,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:121",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033840,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100976,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:121",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100976,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void fpu__save(struct fpu * fpu)
```

```json
{
  "name": "fpu__save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579105536,
      "name": "fpu__save",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:121",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105536,
      "name": "fpu__save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void fpu__save(struct fpu * fpu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void fpu__save(struct fpu * fpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void fpu__save(struct fpu * fpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void fpu__save(struct fpu * fpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void fpu__save(struct fpu * fpu)
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

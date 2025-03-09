# Function: <code>init_kernel_text</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494760,
      "name": "init_kernel_text",
      "external": false,
      "loc": "kernel/extable.c:61",
      "file": "kernel/extable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/extable.c:__kernel_text_address"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579509068,
      "name": "init_kernel_text",
      "external": false,
      "loc": "kernel/extable.c:61",
      "file": "kernel/extable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/extable.c:__kernel_text_address"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579529740,
      "name": "init_kernel_text",
      "external": false,
      "loc": "kernel/extable.c:61",
      "file": "kernel/extable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/extable.c:__kernel_text_address"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579517525,
      "name": "init_kernel_text",
      "external": false,
      "loc": "kernel/extable.c:65",
      "file": "kernel/extable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543669,
      "name": "init_kernel_text",
      "external": false,
      "loc": "kernel/extable.c:67",
      "file": "kernel/extable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:__kernel_text_address"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579571443,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:67",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570912,
      "name": "init_kernel_text",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579608627,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:67",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608096,
      "name": "init_kernel_text",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632963,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:55",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632432,
      "name": "init_kernel_text",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658563,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658032,
      "name": "init_kernel_text",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691331,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:65",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:__kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690928,
      "name": "init_kernel_text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579669603,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:65",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:__kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669200,
      "name": "init_kernel_text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579676531,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:65",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676000,
      "name": "init_kernel_text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579754579,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:65",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754048,
      "name": "init_kernel_text",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490833316,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490832504,
      "name": "init_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224863576,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224862836,
      "name": "init_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283668016,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283666976,
      "name": "init_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271503994,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271503392,
      "name": "init_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579634883,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634352,
      "name": "init_kernel_text",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579563187,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562656,
      "name": "init_kernel_text",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632147,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631616,
      "name": "init_kernel_text",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int init_kernel_text(long unsigned int addr)
```

```json
{
  "name": "init_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665987,
      "name": "init_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:62",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665456,
      "name": "init_kernel_text",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int init_kernel_text(long unsigned int addr)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int init_kernel_text(long unsigned int addr)
```
</details>
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

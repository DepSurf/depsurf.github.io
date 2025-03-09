# Function: <code>update_iter_mod</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580007291,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:532",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053784,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:555",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580110874,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:509",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580159101,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:536",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580205152,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580253488,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
```

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580321760,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:538",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321760,
      "name": "update_iter_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
```

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306896,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:568",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306896,
      "name": "update_iter_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
```

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580310432,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:619",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580310432,
      "name": "update_iter_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
```

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463968,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:683",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463968,
      "name": "update_iter_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
```

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657264,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:707",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657264,
      "name": "update_iter_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
```

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926784,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:780",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926784,
      "name": "update_iter_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
```

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581009664,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:725",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581009664,
      "name": "update_iter_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
```

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105536,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:723",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105536,
      "name": "update_iter_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491496012,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225477460,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284454496,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271938944,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580222288,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580169728,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213760,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_iter_mod",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580266464,
      "name": "update_iter_mod",
      "external": false,
      "loc": "kernel/kallsyms.c:539",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:update_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int update_iter_mod(struct kallsym_iter * iter, loff_t pos)
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

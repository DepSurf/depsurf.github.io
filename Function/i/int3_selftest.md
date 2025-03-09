# Function: <code>int3_selftest</code>

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
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604707706,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:667",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
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
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720093,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:667",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
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
void int3_selftest()
```

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609066751,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:667",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609066751,
      "name": "int3_selftest",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 104
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
void int3_selftest()
```

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612130118,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:670",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612130118,
      "name": "int3_selftest",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614270073,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:566",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615192248,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:566",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void int3_selftest()
```

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616959420,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:855",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616959420,
      "name": "int3_selftest",
      "section": ".init.text",
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
void int3_selftest()
```

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627574176,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1309",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627574176,
      "name": "int3_selftest",
      "section": ".init.text",
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
void int3_selftest()
```

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619326416,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1500",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619326416,
      "name": "int3_selftest",
      "section": ".init.text",
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
void int3_selftest()
```

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621619408,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1610",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621619408,
      "name": "int3_selftest",
      "section": ".init.text",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604646383,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:667",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
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
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604614317,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:667",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
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
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604724175,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:667",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
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
  "name": "int3_selftest",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604724205,
      "name": "int3_selftest",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:667",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
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
void int3_selftest()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void int3_selftest()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void int3_selftest()
```
</details>
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

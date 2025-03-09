# Function: <code>cpuidle_find_governor</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588084656,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588084656,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588946625,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946416,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588958849,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958640,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588847345,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588847136,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589546065,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589545856,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591039153,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591038752,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592750497,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592750064,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593185217,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593184784,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593939041,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593938608,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501329480,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501329480,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233819404,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233819404,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294874256,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294874256,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587706448,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706448,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587484736,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484736,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588040800,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588040800,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```

```json
{
  "name": "cpuidle_find_governor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588156608,
      "name": "cpuidle_find_governor",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:31",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governor.c:cpuidle_register_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156608,
      "name": "cpuidle_find_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct cpuidle_governor * cpuidle_find_governor(const char * str)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpuidle_governor * cpuidle_find_governor(const char * str)
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

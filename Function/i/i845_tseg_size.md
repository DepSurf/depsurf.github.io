# Function: <code>i845_tseg_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595028700,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:261",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
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
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595193678,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:258",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595436565,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:258",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595436565,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 83
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
size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596357013,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:258",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596357013,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 80
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
size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602675369,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:259",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602675369,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 80
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602847363,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:257",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602847363,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604644133,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604644133,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604741749,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604741749,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604755143,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604755143,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609101499,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609101499,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612166415,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612166415,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614306756,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614306756,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615233501,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615233501,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617009031,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:289",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617009031,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 90
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627639376,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:289",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627639376,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 90
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619395440,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:289",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619395440,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 90
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621691136,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:289",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621691136,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604681427,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604681427,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604648981,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604648981,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604759011,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604759011,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
resource_size_t i845_tseg_size()
```

```json
{
  "name": "i845_tseg_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604759242,
      "name": "i845_tseg_size",
      "external": false,
      "loc": "arch/x86/kernel/early-quirks.c:288",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604759242,
      "name": "i845_tseg_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
size_t i845_tseg_size()
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>size_t</code> ➡️ <code>resource_size_t</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
resource_size_t i845_tseg_size()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
resource_size_t i845_tseg_size()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
resource_size_t i845_tseg_size()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
resource_size_t i845_tseg_size()
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

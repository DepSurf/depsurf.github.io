# Function: <code>e820_type_to_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595000870,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:915",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/e820.c:e820_reserve_resources"
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
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595164629,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:915",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/e820.c:e820_reserve_resources"
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
const char * e820_type_to_string(int e820_type)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595403573,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:940",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/e820.c:e820_reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595403573,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596323004,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:975",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323004,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 116
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602640993,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:995",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602640993,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 116
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602810655,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1015",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602810655,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 144
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604605702,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1014",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604605702,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 144
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604701271,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1029",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604701271,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 135
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604713659,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1029",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604713659,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 135
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609060311,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1041",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609060311,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 167
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612123671,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1055",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612123671,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 167
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614263597,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1055",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614263597,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 167
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615184933,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1074",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615184933,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 167
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616951337,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1074",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616951337,
      "name": "e820_type_to_string",
      "section": ".init.text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627561984,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1074",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627561984,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619311312,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1074",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619311312,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 211
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621604432,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1076",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621604432,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 211
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604639949,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1029",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604639949,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 135
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604607883,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1029",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604607883,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 135
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604717741,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1029",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604717741,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 135
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
const char * e820_type_to_string(struct e820_entry * entry)
```

```json
{
  "name": "e820_type_to_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604717771,
      "name": "e820_type_to_string",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:1029",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/e820.c:e820__reserve_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604717771,
      "name": "e820_type_to_string",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 135
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
const char * e820_type_to_string(int e820_type)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct e820_entry * entry</code>
</li>
<li>
<b>Param removed. </b>
<code>int e820_type</code>
</li>
</ul>
</details>
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
const char * e820_type_to_string(struct e820_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
const char * e820_type_to_string(struct e820_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const char * e820_type_to_string(struct e820_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const char * e820_type_to_string(struct e820_entry * entry)
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

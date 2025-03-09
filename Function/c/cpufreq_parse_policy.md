# Function: <code>cpufreq_parse_policy</code>

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
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587820832,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:616",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820832,
      "name": "cpufreq_parse_policy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
unsigned int cpufreq_parse_policy(char * str_governor)
```

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588023808,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:619",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023808,
      "name": "cpufreq_parse_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588896638,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:642",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588908647,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:649",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588798559,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:646",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
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
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589491002,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:647",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590973910,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:648",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592678473,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:648",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593109261,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:655",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593862331,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:690",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char * str_governor)
```

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501286984,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:619",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501286984,
      "name": "cpufreq_parse_policy",
      "section": ".text",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char * str_governor)
```

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233777340,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:619",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233777340,
      "name": "cpufreq_parse_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
unsigned int cpufreq_parse_policy(char * str_governor)
```

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294814336,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:619",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294814336,
      "name": "cpufreq_parse_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
unsigned int cpufreq_parse_policy(char * str_governor)
```

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587648800,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:619",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587648800,
      "name": "cpufreq_parse_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
unsigned int cpufreq_parse_policy(char * str_governor)
```

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587422672,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:619",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587422672,
      "name": "cpufreq_parse_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
unsigned int cpufreq_parse_policy(char * str_governor)
```

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587979952,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:619",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587979952,
      "name": "cpufreq_parse_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
unsigned int cpufreq_parse_policy(char * str_governor)
```

```json
{
  "name": "cpufreq_parse_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588095328,
      "name": "cpufreq_parse_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:619",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095328,
      "name": "cpufreq_parse_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
unsigned int cpufreq_parse_policy(char * str_governor)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
unsigned int cpufreq_parse_policy(char * str_governor)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int cpufreq_parse_policy(char * str_governor)
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

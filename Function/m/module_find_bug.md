# Function: <code>module_find_bug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582944292,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:64",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583231636,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:64",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583346692,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:64",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588196980,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:65",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588745652,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589123440,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589123440,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589357776,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589357776,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589814848,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589814848,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590041152,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590041152,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585036356,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:67",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bug.c:find_bug"
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585188356,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:67",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bug.c:find_bug"
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585070279,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:67",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bug.c:find_bug"
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585517015,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:67",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bug.c:find_bug"
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586668939,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bug.c:find_bug"
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595748043,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:67",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bug.c:find_bug"
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596272371,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:67",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bug.c:find_bug"
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597157107,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:67",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bug.c:find_bug"
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
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503802064,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503802064,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236424676,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297639464,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279699268,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279699268,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589643408,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589643408,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589369280,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589369280,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086784,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086784,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```

```json
{
  "name": "module_find_bug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590136976,
      "name": "module_find_bug",
      "external": false,
      "loc": "lib/bug.c:66",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590136976,
      "name": "module_find_bug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct bug_entry * module_find_bug(long unsigned int bugaddr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct bug_entry * module_find_bug(long unsigned int bugaddr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct bug_entry * module_find_bug(long unsigned int bugaddr)
```
</details>
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

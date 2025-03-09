# Function: <code>rcu_gp_fqs_loop</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579969375,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1936",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580008534,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1590",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580059590,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
void rcu_gp_fqs_loop()
```

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111456,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1852",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111456,
      "name": "rcu_gp_fqs_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
void rcu_gp_fqs_loop()
```

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580093024,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1969",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093024,
      "name": "rcu_gp_fqs_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
void rcu_gp_fqs_loop()
```

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094752,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1977",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094752,
      "name": "rcu_gp_fqs_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void rcu_gp_fqs_loop()
```

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1931",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233568,
      "name": "rcu_gp_fqs_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    },
    {
      "addr": 18446744071592144351,
      "name": "rcu_gp_fqs_loop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void rcu_gp_fqs_loop()
```

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1972",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399184,
      "name": "rcu_gp_fqs_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 989
    },
    {
      "addr": 18446744071593916271,
      "name": "rcu_gp_fqs_loop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void rcu_gp_fqs_loop()
```

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623264,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1625",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623264,
      "name": "rcu_gp_fqs_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1215
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
void rcu_gp_fqs_loop()
```

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580696480,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1578",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696480,
      "name": "rcu_gp_fqs_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
void rcu_gp_fqs_loop()
```

```json
{
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580797632,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1632",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797632,
      "name": "rcu_gp_fqs_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1395
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491263372,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225276196,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284171728,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271792104,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580028326,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972484,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580019862,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
  "name": "rcu_gp_fqs_loop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580065297,
      "name": "rcu_gp_fqs_loop",
      "external": false,
      "loc": "kernel/rcu/tree.c:1619",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
void rcu_gp_fqs_loop()
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

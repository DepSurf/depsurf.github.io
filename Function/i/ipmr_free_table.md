# Function: <code>ipmr_free_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586876369,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:350",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_net_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587324865,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:332",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_net_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587527537,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:337",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_net_exit"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587673456,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:355",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587673456,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199760,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:387",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199760,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588554080,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:413",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554080,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588750160,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:416",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750160,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589182816,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589182816,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589407904,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407904,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590396307,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:413",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rules_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590454019,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:413",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rules_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590378067,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:413",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rules_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591172179,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:415",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rules_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592832443,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:408",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rules_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594710699,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:413",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rules_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595100475,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:413",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rules_exit"
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
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595913147,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:413",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rules_exit"
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503051296,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503051296,
      "name": "ipmr_free_table",
      "section": ".text",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235742240,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235742240,
      "name": "ipmr_free_table",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296760064,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296760064,
      "name": "ipmr_free_table",
      "section": ".text",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279121038,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279121038,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589012816,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012816,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588735872,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735872,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589449200,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589449200,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ipmr_free_table(struct mr_table * mrt)
```

```json
{
  "name": "ipmr_free_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589494304,
      "name": "ipmr_free_table",
      "external": false,
      "loc": "net/ipv4/ipmr.c:409",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589494304,
      "name": "ipmr_free_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void ipmr_free_table(struct mr_table * mrt)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void ipmr_free_table(struct mr_table * mrt)
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

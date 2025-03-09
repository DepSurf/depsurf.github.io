# Function: <code>__synchronize_srcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct * sp, int trycount)
```

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579778992,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcu.c:410",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcu.c:synchronize_srcu",
        "kernel/rcu/srcu.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778992,
      "name": "__synchronize_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct * sp, int trycount)
```

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804336,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcu.c:410",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcu.c:synchronize_srcu_expedited",
        "kernel/rcu/srcu.c:synchronize_srcu",
        "kernel/rcu/srcu.c:synchronize_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804336,
      "name": "__synchronize_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct * sp, int trycount)
```

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579832720,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcu.c:410",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcu.c:synchronize_srcu_expedited",
        "kernel/rcu/srcu.c:synchronize_srcu",
        "kernel/rcu/srcu.c:synchronize_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832720,
      "name": "__synchronize_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579836962,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:880",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836768,
      "name": "__synchronize_srcu.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877266,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:881",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877072,
      "name": "__synchronize_srcu.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579911266,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:911",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911088,
      "name": "__synchronize_srcu.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958962,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:929",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958768,
      "name": "__synchronize_srcu.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579995507,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:904",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995312,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580045635,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045440,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580101280,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:918",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101280,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082816,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:907",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082816,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580084208,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:921",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084208,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580220624,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:913",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220624,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void __synchronize_srcu(struct srcu_struct * ssp, bool do_norm)
```

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381216,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1198",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381216,
      "name": "__synchronize_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void __synchronize_srcu(struct srcu_struct * ssp, bool do_norm)
```

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607968,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1267",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607968,
      "name": "__synchronize_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void __synchronize_srcu(struct srcu_struct * ssp, bool do_norm)
```

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681664,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1341",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681664,
      "name": "__synchronize_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void __synchronize_srcu(struct srcu_struct * ssp, bool do_norm)
```

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748448,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1361",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748448,
      "name": "__synchronize_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491251572,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491251360,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225261320,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225261108,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284150788,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284150512,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271776288,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271776120,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580014371,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014176,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579953107,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952912,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580005907,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005712,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synchronize_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054995,
      "name": "__synchronize_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:905",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:synchronize_srcu_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054816,
      "name": "__synchronize_srcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __synchronize_srcu(struct srcu_struct * sp, int trycount)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __synchronize_srcu(struct srcu_struct * ssp, bool do_norm)
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

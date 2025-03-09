# Function: <code>srcu_gp_end</code>

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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579834938,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:498",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579875242,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:499",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579909306,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:529",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579956858,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:537",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579997133,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580047261,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
void srcu_gp_end(struct srcu_struct * ssp)
```

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101824,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:525",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_advance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101824,
      "name": "srcu_gp_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
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
void srcu_gp_end(struct srcu_struct * ssp)
```

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083360,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:514",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_advance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083360,
      "name": "srcu_gp_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
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
void srcu_gp_end(struct srcu_struct * ssp)
```

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085328,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:517",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_advance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085328,
      "name": "srcu_gp_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
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
void srcu_gp_end(struct srcu_struct * ssp)
```

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:509",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_advance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221760,
      "name": "srcu_gp_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
    },
    {
      "addr": 18446744071592141527,
      "name": "srcu_gp_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:740",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_advance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382688,
      "name": "srcu_gp_end.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
    },
    {
      "addr": 18446744071593912612,
      "name": "srcu_gp_end.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:803",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_advance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609568,
      "name": "srcu_gp_end.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
    },
    {
      "addr": 18446744071595990832,
      "name": "srcu_gp_end.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void srcu_gp_end(struct srcu_struct * ssp)
```

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:851",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_advance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683296,
      "name": "srcu_gp_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1365
    },
    {
      "addr": 18446744071596508988,
      "name": "srcu_gp_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void srcu_gp_end(struct srcu_struct * ssp)
```

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:842",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_advance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750128,
      "name": "srcu_gp_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
    },
    {
      "addr": 18446744071597406706,
      "name": "srcu_gp_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491248444,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void srcu_gp_end(struct srcu_struct * ssp)
```

```json
{
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225261584,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225261584,
      "name": "srcu_gp_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284153644,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271777438,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580015997,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579954689,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580007533,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
  "name": "srcu_gp_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580052983,
      "name": "srcu_gp_end",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:512",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu"
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
void srcu_gp_end(struct srcu_struct * ssp)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void srcu_gp_end(struct srcu_struct * ssp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void srcu_gp_end(struct srcu_struct * ssp)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void srcu_gp_end(struct srcu_struct * ssp)
```
</details>
</li>
</ul>

# Function: <code>__call_srcu</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct * sp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835872,
      "name": "__call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:813",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835872,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
void __call_srcu(struct srcu_struct * sp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876176,
      "name": "__call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:814",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876176,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
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
void __call_srcu(struct srcu_struct * sp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910208,
      "name": "__call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:844",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910208,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957760,
      "name": "__call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:859",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957760,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 961
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994320,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:834",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994320,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044448,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044448,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100864,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:848",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100864,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082416,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:838",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082416,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580084149,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:881",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:call_srcu"
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
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580220597,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:873",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:call_srcu"
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
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580381328,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1158",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/srcutree.c:call_srcu"
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
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580608080,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/srcutree.c:call_srcu"
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
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580681776,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1301",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/srcutree.c:call_srcu"
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
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580748560,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1321",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/srcutree.c:call_srcu"
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491250152,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491250152,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225260048,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225260048,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284149280,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284149280,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271775192,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271775192,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013184,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013184,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951936,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951936,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580004720,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004720,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
```

```json
{
  "name": "__call_srcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053824,
      "name": "__call_srcu",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:835",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053824,
      "name": "__call_srcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
void __call_srcu(struct srcu_struct * sp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct * ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct * sp</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void __call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func, bool do_norm)
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

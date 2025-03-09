# Function: <code>rcu_segcblist_extract_count</code>

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
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857600,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:277",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_dead_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857600,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899035,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:194",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898304,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932952,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:194",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932240,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980008,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:194",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979296,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020504,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:181",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019792,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071467,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070688,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580130141,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:292",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129424,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108365,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:292",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107616,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284632,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491283608,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225291736,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225290656,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189424,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284188432,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801608,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271800858,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040203,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039424,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985545,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984800,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031739,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030960,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082443,
      "name": "rcu_segcblist_extract_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:307",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081664,
      "name": "rcu_segcblist_extract_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void rcu_segcblist_extract_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
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

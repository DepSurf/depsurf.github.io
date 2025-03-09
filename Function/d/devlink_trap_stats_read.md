# Function: <code>devlink_trap_stats_read</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588819818,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589703690,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5920",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589733770,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:6771",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589612851,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:6974",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void devlink_trap_stats_read(struct devlink_stats * trap_stats, struct devlink_stats * stats)
```

```json
{
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590313104,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:7600",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590313104,
      "name": "devlink_trap_stats_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void devlink_trap_stats_read(struct devlink_stats * trap_stats, struct devlink_stats * stats)
```

```json
{
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591899408,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:8093",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591899408,
      "name": "devlink_trap_stats_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void devlink_trap_stats_read(struct devlink_stats * trap_stats, struct devlink_stats * stats)
```

```json
{
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593705536,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:8628",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593705536,
      "name": "devlink_trap_stats_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void devlink_trap_stats_read(struct devlink_stats * trap_stats, struct devlink_stats * stats)
```

```json
{
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595821408,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/devlink/leftover.c:5484",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_trap_group_fill",
        "net/devlink/leftover.c:devlink_nl_trap_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595821408,
      "name": "devlink_trap_stats_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void devlink_trap_stats_read(struct devlink_stats * trap_stats, struct devlink_stats * stats)
```

```json
{
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596755312,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/devlink/trap.c:156",
      "file": "net/devlink/trap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/trap.c:devlink_nl_trap_group_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596755312,
      "name": "devlink_trap_stats_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502393224,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235128480,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295934888,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278606026,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588426202,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588138890,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588758378,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
  "name": "devlink_trap_stats_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588898906,
      "name": "devlink_trap_stats_read",
      "external": false,
      "loc": "net/core/devlink.c:5328",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_stats_put"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void devlink_trap_stats_read(struct devlink_stats * trap_stats, struct devlink_stats * stats)
```
</details>
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

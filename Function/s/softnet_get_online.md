# Function: <code>softnet_get_online</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586412229,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:118",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_start",
        "net/core/net-procfs.c:softnet_seq_next"
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
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586855411,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:118",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587046531,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:118",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587174515,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:118",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587679823,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588012239,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588172975,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588500448,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500448,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588708768,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588708768,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589574864,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589574864,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589584848,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:125",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589584848,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589482656,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:122",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589482656,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590222656,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:122",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590222656,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591800048,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:124",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591800048,
      "name": "softnet_get_online",
      "section": ".text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593594624,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:124",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593594624,
      "name": "softnet_get_online",
      "section": ".text",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594067984,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:128",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594067984,
      "name": "softnet_get_online",
      "section": ".text",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594862528,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:128",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594862528,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502269864,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235010672,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235010672,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295766132,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278504526,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588315504,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315504,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588028288,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028288,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588647328,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588647328,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
struct softnet_data * softnet_get_online(loff_t * pos)
```

```json
{
  "name": "softnet_get_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588786960,
      "name": "softnet_get_online",
      "external": false,
      "loc": "net/core/net-procfs.c:119",
      "file": "net/core/net-procfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-procfs.c:softnet_seq_next",
        "net/core/net-procfs.c:softnet_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588786960,
      "name": "softnet_get_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```
</details>
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
struct softnet_data * softnet_get_online(loff_t * pos)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct softnet_data * softnet_get_online(loff_t * pos)
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

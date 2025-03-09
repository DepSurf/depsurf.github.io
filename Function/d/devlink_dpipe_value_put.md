# Function: <code>devlink_dpipe_value_put</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588577200,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1930",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577200,
      "name": "devlink_dpipe_value_put",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588795072,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795072,
      "name": "devlink_dpipe_value_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589661232,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1964",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589661232,
      "name": "devlink_dpipe_value_put",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589686528,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:2296",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589686528,
      "name": "devlink_dpipe_value_put",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589567696,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:2499",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589567696,
      "name": "devlink_dpipe_value_put",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:3061",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590315792,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071592706943,
      "name": "devlink_dpipe_value_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:3576",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591903072,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071594593682,
      "name": "devlink_dpipe_value_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:3840",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593708032,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071596330402,
      "name": "devlink_dpipe_value_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/devlink/leftover.c:3058",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_dpipe_entry_put",
        "net/devlink/leftover.c:devlink_dpipe_entry_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595820896,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071596893133,
      "name": "devlink_dpipe_value_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/devlink/dpipe.c:305",
      "file": "net/devlink/dpipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dpipe.c:devlink_dpipe_entry_put",
        "net/devlink/dpipe.c:devlink_dpipe_entry_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596713456,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071597818054,
      "name": "devlink_dpipe_value_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502365816,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502365816,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235102880,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235102880,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295896016,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295896016,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278582094,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278582094,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588401456,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588401456,
      "name": "devlink_dpipe_value_put",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588114144,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114144,
      "name": "devlink_dpipe_value_put",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588733632,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588733632,
      "name": "devlink_dpipe_value_put",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
```

```json
{
  "name": "devlink_dpipe_value_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588874064,
      "name": "devlink_dpipe_value_put",
      "external": false,
      "loc": "net/core/devlink.c:1932",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874064,
      "name": "devlink_dpipe_value_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int devlink_dpipe_value_put(struct sk_buff * skb, struct devlink_dpipe_value * value)
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

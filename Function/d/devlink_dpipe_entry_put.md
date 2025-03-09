# Function: <code>devlink_dpipe_entry_put</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588600357,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2021",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588813045,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
```

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589709104,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2055",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589709104,
      "name": "devlink_dpipe_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
```

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589738784,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2387",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589738784,
      "name": "devlink_dpipe_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
```

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589624160,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2590",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589624160,
      "name": "devlink_dpipe_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
```

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:3152",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590373440,
      "name": "devlink_dpipe_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
    },
    {
      "addr": 18446744071592708170,
      "name": "devlink_dpipe_entry_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
```

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:3667",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591959632,
      "name": "devlink_dpipe_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
    },
    {
      "addr": 18446744071594594757,
      "name": "devlink_dpipe_entry_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
```

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:3931",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593762720,
      "name": "devlink_dpipe_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
    },
    {
      "addr": 18446744071596331430,
      "name": "devlink_dpipe_entry_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
```

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/devlink/leftover.c:3149",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595859712,
      "name": "devlink_dpipe_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
    },
    {
      "addr": 18446744071596893356,
      "name": "devlink_dpipe_entry_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
```

```json
{
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/devlink/dpipe.c:396",
      "file": "net/devlink/dpipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dpipe.c:devlink_dpipe_entry_ctx_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596717216,
      "name": "devlink_dpipe_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
    },
    {
      "addr": 18446744071597818158,
      "name": "devlink_dpipe_entry_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502392196,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235121388,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295931540,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278604376,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588419429,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588132117,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588751605,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
  "name": "devlink_dpipe_entry_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588892133,
      "name": "devlink_dpipe_entry_put",
      "external": false,
      "loc": "net/core/devlink.c:2023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append"
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
int devlink_dpipe_entry_put(struct sk_buff * skb, struct devlink_dpipe_entry * entry)
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

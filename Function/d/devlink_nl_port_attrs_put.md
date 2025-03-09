# Function: <code>devlink_nl_port_attrs_put</code>

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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588596865,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:509",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588816351,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
```

```json
{
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660848,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:522",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_port_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660848,
      "name": "devlink_nl_port_attrs_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
```

```json
{
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589685904,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:660",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_port_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589685904,
      "name": "devlink_nl_port_attrs_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
```

```json
{
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589566960,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:663",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_port_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589566960,
      "name": "devlink_nl_port_attrs_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
```

```json
{
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590311696,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:760",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_port_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590311696,
      "name": "devlink_nl_port_attrs_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
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
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
```

```json
{
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591898144,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:978",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_port_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591898144,
      "name": "devlink_nl_port_attrs_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
```

```json
{
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593702944,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:1154",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_port_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593702944,
      "name": "devlink_nl_port_attrs_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
```

```json
{
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595816192,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/devlink/leftover.c:630",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_port_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595816192,
      "name": "devlink_nl_port_attrs_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
```

```json
{
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596692816,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/devlink/port.c:203",
      "file": "net/devlink/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/port.c:devlink_nl_port_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596692816,
      "name": "devlink_nl_port_attrs_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502388408,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235126072,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295924676,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278601286,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588422735,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588135423,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588754911,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
  "name": "devlink_nl_port_attrs_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588895439,
      "name": "devlink_nl_port_attrs_put",
      "external": false,
      "loc": "net/core/devlink.c:506",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_port_fill"
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
int devlink_nl_port_attrs_put(struct sk_buff * msg, struct devlink_port * devlink_port)
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

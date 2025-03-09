# Function: <code>___neigh_create</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:575",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051984,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1640
    },
    {
      "addr": 18446744071588056340,
      "name": "___neigh_create.cold.69",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:575",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588365936,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1765
    },
    {
      "addr": 18446744071588370768,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572384,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1765
    },
    {
      "addr": 18446744071588577044,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589425520,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425520,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589426272,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:574",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589426272,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589323376,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:578",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589323376,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1165
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, u8 flags, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:580",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590052752,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
    },
    {
      "addr": 18446744071592701031,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, u32 flags, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:624",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596832,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
    },
    {
      "addr": 18446744071594587496,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, u32 flags, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:662",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593377936,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1363
    },
    {
      "addr": 18446744071596326213,
      "name": "___neigh_create.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, u32 flags, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:631",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593840096,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
    },
    {
      "addr": 18446744071596856475,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, u32 flags, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:639",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594621760,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1377
    },
    {
      "addr": 18446744071597781480,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502116024,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502116024,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2244
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234861528,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234861528,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1956
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295575072,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295575072,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2384
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
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278382066,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278382066,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1614
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588179120,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1765
    },
    {
      "addr": 18446744071588183780,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891952,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1765
    },
    {
      "addr": 18446744071587896612,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588510944,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1765
    },
    {
      "addr": 18446744071588515604,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```

```json
{
  "name": "___neigh_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___neigh_create",
      "external": false,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648128,
      "name": "___neigh_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1812
    },
    {
      "addr": 18446744071588652836,
      "name": "___neigh_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct neighbour * ___neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool exempt_from_gc, bool want_ref)
```
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>tbl, pkey, dev, exempt_from_gc, want_ref</code> ➡️ <code>tbl, pkey, dev, flags, exempt_from_gc, want_ref</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 flags</code> ➡️ <code>u32 flags</code>
</li>
</ul>
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

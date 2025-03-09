# Function: <code>nexthop_notify</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:335",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589149568,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071589158783,
      "name": "nexthop_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589373680,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589373680,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590361504,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:362",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_add",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590361504,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590416496,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:490",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590416496,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590343168,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:840",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590343168,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:840",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591127968,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071592731065,
      "name": "nexthop_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:841",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592781824,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071594617495,
      "name": "nexthop_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:841",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594655424,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071596352332,
      "name": "nexthop_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:841",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595047824,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
    },
    {
      "addr": 18446744071596881148,
      "name": "nexthop_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:841",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595860864,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
    },
    {
      "addr": 18446744071597805320,
      "name": "nexthop_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503016608,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503016608,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235705212,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235705212,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296711216,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296711216,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279088726,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279088726,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588979856,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979856,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588691792,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588691792,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589416240,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589416240,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
```

```json
{
  "name": "nexthop_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459776,
      "name": "nexthop_notify",
      "external": false,
      "loc": "net/ipv4/nexthop.c:337",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459776,
      "name": "nexthop_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
void nexthop_notify(int event, struct nexthop * nh, struct nl_info * info)
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

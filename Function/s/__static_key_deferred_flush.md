# Function: <code>__static_key_deferred_flush</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011760,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011760,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067136,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067136,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248096,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248096,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289984,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289984,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307824,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307824,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188821,
      "name": "__static_key_deferred_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071581553008,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963918,
      "name": "__static_key_deferred_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581904640,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:321",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023564,
      "name": "__static_key_deferred_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582338848,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:321",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545850,
      "name": "__static_key_deferred_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582540816,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:321",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449629,
      "name": "__static_key_deferred_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582709968,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492427488,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492427488,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285695984,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285695984,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035984,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035984,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982064,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982064,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027184,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027184,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```

```json
{
  "name": "__static_key_deferred_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088544,
      "name": "__static_key_deferred_flush",
      "external": true,
      "loc": "kernel/jump_label.c:293",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_flush",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088544,
      "name": "__static_key_deferred_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __static_key_deferred_flush(void * key, struct delayed_work * work)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __static_key_deferred_flush(void * key, struct delayed_work * work)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __static_key_deferred_flush(void * key, struct delayed_work * work)
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

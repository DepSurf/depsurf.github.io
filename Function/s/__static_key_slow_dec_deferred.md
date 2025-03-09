# Function: <code>__static_key_slow_dec_deferred</code>

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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581012800,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012800,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581068816,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068816,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248400,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248400,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291216,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291216,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308880,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308880,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188931,
      "name": "__static_key_slow_dec_deferred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581553936,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964031,
      "name": "__static_key_slow_dec_deferred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581905664,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:308",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023677,
      "name": "__static_key_slow_dec_deferred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582340016,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:308",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545963,
      "name": "__static_key_slow_dec_deferred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582541984,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:308",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv4/tcp_ipv4.c:tcp_md5sig_info_free_rcu",
        "net/ipv4/tcp_minisocks.c:tcp_md5_twsk_free_rcu",
        "net/ipv4/tcp_ao.c:tcp_ao_destroy_sock",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449742,
      "name": "__static_key_slow_dec_deferred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582711136,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492429736,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492429736,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285697856,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285697856,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581037664,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037664,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580983744,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983744,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581028864,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028864,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
```

```json
{
  "name": "__static_key_slow_dec_deferred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581090288,
      "name": "__static_key_slow_dec_deferred",
      "external": true,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090288,
      "name": "__static_key_slow_dec_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
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
void __static_key_slow_dec_deferred(struct static_key * key, struct delayed_work * work, long unsigned int timeout)
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

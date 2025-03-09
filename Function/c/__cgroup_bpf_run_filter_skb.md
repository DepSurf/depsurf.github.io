# Function: <code>__cgroup_bpf_run_filter_skb</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580513744,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:170",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513744,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580545616,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:170",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545616,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623936,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:446",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623936,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752592,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752592,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817392,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:550",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817392,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580911824,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:616",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911824,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 949
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580965120,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580965120,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 949
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125424,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:963",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125424,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159344,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:987",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159344,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581177472,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:987",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177472,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1302
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1017",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592187719,
      "name": "__cgroup_bpf_run_filter_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581417104,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1142",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593962333,
      "name": "__cgroup_bpf_run_filter_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071581737168,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1356",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596022811,
      "name": "__cgroup_bpf_run_filter_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582148816,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1356",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596544864,
      "name": "__cgroup_bpf_run_filter_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582346272,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1357",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597448559,
      "name": "__cgroup_bpf_run_filter_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582512976,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492312672,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492312672,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226196568,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226196568,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1344
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285551280,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285551280,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1500
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272439846,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272439846,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933920,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933920,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 949
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879984,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580879984,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 949
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925168,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925168,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 949
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
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580985552,
      "name": "__cgroup_bpf_run_filter_skb",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:626",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985552,
      "name": "__cgroup_bpf_run_filter_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock * sk, struct sk_buff * skb, enum bpf_attach_type type)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
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

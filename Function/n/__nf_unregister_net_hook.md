# Function: <code>__nf_unregister_net_hook</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nf_hook_entry * __nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286576,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:130",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286576,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __nf_unregister_net_hook(struct nf_hook_entries * old, const struct nf_hook_ops * unreg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587808032,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:310",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808032,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588150896,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:385",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588150896,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588334192,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:385",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588334192,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588734352,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588734352,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588958160,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958160,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589912400,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589912400,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589953376,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:455",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953376,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589868208,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:455",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868208,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:456",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590629184,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071592713060,
      "name": "__nf_unregister_net_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:482",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592252976,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
    },
    {
      "addr": 18446744071594599074,
      "name": "__nf_unregister_net_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:476",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594086928,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071596334949,
      "name": "__nf_unregister_net_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:488",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594471936,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071596864619,
      "name": "__nf_unregister_net_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:488",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595274256,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071597789692,
      "name": "__nf_unregister_net_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502559928,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502559928,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235267008,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235267008,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296139952,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296139952,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278719384,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278719384,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564544,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564544,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588276528,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276528,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588896720,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588896720,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __nf_unregister_net_hook(struct net * net, int pf, const struct nf_hook_ops * reg)
```

```json
{
  "name": "__nf_unregister_net_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589039008,
      "name": "__nf_unregister_net_hook",
      "external": false,
      "loc": "net/netfilter/core.c:386",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589039008,
      "name": "__nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct nf_hook_entry * __nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nf_hook_entries * old</code>
</li>
<li>
<b>Param added. </b>
<code>const struct nf_hook_ops * unreg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct nf_hook_ops * reg</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct nf_hook_entry *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param added. </b>
<code>int pf</code>
</li>
<li>
<b>Param added. </b>
<code>const struct nf_hook_ops * reg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nf_hook_entries * old</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct nf_hook_ops * unreg</code>
</li>
</ul>
</details>
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

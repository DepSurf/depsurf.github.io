# Function: <code>nf_hook_entry_head</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587154813,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:68",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/netfilter/core.c:nf_register_net_hook"
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
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587286597,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:68",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:nf_register_net_hook"
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
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587808549,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:240",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/netfilter/core.c:nf_register_net_hook"
      ],
      "caller_func": [
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807296,
      "name": "nf_hook_entry_head.isra.4.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588149088,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:266",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588149088,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588332224,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:266",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332224,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588732544,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588732544,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588956464,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956464,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589910992,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589910992,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589951840,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589951840,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589866672,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589866672,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590627584,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590627584,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592250448,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592250448,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594084304,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594084304,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594469248,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:279",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594469248,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595271472,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:279",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595271472,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502557864,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502557864,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235265180,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235265180,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296137744,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296137744,
      "name": "nf_hook_entry_head",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278717570,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278717570,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588562848,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588562848,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588274832,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274832,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895024,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895024,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```

```json
{
  "name": "nf_hook_entry_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037328,
      "name": "nf_hook_entry_head",
      "external": false,
      "loc": "net/netfilter/core.c:267",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037328,
      "name": "nf_hook_entry_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct nf_hook_entries * * nf_hook_entry_head(struct net * net, int pf, unsigned int hooknum, struct net_device * dev)
```
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

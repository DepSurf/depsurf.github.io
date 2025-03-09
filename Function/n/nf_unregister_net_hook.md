# Function: <code>nf_unregister_net_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586517536,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:123",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks",
        "net/netfilter/core.c:nf_unregister_hook",
        "net/netfilter/core.c:netfilter_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517536,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586959952,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:123",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/core.c:nf_unregister_hook",
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959952,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587154784,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:129",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/core.c:_nf_unregister_hook",
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587154784,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286864,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:162",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286864,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808256,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:340",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808256,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588151776,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:424",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588151776,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588334928,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:424",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588334928,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588735040,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735040,
      "name": "nf_unregister_net_hook",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588958848,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958848,
      "name": "nf_unregister_net_hook",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589912871,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hooks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589912736,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589953776,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:492",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953776,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589868608,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:492",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868608,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590629680,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590629680,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592253504,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:523",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592253504,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594087456,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:517",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594087456,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594472464,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:529",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks",
        "net/netfilter/nf_bpf_link.c:bpf_nf_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594472464,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595274784,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:529",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks",
        "net/netfilter/nf_bpf_link.c:bpf_nf_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595274784,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502560776,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502560776,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235267744,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235267744,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296140976,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296140976,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278720050,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278720050,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588565232,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565232,
      "name": "nf_unregister_net_hook",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588277216,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277216,
      "name": "nf_unregister_net_hook",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588897408,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588897408,
      "name": "nf_unregister_net_hook",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hook(struct net * net, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_unregister_net_hook",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589039696,
      "name": "nf_unregister_net_hook",
      "external": true,
      "loc": "net/netfilter/core.c:425",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589039696,
      "name": "nf_unregister_net_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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

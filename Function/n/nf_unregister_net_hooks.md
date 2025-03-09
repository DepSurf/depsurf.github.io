# Function: <code>nf_unregister_net_hooks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int n)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586517872,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:181",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517872,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int n)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586960445,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:181",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586960288,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int n)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587155309,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:185",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587155152,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286944,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:200",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286944,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808464,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:395",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808464,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588152145,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:492",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588151856,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588335297,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:492",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588335008,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588735445,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735136,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588959253,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958944,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589912816,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "security/apparmor/lsm.c:apparmor_nf_unregister",
        "net/netfilter/core.c:nf_register_net_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589912816,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589955362,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:570",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "security/apparmor/lsm.c:apparmor_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589954336,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589870178,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:570",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "security/apparmor/lsm.c:apparmor_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589869168,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590631458,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:571",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "security/apparmor/lsm.c:apparmor_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590630240,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592255003,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:601",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "security/apparmor/lsm.c:apparmor_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592253648,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594089051,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:595",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "security/apparmor/lsm.c:apparmor_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594087616,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594474075,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:607",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "security/apparmor/lsm.c:apparmor_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594472624,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595276395,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:607",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/apparmor/lsm.c:apparmor_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595274944,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502561272,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502560880,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235268124,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235267824,
      "name": "nf_unregister_net_hooks",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296141088,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296141088,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278720494,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278720150,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588565637,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565328,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588277621,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277312,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588897813,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister",
        "net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_put",
        "net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_put",
        "net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588897504,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nf_unregister_net_hooks(struct net * net, const struct nf_hook_ops * reg, unsigned int hookcount)
```

```json
{
  "name": "nf_unregister_net_hooks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589040101,
      "name": "nf_unregister_net_hooks",
      "external": true,
      "loc": "net/netfilter/core.c:493",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hooks"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_nf_unregister",
        "security/smack/smack_netfilter.c:smack_nf_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589039792,
      "name": "nf_unregister_net_hooks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int hookcount</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int n</code>
</li>
</ul>
</details>
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

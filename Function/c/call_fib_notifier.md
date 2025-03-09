# Function: <code>call_fib_notifier</code>

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
  "name": "call_fib_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587490288,
      "name": "call_fib_notifier",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:102",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:register_fib_notifier",
        "net/ipv4/fib_trie.c:register_fib_notifier"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587635808,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:11",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_notify",
        "net/ipv4/fib_rules.c:fib_rules_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587635808,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669072,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:12",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669072,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996032,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:12",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996032,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588155392,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:12",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588155392,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588476912,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:12",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588476912,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588682336,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588682336,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int call_fib_notifier(struct notifier_block * nb, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589548128,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:18",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589548128,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int call_fib_notifier(struct notifier_block * nb, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557152,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:18",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589557152,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int call_fib_notifier(struct notifier_block * nb, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589455104,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:18",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589455104,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int call_fib_notifier(struct notifier_block * nb, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590192544,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:18",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192544,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int call_fib_notifier(struct notifier_block * nb, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591755680,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:18",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591755680,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int call_fib_notifier(struct notifier_block * nb, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593546480,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:18",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593546480,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int call_fib_notifier(struct notifier_block * nb, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594015552,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:18",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594015552,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int call_fib_notifier(struct notifier_block * nb, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594801920,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:18",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594801920,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502236896,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502236896,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234981896,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234981896,
      "name": "call_fib_notifier",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295727680,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295727680,
      "name": "call_fib_notifier",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278478558,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278478558,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289072,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289072,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588001888,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001888,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588620896,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588620896,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588758736,
      "name": "call_fib_notifier",
      "external": true,
      "loc": "net/core/fib_notifier.c:19",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_dump",
        "net/ipv4/fib_notifier.c:call_fib4_notifier",
        "net/ipv6/fib6_notifier.c:call_fib6_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758736,
      "name": "call_fib_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int call_fib_notifier(struct notifier_block * nb, struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>nb, net, event_type, info</code> ➡️ <code>nb, event_type, info</code>
</li>
</ul>
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

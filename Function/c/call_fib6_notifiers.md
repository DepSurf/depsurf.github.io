# Function: <code>call_fib6_notifiers</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588557104,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588557104,
      "name": "call_fib6_notifiers",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588921152,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921152,
      "name": "call_fib6_notifiers",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589144720,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589144720,
      "name": "call_fib6_notifiers",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598960,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589598960,
      "name": "call_fib6_notifiers",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589823312,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589823312,
      "name": "call_fib6_notifiers",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590848192,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590848192,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590908976,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590908976,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590838336,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590838336,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591658272,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591658272,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593353072,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593353072,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595259856,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595259856,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595655216,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595655216,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596502864,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596502864,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503531920,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503531920,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236184884,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236184884,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297328576,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297328576,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279498786,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279498786,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589427680,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427680,
      "name": "call_fib6_notifiers",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589152672,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589152672,
      "name": "call_fib6_notifiers",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589864544,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589864544,
      "name": "call_fib6_notifiers",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib6_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589916016,
      "name": "call_fib6_notifiers",
      "external": true,
      "loc": "net/ipv6/fib6_notifier.c:18",
      "file": "net/ipv6/fib6_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers",
        "net/ipv6/ip6_fib.c:call_fib6_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589916016,
      "name": "call_fib6_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int call_fib6_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```
</details>
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

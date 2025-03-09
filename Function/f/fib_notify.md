# Function: <code>fib_notify</code>

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
  "name": "fib_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587490314,
      "name": "fib_notify",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:2037",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587633408,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1955",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:register_fib_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633408,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588157952,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1951",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157952,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588513024,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1975",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588513024,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588708080,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1984",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588708080,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126752,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126752,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589350848,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350848,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int fib_notify(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590332112,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2184",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332112,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int fib_notify(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590384848,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2175",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590384848,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int fib_notify(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590300784,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2212",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590300784,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int fib_notify(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591088208,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2216",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591088208,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int fib_notify(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592738752,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2225",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592738752,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int fib_notify(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594609680,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2227",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594609680,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int fib_notify(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595001632,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2227",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595001632,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int fib_notify(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595814304,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2233",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595814304,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502991240,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502991240,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235681076,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235681076,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296678992,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296678992,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279067712,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279067712,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588957024,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957024,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668960,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668960,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589393408,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589393408,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void fib_notify(struct net * net, struct notifier_block * nb)
```

```json
{
  "name": "fib_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589436496,
      "name": "fib_notify",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2057",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_notifier.c:fib4_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436496,
      "name": "fib_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void fib_notify(struct net * net, struct notifier_block * nb)
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
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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

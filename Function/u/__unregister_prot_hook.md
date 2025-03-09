# Function: <code>__unregister_prot_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587249248,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:362",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587249248,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587711936,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:363",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587711936,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587926224,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:362",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587926224,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588084496,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:362",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588084496,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588625648,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:357",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588625648,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589005744,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:331",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589005744,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589223840,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:332",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589223840,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589681152,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681152,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589906640,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589906640,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590941424,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590941424,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591005680,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:328",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591005680,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590937088,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:328",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590937088,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591772944,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:329",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591772944,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593467568,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:365",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593467568,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595384688,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:365",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595384688,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595780768,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:363",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595780768,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596631216,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:363",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596631216,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503633296,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503633296,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236264160,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236264160,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297435712,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297435712,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279578602,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279578602,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589511008,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589511008,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589237072,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589237072,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589952272,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589952272,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void __unregister_prot_hook(struct sock * sk, bool sync)
```

```json
{
  "name": "__unregister_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589990112,
      "name": "__unregister_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:324",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990112,
      "name": "__unregister_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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

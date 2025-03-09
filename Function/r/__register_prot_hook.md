# Function: <code>__register_prot_hook</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __register_prot_hook(struct sock * sk)
```

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588998080,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:304",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588998080,
      "name": "__register_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void __register_prot_hook(struct sock * sk)
```

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589221824,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:305",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221824,
      "name": "__register_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589693985,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679040,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589915416,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589903280,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590943724,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590940528,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591008007,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:301",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591004784,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590939600,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:301",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590934928,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591775441,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:302",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591771824,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593479899,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:338",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593470480,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595391075,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:338",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595388400,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void __register_prot_hook(struct sock * sk)
```

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595784944,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:336",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595784944,
      "name": "__register_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void __register_prot_hook(struct sock * sk)
```

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596634960,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:336",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596634960,
      "name": "__register_prot_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503639192,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503624864,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236281832,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236264416,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297463872,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297436224,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279584758,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279577734,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589519784,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507648,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589245848,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589233712,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589961048,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589948912,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_prot_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590013575,
      "name": "__register_prot_hook",
      "external": false,
      "loc": "net/packet/af_packet.c:297",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589992736,
      "name": "__register_prot_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __register_prot_hook(struct sock * sk)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void __register_prot_hook(struct sock * sk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void __register_prot_hook(struct sock * sk)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

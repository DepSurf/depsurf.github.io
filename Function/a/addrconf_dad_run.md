# Function: <code>addrconf_dad_run</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587044502,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3731",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587493393,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3983",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587697166,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4026",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
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
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587847774,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4100",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
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
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588377004,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4102",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588735299,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4161",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588937856,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4181",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588937856,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589380944,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4219",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380944,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589605376,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589605376,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590613344,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4189",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590613344,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590674016,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4216",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590674016,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590599552,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4218",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590599552,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591412448,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4254",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412448,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593088096,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4267",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593088096,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594984544,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4276",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594984544,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595375776,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4282",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595375776,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596216912,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4333",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596216912,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503281080,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503281080,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235953164,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235953164,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297033504,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297033504,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279303394,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279303394,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589209744,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589209744,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588934736,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934736,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646608,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646608,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```

```json
{
  "name": "addrconf_dad_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589695616,
      "name": "addrconf_dad_run",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4225",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589695616,
      "name": "addrconf_dad_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void addrconf_dad_run(struct inet6_dev * idev, bool restart)
```
</details>
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

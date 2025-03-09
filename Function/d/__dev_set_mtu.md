# Function: <code>__dev_set_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586269456,
      "name": "__dev_set_mtu",
      "external": false,
      "loc": "net/core/dev.c:6010",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu"
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
  "name": "__dev_set_mtu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586695328,
      "name": "__dev_set_mtu",
      "external": false,
      "loc": "net/core/dev.c:6461",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu"
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
  "name": "__dev_set_mtu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586884983,
      "name": "__dev_set_mtu",
      "external": false,
      "loc": "net/core/dev.c:6605",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587009498,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:6770",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587001888,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587508355,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:6934",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500544,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587812527,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7070",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805456,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587991609,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7648",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941008,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588303337,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7658",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588250128,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588509865,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455328,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589381112,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:8360",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589323360,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589386952,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:8605",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322352,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589283745,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:8864",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218096,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590011089,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:8854",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589941776,
      "name": "__dev_set_mtu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591549867,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:8619",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591475328,
      "name": "__dev_set_mtu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593324247,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:8606",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593244800,
      "name": "__dev_set_mtu",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593786123,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:8612",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593705488,
      "name": "__dev_set_mtu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594566757,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:8730",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594483808,
      "name": "__dev_set_mtu",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502043376,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501980424,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234795148,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234734444,
      "name": "__dev_set_mtu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295491052,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295408496,
      "name": "__dev_set_mtu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278330024,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278278700,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588116601,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588062112,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587829433,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587775200,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588448425,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393888,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
```

```json
{
  "name": "__dev_set_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588585337,
      "name": "__dev_set_mtu",
      "external": true,
      "loc": "net/core/dev.c:7947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529568,
      "name": "__dev_set_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int __dev_set_mtu(struct net_device * dev, int new_mtu)
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

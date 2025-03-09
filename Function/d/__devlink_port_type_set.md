# Function: <code>__devlink_port_type_set</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:5674",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588598544,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071588619135,
      "name": "__devlink_port_type_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588818032,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588818032,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589702928,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:7307",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589702928,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589750352,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:8187",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589750352,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589620640,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:8406",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589620640,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590386080,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:9149",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590386080,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591956416,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:9756",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591956416,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:10393",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_netdevice_event",
        "net/core/devlink.c:devlink_netdevice_event",
        "net/core/devlink.c:devlink_netdevice_event",
        "net/core/devlink.c:devlink_netdevice_event",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593779296,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
    },
    {
      "addr": 18446744071596331695,
      "name": "__devlink_port_type_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/devlink/leftover.c:6962",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_port_netdevice_event",
        "net/devlink/leftover.c:devlink_port_netdevice_event",
        "net/devlink/leftover.c:devlink_port_netdevice_event",
        "net/devlink/leftover.c:devlink_port_netdevice_event",
        "net/devlink/leftover.c:devlink_port_type_clear",
        "net/devlink/leftover.c:devlink_port_type_ib_set",
        "net/devlink/leftover.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595875392,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 767
    },
    {
      "addr": 18446744071596893617,
      "name": "__devlink_port_type_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/devlink/port.c:1143",
      "file": "net/devlink/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/port.c:devlink_port_netdevice_event",
        "net/devlink/port.c:devlink_port_netdevice_event",
        "net/devlink/port.c:devlink_port_netdevice_event",
        "net/devlink/port.c:devlink_port_netdevice_event",
        "net/devlink/port.c:devlink_port_type_clear",
        "net/devlink/port.c:devlink_port_type_ib_set",
        "net/devlink/port.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596700864,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 783
    },
    {
      "addr": 18446744071597818012,
      "name": "__devlink_port_type_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502390160,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502390160,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235127764,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235127764,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295927088,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295927088,
      "name": "__devlink_port_type_set",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278602668,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278602668,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588424416,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588424416,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588137104,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588137104,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588756592,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588756592,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```

```json
{
  "name": "__devlink_port_type_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588897120,
      "name": "__devlink_port_type_set",
      "external": false,
      "loc": "net/core/devlink.c:6371",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_type_ib_set",
        "net/core/devlink.c:devlink_port_type_eth_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588897120,
      "name": "__devlink_port_type_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __devlink_port_type_set(struct devlink_port * devlink_port, enum devlink_port_type type, void * type_dev)
```
</details>
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

# Function: <code>__devlink_port_phys_port_name_get</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588617721,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:5869",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588841525,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589664544,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:7502",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589664544,
      "name": "__devlink_port_phys_port_name_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589689392,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:8375",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689392,
      "name": "__devlink_port_phys_port_name_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589569840,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:8622",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589569840,
      "name": "__devlink_port_phys_port_name_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590314976,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:9469",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590314976,
      "name": "__devlink_port_phys_port_name_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591901632,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:10127",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591901632,
      "name": "__devlink_port_phys_port_name_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593706928,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:10815",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593706928,
      "name": "__devlink_port_phys_port_name_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595819360,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/devlink/leftover.c:7383",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_compat_phys_port_name_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595819360,
      "name": "__devlink_port_phys_port_name_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596695488,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/devlink/port.c:1462",
      "file": "net/devlink/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/port.c:devlink_compat_phys_port_name_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596695488,
      "name": "__devlink_port_phys_port_name_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502413244,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235149756,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295964832,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278620490,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588447909,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588160597,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588780085,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_phys_port_name_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588920613,
      "name": "__devlink_port_phys_port_name_get",
      "external": false,
      "loc": "net/core/devlink.c:6566",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_phys_port_name_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port * devlink_port, char * name, size_t len)
```
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

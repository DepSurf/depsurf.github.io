# Function: <code>uuid_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583907456,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:142",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584725904,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1024",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584748640,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:86",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584751744,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:106",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583907456,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071584725904,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071584748640,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584751744,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584238496,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:132",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585078256,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1034",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585101952,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:86",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585107024,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:152",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584238496,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071585078256,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585101952,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585107024,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584419936,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:132",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585269168,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1151",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585290992,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:86",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585296080,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:152",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584419936,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071585269168,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071585290992,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585296080,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584503856,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:161",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585350960,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1170",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585377072,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:86",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585381248,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:152",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503856,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071585350960,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071585377072,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585381248,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584913872,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:161",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585779376,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1170",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585806128,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:86",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585810512,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:156",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913872,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071585779376,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071585806128,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585810512,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585145456,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:161",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586026096,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1169",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586052256,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:86",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586058224,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:156",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585145456,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071586026096,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071586052256,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586058224,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585256288,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:161",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586165248,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1192",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586192464,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:86",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586199104,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:156",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585256288,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071586165248,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071586192464,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586199104,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585465728,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586401376,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586429717,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586435312,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:148",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585465728,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071586401376,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071586429648,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071586431253,
      "name": "uuid_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071586435312,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585606432,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586548208,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586576352,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586582304,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606432,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071586548208,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071586576352,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586582304,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586329280,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587333216,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1164",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587361360,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:67",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587367632,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:140",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586329280,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071587333216,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071587361360,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071587367632,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586447104,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587394960,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1164",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587422608,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:67",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587428800,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:140",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588700656,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/md/md.c:4242",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447104,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071587394960,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071587422608,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071587428800,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071588700656,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586330960,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587276640,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1164",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587304544,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:67",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587310672,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:140",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588586352,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/md/md.c:4206",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330960,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071587276640,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071587304544,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587310672,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071588586352,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586850832,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587844128,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1164",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587871728,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:67",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587877568,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:140",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589262320,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/md/md.c:4225",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850832,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071587844128,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071587871728,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587877568,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071589262320,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588137632,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:157",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589192384,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:943",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589221360,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:66",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589227472,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:139",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590733056,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/md/md.c:4215",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588137632,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071589192384,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071589221360,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071589227472,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071590733056,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589527008,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:157",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590747056,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:935",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590777456,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:66",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590784288,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:141",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592409472,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/md/md.c:4177",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589527008,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071590747056,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071590777456,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071590784288,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071592409472,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589828080,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:160",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591088432,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:935",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591118880,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:66",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591125760,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:141",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592838992,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/md/md.c:4163",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589828080,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071591088432,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071591118880,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071591125760,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071592838992,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590165088,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:160",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591433328,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:942",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591464304,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:66",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591471344,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:141",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593588160,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/md/md.c:4289",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165088,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071591433328,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071591464304,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071591471344,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071593588160,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498271712,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499437784,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499466296,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498271712,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446603336499437784,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446603336499466296,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292689728,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292732624,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292737376,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292689728,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 13835058055292732624,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 13835058055292737376,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276663500,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276687254,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276663500,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446743936276687254,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585368080,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586238688,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586266832,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586272784,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvme/host/core.c:3061",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585368080,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071586238688,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071586266832,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586272784,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586465264,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586482928,
      "name": "uuid_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t uuid_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586057056,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586085200,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586091152,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvme/host/core.c:3061",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586057056,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071586085200,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586091152,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586341504,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586359056,
      "name": "uuid_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585556832,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586496176,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586524320,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586530272,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585556832,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071586496176,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071586524320,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586530272,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```

```json
{
  "name": "uuid_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585664784,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:158",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586607920,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1184",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586636048,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:78",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586642000,
      "name": "uuid_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664784,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071586607920,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071586636048,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586642000,
      "name": "uuid_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t uuid_show(struct hyp_sysfs_attr * attr, char * buffer)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param added. </b>
<code>char * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buffer</code>
</li>
<li>
<b>Param reordered. </b>
<code>attr, buffer</code> ➡️ <code>dev, attr, buf</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct hyp_sysfs_attr * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param added. </b>
<code>char * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buffer</code>
</li>
<li>
<b>Param reordered. </b>
<code>attr, buffer</code> ➡️ <code>dev, attr, buf</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct hyp_sysfs_attr * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param added. </b>
<code>char * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buffer</code>
</li>
<li>
<b>Param reordered. </b>
<code>attr, buffer</code> ➡️ <code>dev, attr, buf</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct hyp_sysfs_attr * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

# Function: <code>force_store</code>

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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579935056,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:557",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935056,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579982112,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:557",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982112,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580022208,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:373",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022208,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073232,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:373",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073232,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132352,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:395",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132352,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579710016,
      "name": "force_store",
      "external": false,
      "loc": "kernel/reboot.c:674",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580110576,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:395",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710016,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071580110576,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579717424,
      "name": "force_store",
      "external": false,
      "loc": "kernel/reboot.c:674",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580114288,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:394",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717424,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071580114288,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "force_store",
      "external": false,
      "loc": "kernel/reboot.c:753",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580256601,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:394",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795744,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071592105753,
      "name": "force_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580256496,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071592147460,
      "name": "force_store.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "force_store",
      "external": false,
      "loc": "kernel/reboot.c:1125",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580425769,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:394",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903312,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071593873340,
      "name": "force_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580425648,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071593920159,
      "name": "force_store.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "force_store",
      "external": false,
      "loc": "kernel/reboot.c:1142",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580665785,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:402",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055696,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071595976767,
      "name": "force_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580665664,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071595992209,
      "name": "force_store.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "force_store",
      "external": false,
      "loc": "kernel/reboot.c:1142",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580741961,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:417",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110128,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071596494510,
      "name": "force_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580741840,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071596510399,
      "name": "force_store.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "force_store",
      "external": false,
      "loc": "kernel/reboot.c:1165",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580826921,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:417",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155168,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071597391253,
      "name": "force_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580826800,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071597409272,
      "name": "force_store.cold",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284192704,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:373",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284192704,
      "name": "force_store",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580041968,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:373",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041968,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579987280,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:373",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987280,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580033504,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:373",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033504,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "force_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580084208,
      "name": "force_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:373",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084208,
      "name": "force_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t force_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```
</details>
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

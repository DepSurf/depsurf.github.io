# Function: <code>state_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686096,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:354",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585765104,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2572",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586114432,
      "name": "state_store",
      "external": false,
      "loc": "drivers/extcon/extcon.c:190",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587306528,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:707",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686096,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071585765104,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
    },
    {
      "addr": 18446744071586114432,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071587306528,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579705200,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:355",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586162032,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2576",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586528384,
      "name": "state_store",
      "external": false,
      "loc": "drivers/extcon/extcon.c:178",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587777648,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:703",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705200,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071586162032,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
    },
    {
      "addr": 18446744071586528384,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071587777648,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732752,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:427",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586364944,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2604",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587992800,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:703",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732752,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071586364944,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1299
    },
    {
      "addr": 18446744071587992800,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579728656,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:427",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586465312,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2666",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588150416,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:761",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728656,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071586465312,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1538
    },
    {
      "addr": 18446744071588150416,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761504,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:482",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586932688,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2721",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588698528,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:761",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761504,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071586932688,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1555
    },
    {
      "addr": 18446744071588698528,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795968,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:512",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587217904,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2736",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589065248,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:775",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795968,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071587217904,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1575
    },
    {
      "addr": 18446744071589065248,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579842576,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:501",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585913616,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:318",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587398368,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2727",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589292000,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:777",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842576,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071585913616,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071587398368,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1578
    },
    {
      "addr": 18446744071589292000,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579876544,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:513",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586155040,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:330",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587669904,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2790",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589746544,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876544,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586155040,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071587669904,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071589746544,
      "name": "state_store",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579926832,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586303632,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:299",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587874096,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:89",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589970640,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926832,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586303632,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071587874096,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071588243984,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071588244314,
      "name": "state_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071589970640,
      "name": "state_store",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970736,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:638",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587073776,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:254",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588726496,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2970",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:90",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591003440,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970736,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071587073776,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071588726496,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1790
    },
    {
      "addr": 18446744071589120832,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071589121162,
      "name": "state_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071591003440,
      "name": "state_store",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579958656,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:638",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587158544,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:253",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588754784,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2991",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:191",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591068240,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:787",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958656,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071587158544,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071588754784,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1790
    },
    {
      "addr": 18446744071589119008,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071591620053,
      "name": "state_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071591068240,
      "name": "state_store",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961152,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:638",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587046224,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:319",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588640336,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2955",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:189",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590999008,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:788",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961152,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587046224,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071588640336,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1592
    },
    {
      "addr": 18446744071589008656,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071591563435,
      "name": "state_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071590999008,
      "name": "state_store",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090672,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:641",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587615888,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:326",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589318000,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2965",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:189",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591835280,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:788",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090672,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587615888,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071589318000,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1588
    },
    {
      "addr": 18446744071589723152,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071592684166,
      "name": "state_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071591835280,
      "name": "state_store",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227872,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:615",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588956112,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:331",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590790400,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2955",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:189",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593549952,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:788",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227872,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071588956112,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071590790400,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1464
    },
    {
      "addr": 18446744071591231424,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071594569550,
      "name": "state_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071593549952,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580419728,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:619",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590471744,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:343",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592473872,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2913",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592980864,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:189",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595471728,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:788",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580419728,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071590471744,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071592473872,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
    },
    {
      "addr": 18446744071592980864,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071595471728,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580488800,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:687",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590794672,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:338",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592887696,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2887",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593431872,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:189",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595978832,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:788",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488800,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071590794672,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071592887696,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
    },
    {
      "addr": 18446744071593431872,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071595978832,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548640,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:671",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591138352,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:378",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593636656,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:3009",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594177920,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:189",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596841232,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:809",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548640,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071591138352,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071593636656,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1423
    },
    {
      "addr": 18446744071594177920,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071596841232,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491135960,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499136976,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:299",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501104080,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501701592,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:89",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503708888,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491135960,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446603336499136976,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446603336501104080,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
    },
    {
      "addr": 18446603336501701592,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446603336503708888,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225132836,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233620420,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234226008,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:89",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236341428,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225132836,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 3233620420,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1700
    },
    {
      "addr": 3234226008,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 3236341428,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284027792,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292328896,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:299",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294603152,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295139088,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:89",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297542336,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284027792,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 13835058055292328896,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 13835058055294603152,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2152
    },
    {
      "addr": 13835058055295139088,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 13835058055297542336,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271701912,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277826920,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279636672,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271701912,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446743936277826920,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1320
    },
    {
      "addr": 18446743936279636672,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898656,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586066880,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:299",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587505072,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:89",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589574240,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898656,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071586066880,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071587505072,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071587855680,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071587856010,
      "name": "state_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071589574240,
      "name": "state_store",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579833904,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585912832,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:299",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587273232,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589298816,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833904,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071585912832,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071587273232,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071589298816,
      "name": "state_store",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579887104,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586251600,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:299",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587830240,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590016272,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887104,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586251600,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071587830240,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071590016272,
      "name": "state_store",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t state_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "state_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932864,
      "name": "state_store",
      "external": false,
      "loc": "kernel/power/main.c:599",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586362544,
      "name": "state_store",
      "external": false,
      "loc": "drivers/base/memory.c:299",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587943872,
      "name": "state_store",
      "external": false,
      "loc": "drivers/md/md.c:2844",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_store",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:89",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590066352,
      "name": "state_store",
      "external": false,
      "loc": "net/rfkill/core.c:765",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932864,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586362544,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071587943872,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071588316320,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071588316650,
      "name": "state_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071590066352,
      "name": "state_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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

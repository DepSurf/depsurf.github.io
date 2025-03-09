# Function: <code>wakeup_show</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852176,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:213",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585707168,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:323",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852176,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585707168,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898944,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:213",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585838800,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:323",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898944,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585838800,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933760,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586075248,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:318",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933760,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071586075248,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983888,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586223440,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983888,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071586223440,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032192,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586989472,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032192,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071586989472,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015904,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587074176,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:324",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015904,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587074176,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016672,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586960464,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:324",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016672,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071586960464,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148896,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587526608,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:324",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148896,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587526608,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580291248,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588856576,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:324",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291248,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071588856576,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580501680,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590362624,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:324",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501680,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071590362624,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573456,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:246",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590683120,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:324",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573456,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071590683120,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580637696,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:246",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591044576,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:324",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637696,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071591044576,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491169768,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499032976,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491169768,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446603336499032976,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225194736,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231593212,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225194736,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 3231593212,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284069696,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292201776,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284069696,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 13835058055292201776,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271722342,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271722342,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952624,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585983648,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952624,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071585983648,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890608,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585832912,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890608,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585832912,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944160,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586173456,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944160,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071586173456,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "wakeup_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989520,
      "name": "wakeup_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:214",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586282144,
      "name": "wakeup_show",
      "external": false,
      "loc": "drivers/base/power/sysfs.c:319",
      "file": "drivers/base/power/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989520,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586282144,
      "name": "wakeup_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
ssize_t wakeup_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
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

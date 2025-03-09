# Function: <code>enabled_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797872,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:590",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580893760,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:277",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584239824,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:116",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586126288,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:433",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797872,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071580893760,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584239824,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071586126288,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823808,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:654",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581022880,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:161",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584579840,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:116",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586540016,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:433",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823808,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071581022880,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584579840,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071586540016,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579852848,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:649",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581097520,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:181",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584761296,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:116",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586721744,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:433",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852848,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071581097520,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584761296,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071586721744,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858560,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:498",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581145072,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:148",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584842896,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:120",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586848144,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:433",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858560,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071581145072,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584842896,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071586848144,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899760,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:512",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581267104,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:148",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585263504,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:129",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587335872,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:433",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899760,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071581267104,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585263504,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071587335872,
      "name": "enabled_show",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933632,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:509",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581414112,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:148",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585500432,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:129",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587639168,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:433",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933632,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071581414112,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585500432,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071587639168,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980688,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:509",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581497440,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:158",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585637360,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:129",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587768080,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:433",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980688,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071581497440,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585637360,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071587768080,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580021184,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:354",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581605328,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585860848,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588072832,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021184,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581605328,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585860848,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071588072832,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580072192,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:354",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581675904,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586003440,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588278640,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072192,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581675904,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071586003440,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071588278640,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580131392,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:376",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581893936,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586741264,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589159408,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131392,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581893936,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071586741264,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071589159408,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580109616,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:376",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581939776,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586835424,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:117",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589156368,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:420",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109616,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581939776,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586835424,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071589156368,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580113408,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:375",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581965216,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:176",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586715568,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:117",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589050080,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:420",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113408,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581965216,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586715568,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071589050080,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:375",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582268000,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:176",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586245376,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:916",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587266144,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:117",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589455808,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:166",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:420",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255696,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071592147286,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582268000,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586245376,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587266144,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071589455808,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071589770656,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071592690141,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:375",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582748576,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:175",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587485008,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:927",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588576160,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:117",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590932368,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:166",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:420",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424944,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071593919985,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582748576,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071587485008,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071588576160,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071590932368,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591280640,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071594575319,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:383",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583281600,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:238",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588753584,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:928",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590031248,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:117",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592633424,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:166",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664800,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071595992008,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583281600,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071588753584,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071590031248,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071592633424,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071593029840,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071596320347,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:398",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582688944,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/vmscan.c:5760",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583501072,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:239",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589042048,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:945",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590340528,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:117",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593064064,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:166",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740992,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071596510198,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582688944,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071583501072,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071589042048,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071590340528,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071593064064,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071593481536,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071596849990,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:398",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582859120,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/vmscan.c:5105",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583694544,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:273",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589346752,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:945",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590682016,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:117",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592158608,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/gpu/drm/drm_sysfs.c:252",
      "file": "drivers/gpu/drm/drm_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593815952,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:166",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825952,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071597409071,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582859120,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071583694544,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071589346752,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071590682016,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071592158608,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071593815952,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071594228688,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071597774811,
      "name": "enabled_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493121704,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498799952,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501750120,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493121704,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446603336498799952,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336501750120,
      "name": "enabled_show",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t enabled_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231414560,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234302476,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231414560,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 3234302476,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284190336,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:354",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286599536,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291996400,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295193600,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284190336,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055286599536,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 13835058055291996400,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 13835058055295193600,
      "name": "enabled_show",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t enabled_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276302820,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278153312,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278153312,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446743936276302820,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040928,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:354",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581644640,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585764416,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040928,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581644640,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585764416,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579986240,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:354",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581585504,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585623600,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986240,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581585504,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585623600,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580032464,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:354",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581635952,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585953456,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588215696,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032464,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581635952,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585953456,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071588215696,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
ssize_t enabled_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "enabled_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580083168,
      "name": "enabled_show",
      "external": false,
      "loc": "kernel/livepatch/core.c:354",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581702928,
      "name": "enabled_show",
      "external": false,
      "loc": "mm/huge_memory.c:163",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586061216,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/char/tpm/tpm-sysfs.c:128",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588350992,
      "name": "enabled_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:421",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083168,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581702928,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071586061216,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071588350992,
      "name": "enabled_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct kobj_attribute * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
<b>Param removed. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct kobj_attribute * attr</code> ➡️ <code>struct device_attribute * attr</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

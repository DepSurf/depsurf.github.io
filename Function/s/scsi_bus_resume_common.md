# Function: <code>scsi_bus_resume_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584845744,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:126",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845696,
      "name": "scsi_bus_resume_common.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071584845744,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585208240,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:126",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585208240,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585402944,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:126",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585402944,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585487152,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:126",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487152,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585918688,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:126",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585918688,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166000,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:126",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166000,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586307952,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586307952,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586551456,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:142",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586551456,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586698688,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698688,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587498544,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:147",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587498544,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587565424,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587565424,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587446784,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446784,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588020224,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588020224,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589382197,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:78",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590954757,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:78",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591298421,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:78",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591646629,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:78",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499607408,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499607408,
      "name": "scsi_bus_resume_common",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232063520,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232063520,
      "name": "scsi_bus_resume_common",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292912304,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292912304,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586389168,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389168,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586230480,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230480,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586646656,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646656,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```

```json
{
  "name": "scsi_bus_resume_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586759200,
      "name": "scsi_bus_resume_common",
      "external": false,
      "loc": "drivers/scsi/scsi_pm.c:141",
      "file": "drivers/scsi/scsi_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759200,
      "name": "scsi_bus_resume_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int scsi_bus_resume_common(struct device * dev, int (*)(struct device *, const struct dev_pm_ops *) cb)
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

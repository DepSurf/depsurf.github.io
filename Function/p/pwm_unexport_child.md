# Function: <code>pwm_unexport_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583224887,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:228",
      "file": "drivers/pwm/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:unexport_store"
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
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583532563,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:287",
      "file": "drivers/pwm/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:unexport_store"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668512,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:287",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668512,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708512,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:287",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708512,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583965904,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:287",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965904,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160496,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:289",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160496,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584248240,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:293",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584248240,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584441840,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584441840,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584578576,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578576,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585253616,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585253616,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585410752,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585410752,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585291488,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585291488,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585748176,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748176,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586931088,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586931088,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588087536,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588087536,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588361856,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588361856,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588656576,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588656576,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496814592,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496814592,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230097632,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230097632,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290884352,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290884352,
      "name": "pwm_unexport_child",
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275522746,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275522746,
      "name": "pwm_unexport_child",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533024,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533024,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528736,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528736,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```

```json
{
  "name": "pwm_unexport_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584636512,
      "name": "pwm_unexport_child",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:285",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636512,
      "name": "pwm_unexport_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int pwm_unexport_child(struct device * parent, struct pwm_device * pwm)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

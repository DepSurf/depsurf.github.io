# Function: <code>class_remove_file_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584402144,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:102",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:__class_register"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584402144,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584737881,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:102",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:__class_register"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737488,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584927753,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:102",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:__class_register"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584927360,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585012160,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:102",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012160,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585434400,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:102",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434400,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585677552,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677552,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585807808,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807808,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586041040,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041040,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586188672,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188672,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950384,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:101",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950384,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587035376,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:101",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587035376,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919168,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:101",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919168,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587481584,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:101",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481584,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588804288,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:101",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588804288,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590301600,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:101",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590301600,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void class_remove_file_ns(const struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590621888,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:145",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590621888,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void class_remove_file_ns(const struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590981136,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:145",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_destroy",
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590981136,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498987688,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498987688,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231556120,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231556120,
      "name": "class_remove_file_ns",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292140768,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292140768,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276363334,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276363334,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585949040,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949040,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585798096,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798096,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586138688,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138688,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void class_remove_file_ns(struct class * cls, const struct class_attribute * attr, const void * ns)
```

```json
{
  "name": "class_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586247376,
      "name": "class_remove_file_ns",
      "external": true,
      "loc": "drivers/base/class.c:100",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_class_remove_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247376,
      "name": "class_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class * cls</code> ➡️ <code>const struct class * cls</code>
</li>
</ul>
</details>
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

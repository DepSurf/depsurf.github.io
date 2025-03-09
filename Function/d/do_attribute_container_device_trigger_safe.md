# Function: <code>do_attribute_container_device_trigger_safe</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_attribute_container_device_trigger_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586968900,
      "name": "do_attribute_container_device_trigger_safe",
      "external": false,
      "loc": "drivers/base/attribute_container.c:240",
      "file": "drivers/base/attribute_container.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ],
      "caller_func": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968512,
      "name": "do_attribute_container_device_trigger_safe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_attribute_container_device_trigger_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587054676,
      "name": "do_attribute_container_device_trigger_safe",
      "external": false,
      "loc": "drivers/base/attribute_container.c:240",
      "file": "drivers/base/attribute_container.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ],
      "caller_func": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054288,
      "name": "do_attribute_container_device_trigger_safe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_attribute_container_device_trigger_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586938468,
      "name": "do_attribute_container_device_trigger_safe",
      "external": false,
      "loc": "drivers/base/attribute_container.c:240",
      "file": "drivers/base/attribute_container.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ],
      "caller_func": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938080,
      "name": "do_attribute_container_device_trigger_safe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_attribute_container_device_trigger_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587502052,
      "name": "do_attribute_container_device_trigger_safe",
      "external": false,
      "loc": "drivers/base/attribute_container.c:240",
      "file": "drivers/base/attribute_container.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ],
      "caller_func": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587501664,
      "name": "do_attribute_container_device_trigger_safe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int do_attribute_container_device_trigger_safe(struct device * dev, struct attribute_container * cont, int (*)(struct attribute_container *, struct device *, struct device *) fn, int (*)(struct attribute_container *, struct device *, struct device *) undo)
```

```json
{
  "name": "do_attribute_container_device_trigger_safe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588826000,
      "name": "do_attribute_container_device_trigger_safe",
      "external": false,
      "loc": "drivers/base/attribute_container.c:240",
      "file": "drivers/base/attribute_container.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588826000,
      "name": "do_attribute_container_device_trigger_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int do_attribute_container_device_trigger_safe(struct device * dev, struct attribute_container * cont, int (*)(struct attribute_container *, struct device *, struct device *) fn, int (*)(struct attribute_container *, struct device *, struct device *) undo)
```

```json
{
  "name": "do_attribute_container_device_trigger_safe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590325696,
      "name": "do_attribute_container_device_trigger_safe",
      "external": false,
      "loc": "drivers/base/attribute_container.c:240",
      "file": "drivers/base/attribute_container.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590325696,
      "name": "do_attribute_container_device_trigger_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int do_attribute_container_device_trigger_safe(struct device * dev, struct attribute_container * cont, int (*)(struct attribute_container *, struct device *, struct device *) fn, int (*)(struct attribute_container *, struct device *, struct device *) undo)
```

```json
{
  "name": "do_attribute_container_device_trigger_safe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590645728,
      "name": "do_attribute_container_device_trigger_safe",
      "external": false,
      "loc": "drivers/base/attribute_container.c:240",
      "file": "drivers/base/attribute_container.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590645728,
      "name": "do_attribute_container_device_trigger_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int do_attribute_container_device_trigger_safe(struct device * dev, struct attribute_container * cont, int (*)(struct attribute_container *, struct device *, struct device *) fn, int (*)(struct attribute_container *, struct device *, struct device *) undo)
```

```json
{
  "name": "do_attribute_container_device_trigger_safe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591005824,
      "name": "do_attribute_container_device_trigger_safe",
      "external": false,
      "loc": "drivers/base/attribute_container.c:240",
      "file": "drivers/base/attribute_container.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_device_trigger_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591005824,
      "name": "do_attribute_container_device_trigger_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int do_attribute_container_device_trigger_safe(struct device * dev, struct attribute_container * cont, int (*)(struct attribute_container *, struct device *, struct device *) fn, int (*)(struct attribute_container *, struct device *, struct device *) undo)
```
</details>
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

# Function: <code>__platform_get_irq_byname</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586192613,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586957189,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:303",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587042437,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:455",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586926261,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:454",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587488677,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:434",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588811237,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:438",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590311024,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:438",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590311024,
      "name": "__platform_get_irq_byname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590631520,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:438",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590631520,
      "name": "__platform_get_irq_byname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590990752,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:439",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590990752,
      "name": "__platform_get_irq_byname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498991304,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498991304,
      "name": "__platform_get_irq_byname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231559756,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231559756,
      "name": "__platform_get_irq_byname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292150704,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292150704,
      "name": "__platform_get_irq_byname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276369290,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276369290,
      "name": "__platform_get_irq_byname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585952821,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585802037,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586142629,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
  "name": "__platform_get_irq_byname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586251317,
      "name": "__platform_get_irq_byname",
      "external": false,
      "loc": "drivers/base/platform.c:245",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_byname_optional",
        "drivers/base/platform.c:platform_get_irq_byname"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int __platform_get_irq_byname(struct platform_device * dev, const char * name)
```
</details>
</li>
</ul>

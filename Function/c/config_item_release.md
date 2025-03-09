# Function: <code>config_item_release</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581867136,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:167",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_put"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017088,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:167",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017088,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205504,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:167",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205504,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582300512,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:151",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300512,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466848,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466848,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582565792,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565792,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582874204,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
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
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582947068,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
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
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582974556,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:135",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
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
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583310153,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:135",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
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
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583817082,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:135",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584439018,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:135",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584667786,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:135",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584900554,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:135",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494211332,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227642772,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287905504,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_put"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273669782,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534528,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534528,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471696,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471696,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525008,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525008,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void config_item_release(struct kref * kref)
```

```json
{
  "name": "config_item_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582605680,
      "name": "config_item_release",
      "external": false,
      "loc": "fs/configfs/item.c:137",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605680,
      "name": "config_item_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void config_item_release(struct kref * kref)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void config_item_release(struct kref * kref)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void config_item_release(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void config_item_release(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void config_item_release(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void config_item_release(struct kref * kref)
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

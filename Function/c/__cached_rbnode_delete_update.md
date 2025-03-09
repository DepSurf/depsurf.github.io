# Function: <code>__cached_rbnode_delete_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584273244,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:69",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
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
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584615729,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:81",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584798961,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:81",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584888161,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:82",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova"
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
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304944,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:136",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304944,
      "name": "__cached_rbnode_delete_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545856,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:136",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545856,
      "name": "__cached_rbnode_delete_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670256,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:137",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670256,
      "name": "__cached_rbnode_delete_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585897600,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:135",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585897600,
      "name": "__cached_rbnode_delete_update",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586040448,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:135",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040448,
      "name": "__cached_rbnode_delete_update",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586788960,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:135",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586788960,
      "name": "__cached_rbnode_delete_update",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586973432,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:136",
      "file": "drivers/iommu/iova.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586855000,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:153",
      "file": "drivers/iommu/iova.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587414980,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:150",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:remove_iova"
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
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588730648,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:90",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:remove_iova"
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
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590215624,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:95",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:remove_iova"
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
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590534920,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:95",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:remove_iova"
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
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590890808,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:96",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:remove_iova"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498858528,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:135",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498858528,
      "name": "__cached_rbnode_delete_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585801424,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:135",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801424,
      "name": "__cached_rbnode_delete_update",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585660608,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:135",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660608,
      "name": "__cached_rbnode_delete_update",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585990464,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:135",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585990464,
      "name": "__cached_rbnode_delete_update",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```

```json
{
  "name": "__cached_rbnode_delete_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586098384,
      "name": "__cached_rbnode_delete_update",
      "external": false,
      "loc": "drivers/iommu/iova.c:135",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098384,
      "name": "__cached_rbnode_delete_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain * iovad, struct iova * free)
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

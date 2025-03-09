# Function: <code>free_iova_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584271744,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:218",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:split_and_remove_iova"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584271744,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584616051,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:230",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584612656,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584799283,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:230",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584795840,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584888469,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:206",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884992,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585309497,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:232",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305264,
      "name": "free_iova_mem.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585305296,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585550416,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:232",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546192,
      "name": "free_iova_mem.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585546224,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585674832,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:241",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671264,
      "name": "free_iova_mem.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585671296,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585902398,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:240",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898384,
      "name": "free_iova_mem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585898416,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586045342,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:240",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041248,
      "name": "free_iova_mem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586041280,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586794120,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:240",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790288,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
  "name": "free_iova_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586973332,
      "name": "free_iova_mem",
      "external": false,
      "loc": "drivers/iommu/iova.c:251",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
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
  "name": "free_iova_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586854888,
      "name": "free_iova_mem",
      "external": false,
      "loc": "drivers/iommu/iova.c:305",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
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
  "name": "free_iova_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587416689,
      "name": "free_iova_mem",
      "external": false,
      "loc": "drivers/iommu/iova.c:302",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
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
  "name": "free_iova_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588732323,
      "name": "free_iova_mem",
      "external": false,
      "loc": "drivers/iommu/iova.c:243",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
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
  "name": "free_iova_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590218761,
      "name": "free_iova_mem",
      "external": false,
      "loc": "drivers/iommu/iova.c:248",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_magazine_free_pfns",
        "drivers/iommu/iova.c:iova_magazine_free_pfns",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
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
  "name": "free_iova_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590538145,
      "name": "free_iova_mem",
      "external": false,
      "loc": "drivers/iommu/iova.c:248",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_magazine_free_pfns",
        "drivers/iommu/iova.c:iova_magazine_free_pfns",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
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
  "name": "free_iova_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590894753,
      "name": "free_iova_mem",
      "external": false,
      "loc": "drivers/iommu/iova.c:249",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_magazine_free_pfns",
        "drivers/iommu/iova.c:iova_magazine_free_pfns",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498864992,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:240",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498858936,
      "name": "free_iova_mem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446603336498858992,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585806318,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:240",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585802224,
      "name": "free_iova_mem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585802256,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585665502,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:240",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661408,
      "name": "free_iova_mem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585661440,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585995358,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:240",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585991264,
      "name": "free_iova_mem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585991296,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_iova_mem(struct iova * iova)
```

```json
{
  "name": "free_iova_mem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586103326,
      "name": "free_iova_mem",
      "external": true,
      "loc": "drivers/iommu/iova.c:240",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": [
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586099648,
      "name": "free_iova_mem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586099680,
      "name": "free_iova_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void free_iova_mem(struct iova * iova)
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
void free_iova_mem(struct iova * iova)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void free_iova_mem(struct iova * iova)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void free_iova_mem(struct iova * iova)
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

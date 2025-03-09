# Function: <code>virtio_balloon_report_free_page</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585183995,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:657",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:648",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396144,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071585397361,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585536464,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071585538097,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:705",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249696,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071586256009,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:697",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586367824,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071591446955,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:697",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586257184,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
    },
    {
      "addr": 18446744071591388671,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:697",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767760,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
    },
    {
      "addr": 18446744071592432206,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:697",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588039728,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    },
    {
      "addr": 18446744071594300171,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589418080,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:690",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418080,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589717280,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:690",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589717280,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590054928,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:729",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590054928,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498193048,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498193048,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230955484,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230955484,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291433040,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291433040,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275972806,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275972806,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298496,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071585300129,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585251008,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071585252625,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486864,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071585488497,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```

```json
{
  "name": "virtio_balloon_report_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_balloon_report_free_page",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:652",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585590928,
      "name": "virtio_balloon_report_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
    },
    {
      "addr": 18446744071585596381,
      "name": "virtio_balloon_report_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon * vb)
```
</details>
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

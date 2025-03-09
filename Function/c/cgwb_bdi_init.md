# Function: <code>cgwb_bdi_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580610197,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:665",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_init"
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
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580713698,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:665",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_init"
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
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580779538,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:666",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_init"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817152,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:688",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817152,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907296,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:703",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907296,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581043472,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:683",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043472,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581120624,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:685",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120624,
      "name": "cgwb_bdi_init",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581185248,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:672",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185248,
      "name": "cgwb_bdi_init",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243904,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243904,
      "name": "cgwb_bdi_init",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432960,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:694",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432960,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475488,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:595",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475488,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581496240,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:594",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496240,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756720,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:617",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756720,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582138905,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:606",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_init"
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
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582616345,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:733",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_init"
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
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582825081,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:746",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_init"
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
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582999524,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:741",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_init"
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492642832,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492642832,
      "name": "cgwb_bdi_init",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226484856,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226484856,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285959728,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285959728,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272658394,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272658394,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212752,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212752,
      "name": "cgwb_bdi_init",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159456,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159456,
      "name": "cgwb_bdi_init",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581203952,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203952,
      "name": "cgwb_bdi_init",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267280,
      "name": "cgwb_bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:695",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267280,
      "name": "cgwb_bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int cgwb_bdi_init(struct backing_dev_info * bdi)
```
</details>
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
int cgwb_bdi_init(struct backing_dev_info * bdi)
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

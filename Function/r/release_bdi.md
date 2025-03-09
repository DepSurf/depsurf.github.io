# Function: <code>release_bdi</code>

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
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580816406,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:943",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_put"
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906512,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:958",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906512,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042288,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:956",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042288,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119872,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:959",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119872,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184448,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:946",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184448,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243104,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243104,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432080,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1017",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432080,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581474752,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:887",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474752,
      "name": "release_bdi",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581495504,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:886",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495504,
      "name": "release_bdi",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581755175,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:969",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135808,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:960",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135808,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582613088,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1083",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613088,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582821856,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1096",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582821856,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994432,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1092",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994432,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492642076,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_put"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226484156,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_put"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285958772,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_put"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272657632,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272657632,
      "name": "release_bdi",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211952,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211952,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158672,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158672,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581203152,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203152,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void release_bdi(struct kref * ref)
```

```json
{
  "name": "release_bdi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266496,
      "name": "release_bdi",
      "external": false,
      "loc": "mm/backing-dev.c:1027",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266496,
      "name": "release_bdi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void release_bdi(struct kref * ref)
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void release_bdi(struct kref * ref)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void release_bdi(struct kref * ref)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void release_bdi(struct kref * ref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void release_bdi(struct kref * ref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void release_bdi(struct kref * ref)
```
</details>
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

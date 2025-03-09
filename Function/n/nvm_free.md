# Function: <code>nvm_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584362744,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:477",
      "file": "drivers/lightnvm/core.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584697928,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:599",
      "file": "drivers/lightnvm/core.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void nvm_free(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584889152,
      "name": "nvm_free",
      "external": true,
      "loc": "drivers/lightnvm/core.c:714",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584889152,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584973937,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1019",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_unregister"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585394913,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1025",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_unregister"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585637543,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:880",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_unregister"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void nvm_free(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585763248,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1092",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585763248,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995504,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1094",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995504,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586142688,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1124",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142688,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586897200,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1123",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897200,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982096,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1118",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982096,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586864528,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1118",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864528,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498933520,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1124",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498933520,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231505564,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1124",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231505564,
      "name": "nvm_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292069888,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1124",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292069888,
      "name": "nvm_free",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276319834,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1124",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276319834,
      "name": "nvm_free",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585903056,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1124",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585903056,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586092704,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1124",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586092704,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void nvm_free(struct kref * ref)
```

```json
{
  "name": "nvm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586201312,
      "name": "nvm_free",
      "external": false,
      "loc": "drivers/lightnvm/core.c:1124",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_unregister",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586201312,
      "name": "nvm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void nvm_free(struct nvm_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void nvm_free(struct nvm_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void nvm_free(struct nvm_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kref * ref</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_dev * dev</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void nvm_free(struct kref * ref)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void nvm_free(struct kref * ref)
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

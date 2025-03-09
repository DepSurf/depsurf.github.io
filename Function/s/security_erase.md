# Function: <code>security_erase</code>

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
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586587418,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587371872,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587371872,
      "name": "security_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587432560,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432560,
      "name": "security_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587313680,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587313680,
      "name": "security_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880512,
      "name": "security_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    },
    {
      "addr": 18446744071592523680,
      "name": "security_erase.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230800,
      "name": "security_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    },
    {
      "addr": 18446744071594395161,
      "name": "security_erase.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:346",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590787888,
      "name": "security_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    },
    {
      "addr": 18446744071596258510,
      "name": "security_erase.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:346",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591129376,
      "name": "security_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446744071596786589,
      "name": "security_erase.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:346",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591475056,
      "name": "security_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446744071597695524,
      "name": "security_erase.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499470600,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292748532,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276691292,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586277898,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586096266,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586535386,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
  "name": "security_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586647114,
      "name": "security_erase",
      "external": false,
      "loc": "drivers/nvdimm/security.c:325",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int security_erase(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```
</details>
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

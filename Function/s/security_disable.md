# Function: <code>security_disable</code>

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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586587184,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
int security_disable(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587371440,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
      "addr": 18446744071587371440,
      "name": "security_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int security_disable(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587432128,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
      "addr": 18446744071587432128,
      "name": "security_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587317005,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587884081,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589234368,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int security_disable(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:248",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590790880,
      "name": "security_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071596258678,
      "name": "security_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int security_disable(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:248",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591131552,
      "name": "security_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    },
    {
      "addr": 18446744071596786715,
      "name": "security_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int security_disable(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
```

```json
{
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:248",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591477232,
      "name": "security_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    },
    {
      "addr": 18446744071597695650,
      "name": "security_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499470824,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292748268,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276691526,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586277664,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586096032,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586535152,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
  "name": "security_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586646880,
      "name": "security_disable",
      "external": false,
      "loc": "drivers/nvdimm/security.c:242",
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
int security_disable(struct nvdimm * nvdimm, unsigned int keyid)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int security_disable(struct nvdimm * nvdimm, unsigned int keyid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int security_disable(struct nvdimm * nvdimm, unsigned int keyid, enum nvdimm_passphrase_type pass_type)
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

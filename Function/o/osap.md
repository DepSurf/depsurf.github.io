# Function: <code>osap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582219311,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:394",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582438072,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:394",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582530264,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:394",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582613864,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:394",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582767480,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:394",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582967688,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:393",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583078835,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:396",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583263392,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583369280,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
```

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583702144,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:398",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702144,
      "name": "osap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
```

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823424,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:398",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823424,
      "name": "osap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
```

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848608,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:391",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848608,
      "name": "osap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
```

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211648,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:391",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211648,
      "name": "osap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
```

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584815088,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:391",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815088,
      "name": "osap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
```

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585514288,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:391",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514288,
      "name": "osap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
```

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585746000,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:391",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746000,
      "name": "osap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
```

```json
{
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585993344,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:391",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993344,
      "name": "osap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495118920,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228506528,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289023708,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274372268,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583338016,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583275120,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583321792,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
  "name": "osap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583416816,
      "name": "osap",
      "external": false,
      "loc": "security/keys/trusted.c:398",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_seal"
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
int osap(struct tpm_buf * tb, struct osapsess * s, const unsigned char * key, uint16_t type, uint32_t handle)
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

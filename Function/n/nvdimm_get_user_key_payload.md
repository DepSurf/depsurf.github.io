# Function: <code>nvdimm_get_user_key_payload</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586440534,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_overwrite",
        "drivers/nvdimm/security.c:nvdimm_security_erase",
        "drivers/nvdimm/security.c:nvdimm_security_update",
        "drivers/nvdimm/security.c:nvdimm_security_update",
        "drivers/nvdimm/security.c:nvdimm_security_disable"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_overwrite",
        "drivers/nvdimm/security.c:nvdimm_security_erase",
        "drivers/nvdimm/security.c:nvdimm_security_update",
        "drivers/nvdimm/security.c:nvdimm_security_update",
        "drivers/nvdimm/security.c:nvdimm_security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586437856,
      "name": "nvdimm_get_user_key_payload.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586587095,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584928,
      "name": "nvdimm_get_user_key_payload.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587370785,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:security_disable"
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
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587431473,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:security_disable"
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
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587317076,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312992,
      "name": "nvdimm_get_user_key_payload.part.0.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587884152,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879824,
      "name": "nvdimm_get_user_key_payload.part.0.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
const void * nvdimm_get_user_key_payload(struct nvdimm * nvdimm, key_serial_t id, int subclass, struct key * * key)
```

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589230080,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230080,
      "name": "nvdimm_get_user_key_payload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
const void * nvdimm_get_user_key_payload(struct nvdimm * nvdimm, key_serial_t id, int subclass, struct key * * key)
```

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590787136,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590787136,
      "name": "nvdimm_get_user_key_payload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
const void * nvdimm_get_user_key_payload(struct nvdimm * nvdimm, key_serial_t id, int subclass, struct key * * key)
```

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591128640,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128640,
      "name": "nvdimm_get_user_key_payload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
const void * nvdimm_get_user_key_payload(struct nvdimm * nvdimm, key_serial_t id, int subclass, struct key * * key)
```

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591474320,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591474320,
      "name": "nvdimm_get_user_key_payload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499471116,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499468464,
      "name": "nvdimm_get_user_key_payload.part.0",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292747708,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292744816,
      "name": "nvdimm_get_user_key_payload.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276691010,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276689180,
      "name": "nvdimm_get_user_key_payload.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586277575,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275408,
      "name": "nvdimm_get_user_key_payload.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586095943,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093776,
      "name": "nvdimm_get_user_key_payload.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586535063,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532896,
      "name": "nvdimm_get_user_key_payload.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_get_user_key_payload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586646791,
      "name": "nvdimm_get_user_key_payload",
      "external": false,
      "loc": "drivers/nvdimm/security.c:120",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644624,
      "name": "nvdimm_get_user_key_payload.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
const void * nvdimm_get_user_key_payload(struct nvdimm * nvdimm, key_serial_t id, int subclass, struct key * * key)
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

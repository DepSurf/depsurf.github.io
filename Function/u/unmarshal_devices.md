# Function: <code>unmarshal_devices</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595766755,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:128",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
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
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596695826,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:128",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
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
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603025934,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:128",
      "file": "drivers/firmware/efi/apple-properties.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:126",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
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
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:126",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605121583,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:115",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605121583,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 900
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605160958,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:115",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605160958,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 900
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609430597,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:113",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609430597,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 429
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612504461,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:118",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612504461,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 429
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614646741,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:118",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614646741,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 429
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615604718,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:118",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615604718,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 431
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617414488,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:118",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617414488,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 459
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628167216,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:118",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628167216,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 560
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619934544,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:118",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619934544,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 560
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622245968,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:118",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622245968,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 560
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605051396,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:115",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605051396,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 900
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605016736,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:115",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605016736,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 900
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605137971,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:115",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605137971,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 900
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
int unmarshal_devices(struct properties_header * properties)
```

```json
{
  "name": "unmarshal_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605165152,
      "name": "unmarshal_devices",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:115",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605165152,
      "name": "unmarshal_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 900
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
int unmarshal_devices(struct properties_header * properties)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int unmarshal_devices(struct properties_header * properties)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int unmarshal_devices(struct properties_header * properties)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int unmarshal_devices(struct properties_header * properties)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int unmarshal_devices(struct properties_header * properties)
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

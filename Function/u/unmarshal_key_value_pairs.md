# Function: <code>unmarshal_key_value_pairs</code>

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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595767040,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:57",
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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596695834,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:57",
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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603025942,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:57",
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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603198920,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:59",
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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605009303,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:59",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605121875,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:48",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605161250,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:48",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
```

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609430101,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:48",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609430101,
      "name": "unmarshal_key_value_pairs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 496
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
```

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612503945,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:49",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612503945,
      "name": "unmarshal_key_value_pairs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 516
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
```

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614646225,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:49",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614646225,
      "name": "unmarshal_key_value_pairs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 516
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
```

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615604171,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:49",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615604171,
      "name": "unmarshal_key_value_pairs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 547
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
```

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617413932,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:49",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617413932,
      "name": "unmarshal_key_value_pairs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 556
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
```

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628166400,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:49",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628166400,
      "name": "unmarshal_key_value_pairs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 786
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
```

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619933728,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:49",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619933728,
      "name": "unmarshal_key_value_pairs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 786
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
```

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622245152,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:49",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622245152,
      "name": "unmarshal_key_value_pairs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 786
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605051688,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:48",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605017028,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:48",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605138263,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:48",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
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
  "name": "unmarshal_key_value_pairs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605165444,
      "name": "unmarshal_key_value_pairs",
      "external": false,
      "loc": "drivers/firmware/efi/apple-properties.c:48",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
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
void unmarshal_key_value_pairs(struct dev_header * dev_header, struct device * dev, const void * ptr, struct property_entry * entry)
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

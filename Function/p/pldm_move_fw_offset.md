# Function: <code>pldm_move_fw_offset</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv * data, size_t bytes_to_move)
```

```json
{
  "name": "pldm_move_fw_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585182296,
      "name": "pldm_move_fw_offset",
      "external": false,
      "loc": "lib/pldmfw/pldmfw.c:91",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs"
      ],
      "caller_func": [
        "lib/pldmfw/pldmfw.c:pldm_parse_image",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585181504,
      "name": "pldm_move_fw_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv * data, size_t bytes_to_move)
```

```json
{
  "name": "pldm_move_fw_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585063752,
      "name": "pldm_move_fw_offset",
      "external": false,
      "loc": "lib/pldmfw/pldmfw.c:91",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs"
      ],
      "caller_func": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062944,
      "name": "pldm_move_fw_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv * data, size_t bytes_to_move)
```

```json
{
  "name": "pldm_move_fw_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585510392,
      "name": "pldm_move_fw_offset",
      "external": false,
      "loc": "lib/pldmfw/pldmfw.c:91",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs"
      ],
      "caller_func": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509616,
      "name": "pldm_move_fw_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv * data, size_t bytes_to_move)
```

```json
{
  "name": "pldm_move_fw_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586660984,
      "name": "pldm_move_fw_offset",
      "external": false,
      "loc": "lib/pldmfw/pldmfw.c:91",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs"
      ],
      "caller_func": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586660144,
      "name": "pldm_move_fw_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv * data, size_t bytes_to_move)
```

```json
{
  "name": "pldm_move_fw_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587908968,
      "name": "pldm_move_fw_offset",
      "external": false,
      "loc": "lib/pldmfw/pldmfw.c:91",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs"
      ],
      "caller_func": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587908096,
      "name": "pldm_move_fw_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int pldm_move_fw_offset(struct pldmfw_priv * data, size_t bytes_to_move)
```

```json
{
  "name": "pldm_move_fw_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588181504,
      "name": "pldm_move_fw_offset",
      "external": false,
      "loc": "lib/pldmfw/pldmfw.c:91",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588181504,
      "name": "pldm_move_fw_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int pldm_move_fw_offset(struct pldmfw_priv * data, size_t bytes_to_move)
```

```json
{
  "name": "pldm_move_fw_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588472384,
      "name": "pldm_move_fw_offset",
      "external": false,
      "loc": "lib/pldmfw/pldmfw.c:91",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_components",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header",
        "lib/pldmfw/pldmfw.c:pldm_parse_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472384,
      "name": "pldm_move_fw_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv * data, size_t bytes_to_move)
```
</details>
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

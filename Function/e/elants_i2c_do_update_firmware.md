# Function: <code>elants_i2c_do_update_firmware</code>

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
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586187797,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:620",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
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
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586275963,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:620",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
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
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586739323,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:621",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
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
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587005737,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:620",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
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
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587167177,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:621",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587434059,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:616",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434059,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637115,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:616",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637115,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503233,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:661",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503233,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591574275,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:669",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591574275,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591516873,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:739",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591516873,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592625279,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:783",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592625279,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1125
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594509021,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:783",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594509021,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1143
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592173616,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:783",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592173616,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1695
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592597184,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:783",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592597184,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1712
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593341888,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:783",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593341888,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1712
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587588363,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:616",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587588363,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```

```json
{
  "name": "elants_i2c_do_update_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587699259,
      "name": "elants_i2c_do_update_firmware",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:616",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699259,
      "name": "elants_i2c_do_update_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
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
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client * client, const struct firmware * fw, bool force)
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

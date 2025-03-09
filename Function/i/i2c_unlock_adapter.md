# Function: <code>i2c_unlock_adapter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void i2c_unlock_adapter(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_unlock_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585631680,
      "name": "i2c_unlock_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:993",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read",
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write",
        "drivers/i2c/i2c-core.c:i2c_unlock_adapter",
        "drivers/i2c/i2c-core.c:i2c_transfer",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585631680,
      "name": "i2c_unlock_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_unlock_adapter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584941338,
      "name": "i2c_unlock_adapter",
      "external": false,
      "loc": "include/linux/i2c.h:622",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read",
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586031248,
      "name": "i2c_unlock_adapter",
      "external": false,
      "loc": "include/linux/i2c.h:622",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_slave_register"
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
  "name": "i2c_unlock_adapter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585124647,
      "name": "i2c_unlock_adapter",
      "external": false,
      "loc": "include/linux/i2c.h:658",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read",
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write"
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
  "name": "i2c_unlock_adapter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585205959,
      "name": "i2c_unlock_adapter",
      "external": false,
      "loc": "include/linux/i2c.h:673",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read",
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write"
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
  "name": "i2c_unlock_adapter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585634125,
      "name": "i2c_unlock_adapter",
      "external": false,
      "loc": "include/linux/i2c.h:675",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read",
        "drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write"
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void i2c_unlock_adapter(struct i2c_adapter * adapter)
```
</details>
</li>
</ul>

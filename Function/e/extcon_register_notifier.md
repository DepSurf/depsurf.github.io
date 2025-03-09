# Function: <code>extcon_register_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586112592,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:579",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112592,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586526592,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:427",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586526592,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586709808,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:903",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709808,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586832832,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:917",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586832832,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587320608,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:906",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587320608,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587623504,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:907",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587623504,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587752944,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:907",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587752944,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588057648,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057648,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588263552,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263552,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589143008,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589143008,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589141952,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141952,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589032096,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589032096,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589747792,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589747792,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591260672,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:893",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591260672,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593016000,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:903",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593016000,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593467568,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:913",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593467568,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594214656,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:913",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214656,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501725456,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501725456,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234255396,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234255396,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295174320,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295174320,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278141174,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278141174,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587875248,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875248,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588200608,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588200608,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
```

```json
{
  "name": "extcon_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588335904,
      "name": "extcon_register_notifier",
      "external": true,
      "loc": "drivers/extcon/extcon.c:899",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588335904,
      "name": "extcon_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
int extcon_register_notifier(struct extcon_dev * edev, unsigned int id, struct notifier_block * nb)
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

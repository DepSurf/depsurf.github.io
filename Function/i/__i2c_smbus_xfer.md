# Function: <code>__i2c_smbus_xfer</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587225344,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:542",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587225344,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587491808,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:543",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587491808,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
    },
    {
      "addr": 18446744071587492656,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587694976,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:543",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587694976,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
    },
    {
      "addr": 18446744071587695824,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588563392,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:550",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563392,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
    },
    {
      "addr": 18446744071588564240,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588588096,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:550",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588588096,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    },
    {
      "addr": 18446744071588588880,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588472192,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:544",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472192,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    },
    {
      "addr": 18446744071588472976,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589140400,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:552",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140400,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    },
    {
      "addr": 18446744071589141184,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590591744,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:553",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590591744,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
    },
    {
      "addr": 18446744071590592640,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592250544,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:553",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592250544,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 925
    },
    {
      "addr": 18446744071592251488,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592675776,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:553",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592675776,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
    },
    {
      "addr": 18446744071592676736,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593421168,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:553",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593421168,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 966
    },
    {
      "addr": 18446744071593422160,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500855912,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:543",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500855912,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
    },
    {
      "addr": 18446603336500856872,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233371688,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:543",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233371688,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    },
    {
      "addr": 3233372848,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294322048,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:543",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294322048,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1216
    },
    {
      "addr": 13835058055294323264,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277658256,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:543",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277658256,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    },
    {
      "addr": 18446743936277659020,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587646224,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:543",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646224,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
    },
    {
      "addr": 18446744071587647072,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "__i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587757424,
      "name": "__i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:543",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587757424,
      "name": "__i2c_smbus_xfer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
    },
    {
      "addr": 18446744071587758352,
      "name": "__i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
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

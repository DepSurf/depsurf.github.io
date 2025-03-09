# Function: <code>elants_i2c_send</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586183888,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:156",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586183888,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586272240,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:156",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586272240,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586735632,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:157",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735632,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587002048,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:156",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002048,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587163488,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:157",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587163488,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:152",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587428752,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071587433835,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:152",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587631808,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071587636891,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588502108,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:159",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496608,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588502272,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588530956,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:164",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588525376,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071591573314,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588412732,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:177",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408048,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071591516157,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589081310,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:190",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589075104,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071592624542,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590524266,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:190",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590517648,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071594508258,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592173271,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:190",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592596839,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:190",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593341543,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:190",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:152",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583056,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071587588139,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```

```json
{
  "name": "elants_i2c_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elants_i2c_send",
      "external": false,
      "loc": "drivers/input/touchscreen/elants_i2c.c:152",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693952,
      "name": "elants_i2c_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071587699035,
      "name": "elants_i2c_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
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
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int elants_i2c_send(struct i2c_client * client, const void * data, size_t size)
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

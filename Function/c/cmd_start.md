# Function: <code>cmd_start</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584083920,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1025",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083920,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206624,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206624,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584602496,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1026",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602496,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721344,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1026",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721344,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748720,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1026",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748720,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176976,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1026",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176976,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585913968,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1026",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913968,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586703792,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1066",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703792,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964800,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1074",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:set_lr_boolean_ace",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_columns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964800,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587245648,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1191",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:set_lr_boolean_ace",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:revert_lsp",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_columns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245648,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496077624,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496077624,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229406648,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229406648,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290317424,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290317424,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275148094,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275148094,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175360,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175360,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110608,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110608,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159120,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159120,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
```

```json
{
  "name": "cmd_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584263504,
      "name": "cmd_start",
      "external": false,
      "loc": "block/sed-opal.c:1024",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584263504,
      "name": "cmd_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int cmd_start(struct opal_dev * dev, const u8 * uid, const u8 * method)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

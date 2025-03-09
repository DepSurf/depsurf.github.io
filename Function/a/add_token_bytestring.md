# Function: <code>add_token_bytestring</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583416688,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:567",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:gen_key"
      ],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:gen_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413632,
      "name": "add_token_bytestring.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583597312,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:579",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:gen_key"
      ],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:gen_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593312,
      "name": "add_token_bytestring.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583814092,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:576",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:gen_key"
      ],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:gen_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810240,
      "name": "add_token_bytestring.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583897404,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:576",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:gen_key"
      ],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:generic_lr_enable_disable",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:gen_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893552,
      "name": "add_token_bytestring.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584083856,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:629",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083856,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206560,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206560,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601232,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:632",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601232,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584720080,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:632",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720080,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584747456,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:632",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747456,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176096,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:632",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176096,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585913792,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:632",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913792,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586703600,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:672",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703600,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586963664,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:680",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:set_lr_boolean_ace",
        "block/sed-opal.c:set_lr_boolean_ace",
        "block/sed-opal.c:set_lr_boolean_ace",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963664,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587245456,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:793",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:set_lr_boolean_ace",
        "block/sed-opal.c:set_lr_boolean_ace",
        "block/sed-opal.c:set_lr_boolean_ace",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245456,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496077520,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496077520,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229406572,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229406572,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290317296,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290317296,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275148008,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275148008,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175296,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175296,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110544,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110544,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159056,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159056,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
```

```json
{
  "name": "add_token_bytestring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584263440,
      "name": "add_token_bytestring",
      "external": false,
      "loc": "block/sed-opal.c:630",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:cmd_start",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584263440,
      "name": "add_token_bytestring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void add_token_bytestring(int * err, struct opal_dev * cmd, const u8 * bytestring, size_t len)
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

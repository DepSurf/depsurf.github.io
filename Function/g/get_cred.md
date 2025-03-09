# Function: <code>get_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579508409,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999958,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:get_empty_filp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582203923,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205814,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209024,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505361,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585242403,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586965888,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:init_peercred",
        "net/unix/af_unix.c:unix_stream_connect"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579524399,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158214,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:get_empty_filp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420759,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422794,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582425982,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740775,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585646478,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424116,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:250",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448449,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579548047,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581234934,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:get_empty_filp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512935,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514970,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518158,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835751,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585834162,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587627515,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:241",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579436394,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579534659,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282047,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:get_empty_filp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582594604,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582596506,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582599656,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918173,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585919887,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587776804,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579464666,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579561187,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421567,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:get_empty_filp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582747830,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749674,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582753166,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077133,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586360692,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588305666,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:243",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579478186,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579589386,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579455,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:get_empty_filp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947910,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949728,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953083,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279345,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586617772,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588663735,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:242",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579511514,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579626773,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665228,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583057001,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058832,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583062189,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397656,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586766903,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588877714,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579531130,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579651488,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782276,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033556,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240818,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243274,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246723,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583583947,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587023051,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589319788,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579557274,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579688624,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581854500,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111316,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272664,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583346642,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349098,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583352563,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690219,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587222887,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589544188,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579588730,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579728967,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255674,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079348,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349090,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520589,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:io_queue_async_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583681478,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685093,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583688531,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056243,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588072847,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590528083,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:copy_peercred",
        "net/unix/af_unix.c:init_peercred"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568746,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579708059,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297722,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125780,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400812,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563549,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_register_personality",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:io_grab_identity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583802982,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583806661,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583810115,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584175363,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588118407,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590587507,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:248",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:copy_peercred",
        "net/unix/af_unix.c:init_peercred"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579574282,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579715260,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315290,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582150612,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428064,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582641201,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:io_prep_async_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583827174,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583830917,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583834384,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584202372,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587999350,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590531998,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579647248,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793564,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560538,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467476,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582750816,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582967317,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:io_prep_async_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584190214,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584194037,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584197376,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584587588,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588615682,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589842552,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591339003,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cred * get_cred(const struct cred * cred)
```

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579743397,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900710,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914445,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987653,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298248,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584791316,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584795484,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799209,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585234976,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586022584,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_prep_async_work"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_sq_offload_create"
      ]
    },
    {
      "addr": 18446744071590027903,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591374133,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593008559,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585940864,
      "name": "get_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579874101,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580051736,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349597,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583548213,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583883530,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585488788,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585493116,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585497161,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585930151,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_dup_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585969610,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586759599,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_prep_async_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586819489,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591630335,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593132641,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594898159,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579923957,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106184,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582552447,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583764165,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:init_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584105226,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585720260,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585724693,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585728711,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586162474,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_dup_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586201809,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587026365,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_prep_async_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587085904,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592052877,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593587299,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595289531,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:249",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579963205,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580150458,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582723023,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583966853,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:init_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584321482,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585967380,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971877,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585975939,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586411322,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_dup_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586453886,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587292877,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_prep_async_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587365328,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587412873,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "io_uring/register.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/register.c:__io_uring_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592793036,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594359988,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596130519,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:233",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490712624,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490864924,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493322832,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493652612,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493838360,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495090988,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495093508,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495097460,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495484104,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500308392,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503214228,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/af_unix.c:init_peercred"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224772216,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224884828,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 3226919196,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3227186256,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227346092,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3228484532,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228488052,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228490572,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 3228851232,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 3232777876,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 3235885952,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283536352,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283696720,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286862316,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287243596,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287470464,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288992048,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288996712,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288999996,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289544364,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293623180,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296951596,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271432194,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271521888,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273055808,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273282290,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273418320,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274353602,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274356358,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274358548,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274669128,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277212324,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279248128,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579533578,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579664944,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823236,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080052,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582241400,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583315378,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317834,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321299,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658955,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586928967,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589148556,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579462346,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579593296,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760900,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582017572,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582179128,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252482,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254938,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258403,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583596011,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586870135,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588873548,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579530858,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579662208,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581814548,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071332,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231880,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583299410,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583301642,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305075,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583642731,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587177447,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589585420,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
  "name": "get_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563930,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579696208,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883764,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143092,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582310136,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583394034,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396490,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400035,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583741155,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587284519,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589633215,
      "name": "get_cred",
      "external": false,
      "loc": "include/linux/cred.h:247",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
const struct cred * get_cred(const struct cred * cred)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
const struct cred * get_cred(const struct cred * cred)
```
</details>
</li>
</ul>

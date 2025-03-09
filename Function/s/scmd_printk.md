# Function: <code>scmd_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584841216,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:123",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841216,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585203840,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:123",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585203840,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585398544,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:123",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398544,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585483072,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:123",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483072,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585914512,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:123",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585914512,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161744,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:123",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161744,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586303632,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:123",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303632,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:122",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586549910,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586546784,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697742,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586696928,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587497535,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587495616,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591521317,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587562784,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591463534,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587444144,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:81",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592528723,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588017664,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:83",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594400311,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071589378736,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590949648,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:83",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590949648,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591293712,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:83",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/virtio_scsi.c:virtscsi_abort",
        "drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591293712,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591641648,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:83",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/virtio_scsi.c:virtscsi_abort",
        "drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591641648,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499605904,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499605904,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232062272,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232062272,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292910224,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292910224,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276793526,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276793526,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586388222,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586387408,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586229534,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586228720,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/virtio_scsi.c:virtscsi_abort",
        "drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586645710,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586644896,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void scmd_printk(const char * level, const struct scsi_cmnd * scmd, const char * fmt, void (anon))
```

```json
{
  "name": "scmd_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scmd_printk",
      "external": true,
      "loc": "drivers/scsi/scsi_logging.c:80",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi.c:scsi_log_send",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_tur",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_done",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586758254,
      "name": "scmd_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586757440,
      "name": "scmd_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

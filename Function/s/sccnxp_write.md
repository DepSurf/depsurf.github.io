# Function: <code>sccnxp_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584147334,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:220",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584488995,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:220",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584671123,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:220",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584753186,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:220",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585170471,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:216",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585405527,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:216",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523616,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523616,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742224,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742224,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585884464,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585884464,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586627151,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:235",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud"
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
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586736687,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:235",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud"
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
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586620303,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:235",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587164106,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:235",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157616,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071592453294,
      "name": "sccnxp_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588475130,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:235",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468176,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071594321639,
      "name": "sccnxp_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589909610,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:235",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589902304,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071596237308,
      "name": "sccnxp_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590218730,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:235",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590211504,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071596765475,
      "name": "sccnxp_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590559450,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:235",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_baud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590552144,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071597674109,
      "name": "sccnxp_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498673904,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498673904,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231291660,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231291660,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291848208,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291848208,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276218170,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276218170,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645456,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645456,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510528,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510528,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585834864,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834864,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```

```json
{
  "name": "sccnxp_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942480,
      "name": "sccnxp_write",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:239",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_console_putchar",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_bit",
        "drivers/tty/serial/sccnxp.c:sccnxp_disable_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_enable_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942480,
      "name": "sccnxp_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void sccnxp_write(struct uart_port * port, u8 reg, u8 v)
```
</details>
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

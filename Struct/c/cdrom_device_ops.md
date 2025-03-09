# Struct: <code>cdrom_device_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int n_minors;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int n_minors;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int n_minors;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
    int (*)(struct cdrom_device_info *, void *, u32, u32, u8 *) read_cdda_bpc;
    const int capability;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
    int (*)(struct cdrom_device_info *, void *, u32, u32, u8 *) read_cdda_bpc;
    const int capability;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
    int (*)(struct cdrom_device_info *, void *, u32, u32, u8 *) read_cdda_bpc;
    const int capability;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
    int (*)(struct cdrom_device_info *, void *, u32, u32, u8 *) read_cdda_bpc;
    const int capability;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
    int (*)(struct cdrom_device_info *, void *, u32, u32, u8 *) read_cdda_bpc;
    const int capability;
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
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
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
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cdrom_device_ops {
    int (*)(struct cdrom_device_info *, int) open;
    void (*)(struct cdrom_device_info *) release;
    int (*)(struct cdrom_device_info *, int) drive_status;
    unsigned int (*)(struct cdrom_device_info *, unsigned int, int) check_events;
    int (*)(struct cdrom_device_info *, int) media_changed;
    int (*)(struct cdrom_device_info *, int) tray_move;
    int (*)(struct cdrom_device_info *, int) lock_door;
    int (*)(struct cdrom_device_info *, int) select_speed;
    int (*)(struct cdrom_device_info *, int) select_disc;
    int (*)(struct cdrom_device_info *, struct cdrom_multisession *) get_last_session;
    int (*)(struct cdrom_device_info *, struct cdrom_mcn *) get_mcn;
    int (*)(struct cdrom_device_info *) reset;
    int (*)(struct cdrom_device_info *, unsigned int, void *) audio_ioctl;
    const int capability;
    int (*)(struct cdrom_device_info *, struct packet_command *) generic_packet;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int n_minors</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct cdrom_device_info *, int) media_changed</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct cdrom_device_info *, void *, u32, u32, u8 *) read_cdda_bpc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct cdrom_device_info *, int) select_disc</code>
</li>
</ul>
</details>
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

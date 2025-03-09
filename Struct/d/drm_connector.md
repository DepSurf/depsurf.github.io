# Struct: <code>drm_connector</code>

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
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct fwnode_handle * fwnode;
    struct list_head head;
    struct list_head global_connector_list_entry;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    struct drm_privacy_screen * privacy_screen;
    struct notifier_block privacy_screen_notifier;
    struct drm_property * privacy_screen_sw_state_property;
    struct drm_property * privacy_screen_hw_state_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    const struct drm_edid * edid_override;
    struct mutex edid_override_mutex;
    u64 epoch_counter;
    u32 possible_encoders;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    u8 real_edid_checksum;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
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
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
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
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
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
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct i2c_adapter * ddc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct list_head head;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    bool override_edid;
    uint32_t[3] encoder_ids;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct drm_connector {
    struct drm_device * dev;
    struct device * kdev;
    struct device_attribute * attr;
    struct fwnode_handle * fwnode;
    struct list_head head;
    struct list_head global_connector_list_entry;
    struct drm_mode_object base;
    char * name;
    struct mutex mutex;
    unsigned int index;
    int connector_type;
    int connector_type_id;
    bool interlace_allowed;
    bool doublescan_allowed;
    bool stereo_allowed;
    bool ycbcr_420_allowed;
    enum drm_connector_registration_state registration_state;
    struct list_head modes;
    enum drm_connector_status status;
    struct list_head probed_modes;
    struct drm_display_info display_info;
    const struct drm_connector_funcs * funcs;
    struct drm_property_blob * edid_blob_ptr;
    struct drm_object_properties properties;
    struct drm_property * scaling_mode_property;
    struct drm_property * vrr_capable_property;
    struct drm_property * colorspace_property;
    struct drm_property_blob * path_blob_ptr;
    struct drm_property * max_bpc_property;
    struct drm_privacy_screen * privacy_screen;
    struct notifier_block privacy_screen_notifier;
    struct drm_property * privacy_screen_sw_state_property;
    struct drm_property * privacy_screen_hw_state_property;
    uint8_t polled;
    int dpms;
    const struct drm_connector_helper_funcs * helper_private;
    struct drm_cmdline_mode cmdline_mode;
    enum drm_connector_force force;
    const struct drm_edid * edid_override;
    struct mutex edid_override_mutex;
    u64 epoch_counter;
    u32 possible_encoders;
    struct drm_encoder * encoder;
    uint8_t[128] eld;
    bool[2] latency_present;
    int[2] video_latency;
    int[2] audio_latency;
    struct i2c_adapter * ddc;
    int null_edid_counter;
    unsigned int bad_edid_counter;
    bool edid_corrupt;
    u8 real_edid_checksum;
    struct dentry * debugfs_entry;
    struct drm_connector_state * state;
    struct drm_property_blob * tile_blob_ptr;
    bool has_tile;
    struct drm_tile_group * tile_group;
    bool tile_is_single_monitor;
    uint8_t num_h_tile;
    uint8_t num_v_tile;
    uint8_t tile_h_loc;
    uint8_t tile_v_loc;
    uint16_t tile_h_size;
    uint16_t tile_v_size;
    struct llist_node free_node;
    struct hdr_sink_metadata hdr_sink_metadata;
}
```
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct i2c_adapter * ddc</code> ➡️ <code>struct i2c_adapter * ddc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct i2c_adapter * ddc</code> ➡️ <code>struct i2c_adapter * ddc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

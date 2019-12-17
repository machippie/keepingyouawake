
## Default Variables

### keepingyouawake_activate_on_launch

Activate on launch

#### Default value

```yaml
keepingyouawake_activate_on_launch: false
```

### keepingyouawake_batter_threshold_value

Battery threshold value

#### Default value

```yaml
keepingyouawake_batter_threshold_value: 10
```

### keepingyouawake_battery_threshold_enabled

Battery threshold enabled

#### Default value

```yaml
keepingyouawake_battery_threshold_enabled: true
```

### keepingyouawake_launch_at_login

Launch at login

#### Default value

```yaml
keepingyouawake_launch_at_login: true
```

### keepingyouawake_menubar_highlight_disabled

Menubar highlight disabled

#### Default value

```yaml
keepingyouawake_menubar_highlight_disabled: false
```

### keepingyouawake_notifications_enabled

Notifications enabled

#### Default value

```yaml
keepingyouawake_notifications_enabled: true
```

### keepingyouawake_started

Start in background after install

#### Default value

```yaml
keepingyouawake_started: true
```

### keepingyouawake_time_interval

Time interval

#### Default value

```yaml
keepingyouawake_time_interval: 0
```

### keepingyouawake_user

User to run user-specific commands

#### Default value

```yaml
keepingyouawake_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger

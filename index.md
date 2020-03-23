
## Default Variables

### keepingyouawake_started

Start in background after install

#### Default value

```yaml
keepingyouawake_started: true
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

### 1.4
- Desktop/Console client: Windows: fix startup registration

### 1.3
- Daemon: fix settings re-apply on wake from sleep, if enabled
- libPWTShared: minor optimizations

### 1.2
- Desktop client: fix sanitizer memory leak warnings
- Console client: use the correct invalid value for the joystick ID
- Console client: update SDL to 3.4.0
- Daemon: fix various warnings and errors

### 1.1

- Fix GPU name being shown as generic vendor string instead of the marketing name (for GPUs in database)
- Add built-in input ranges for GPD Win 5 (stock and recommended values by GPD)
- AMD: RyzenAdj: set 0 as minimum for vrm current sliders
- libPWTClientService: fix DAEMON_CMD_FAIL cmd not stopping the failed cmd timer (fixes log spam in clients)
- AMD: RyzenAdj: disable curve optimizer for strix halo (tested, command is rejected, no known report of that being correct)
- Console client: fix top section title not being shown once hidden by scrolling using gamepad navigation
- Console/Desktop client: Intel: HWP: add 'Prefer OS setting' checkbox
- CLI client: AMD: RyzenAdj: set settings with no read command as ignored unless defined by the user to avoid potential issues (like writing bad values)
- Console/Desktop client: AMD: RyzenAdj: add enable checkbox to settings with no read command to avoid potential issues (like writing bad values)
- Attempt to fix checkboxes when display scaling is set

### 1.0

- First public release

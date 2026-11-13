# dalamud-plugins

Custom Dalamud plugin repository. The plugin list (`repo.json`) and the release zips are published here; the plugin source lives elsewhere.

## Install

1. In game: `/xlsettings` → **Experimental** → **Custom Plugin Repositories**. Add this URL, tick **Enabled**, then **Save and Close**:

   ```
   https://raw.githubusercontent.com/h1arc/dalamud-plugins/main/repo.json
   ```

2. `/xlplugins` → find the plugin → **Install**.

## Testing builds

1. `/xlsettings` → **Experimental** → turn on **Get plugin testing builds**.
2. `/xlplugins` → **Installed Plugins** → right-click the plugin → **Receive plugin testing versions**.
   (Not installed yet: right-click it under All Plugins → **Install testing version**.)

Testing builds are published on every merge; stable builds are promoted from tested testing builds.

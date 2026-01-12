# UI Navigation & Activity Flow

The application follows a multi-activity architecture.

## Navigation Principles

- Stateless navigation between screens
- Explicit intent-based transitions
- Game restarts without app reloads

## Key Activities

- MainActivity: Home menu
- GameActivity: AI gameplay
- LocalGameActivity: Local multiplayer
- BluetoothActivity: Bluetooth pairing & multiplayer
- StatsActivity: Game history and statistics

Navigation flows are illustrated in `architecture/activity-flow.png`.

# Bug Report
## Description

When archiving the test app, the process works fine for the iOS app but results in a compiler error when archiving for Catalyst.

## Possible Cause: Conflict with Other Libraries
This issue occurs when using `swift-composable-architecture` and `MetaCodable` together.

If either of these libraries is removed, the archiving process works without issues.

# Snapshots

![img](./CleanShot%202024-11-28%20at%2011.26.57@2x.png)
![img](./CleanShot%202024-11-28%20at%2011.23.33@2x.png)

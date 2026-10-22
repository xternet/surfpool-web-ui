# Unofficial historical Studio preview

This branch contains the combined SVM Replay historical UI, not an upstream
Studio release. Proposed upstream PRs remain separate and unmerged.

Revision 2 ignores delayed events from replaced WebSockets, preserving the
current connection and its subscriptions in both normal and historical mode.
It adds no replay engine or server RPC methods to the browser.

[Built assets and source pins](https://github.com/xternet/surfpool-web-ui/releases/tag/svm-replay-0.2.0-preview.2)

The matching unofficial Surfpool binaries embed these assets. Use that paired
preview rather than combining unrelated server and UI versions.

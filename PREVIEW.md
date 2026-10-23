# Unofficial historical Studio preview

This branch contains the combined SVM Replay historical UI, not an upstream
Studio release. Proposed upstream PRs remain separate and unmerged.

Revision 2 ignores delayed events from replaced WebSockets, preserving the
current connection and its subscriptions in both normal and historical mode.
It adds no replay engine or server RPC methods to the browser.

The latest source also escapes account-derived parsed and hex text at inspector
markup boundaries, preserving formatting and expand state. Real-component and
custom-element DOM regressions cover those paths; this is not a new browser or
platform qualification.

[Earlier built assets and source pins](https://github.com/xternet/surfpool-web-ui/releases/tag/svm-replay-0.2.0-preview.2)

Those pinned assets and the matching Surfpool downloads predate this latest
source-only rendering repair. They have not been replaced. Review/build this
branch for the updated source; publishing a new paired asset/binary is separate.

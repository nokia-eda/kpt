# fluentd (legacy kpt package)

This directory is **kept in the repo for upgrades only**. It is **not** applied by default when installing EDA.

Clusters that previously installed the legacy fluentd + fluent-bit stack via kpt should **remove** that inventory during upgrade (for example with `kpt live destroy` from a checkout or build tree that still maps to this package path and its resource group), following your release notes and runbooks.

See the `Kptfile` metadata and your cluster’s kpt inventory for the exact group name and workflow.

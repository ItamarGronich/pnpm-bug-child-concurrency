This is a reproduction repo for pnpm.

There's a bug when you use `child-concurrency` with `shared-workspace-lockfile=false`.

It seems that the value for `child-concurrency=10` get's parsed as a string instead of a number.

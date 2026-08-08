# db-update-test

Scratch repository for exercising the in-app database update flow end to end
without publishing anything to a production `{city}busmap-database` repo, where
real users would be offered it.

Point a debug build at it with the launch argument:

    -databaseRepo junebot-bus/db-update-test

Contents are a copy of DC's bundled store with a deliberately high version
number, so any build will see an update available. Safe to delete.

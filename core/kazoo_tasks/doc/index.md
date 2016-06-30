/*
Section: Kazoo Tasks
Title: Kazoo Tasks
Language: en-US
*/

# Kazoo Tasks

Run background jobs on Kazoo clusters.

Tasks can take CSV, JSON data or nothing at all as input & will generate a CSV output.

`kazoo_tasks` discovers the different kinds of tasks provided by Kazoo applications on a cluster
by sending an `help_req` event.

An app can listen to the `help_req` event from `tasks` and then reply with the kinds of tasks it is offering.


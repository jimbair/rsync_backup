# rsync_backup
A shell script to backup linux systems via rsync onto our Synology

Nothing wild; it started with excludes from the Arch Wiki and I added a few
that met my needs. This script dynamically reads the SSH config and runs rsync
across all hosts it finds. Also, you can pass it the name of a specific server
for a single rsync backup run if troubleshooting your excludes.

# Log Archiver

A bash script that compresses and archives log directories on a schedule.

## Features

- Compresses any directory into a timestamped `.tar.gz` archive
- Logs all actions to `archive.log`
- Can be run manually or scheduled with cron
- Works on any Linux system

## Usage

```bash
./archive.sh /path/to/directory
```
## Cron Schedule examples
| Schedule | Cron Expression |
|----------|----------------|
| Every 6 hours | `0 */6 * * *` |
| Daily at 2 AM | `0 2 * * *` |
| Weekly on Sunday | `0 0 * * 0` |
| Every hour | `0 * * * *` |

## Installation
```bash
git clone https://github.com/majortife/log-archiver.git
cd log-archiver
chmod +x archive.sh
```
https://roadmap.sh/projects/log-archive-tool

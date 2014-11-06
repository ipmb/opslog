A simple script that saves and retreives messages in ElasticSearch

Inspired by https://code.google.com/p/opslog/

## Usage

    opslog add "Running low on disk space, I pruned some files in /tmp"

    opslog list  # list all opslogs for this host

## Configuration

    $ cat /etc/opslog.conf
    elasticsearch_url: http://your-es-host:9100/opslog/log

See `opslog --help` for more options.

The only dependency is Python. Copy `opslog` to your `$PATH` and make sure it's executable.
